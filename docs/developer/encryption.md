---
title: Content Encryption
---

# Encrypting Content for Stashh

Stashh uses `AES-256-GCM` to encrypt and decrypt content using a symmetric key.

## On Platform

When a sNFT is created on Stashh encryption and decryption are handled automatically.

Private assets are encrypted when they are uploaded, and the decryption key is automatically embedded into the sNFT when it is created. Similarly, when an owner views their sNFT the private assets are seamlessly decrypted and displayed.

Public assets are uploaded unencrypted.

## Off Platform

sNFTs created outside of Stashh can benefit from automatic decryption on Stashh as long as `AES-256-GCM` is used and the key is embedded into the [MediaFile Extension](`https://github.com/baedrik/snip721-reference-impl#mediafile`) correctly

``` json
{
 "file_type": "...",
 "extension": "...",
 "authentication": {
  "key": "KEY_GOES_HERE"
 },
 "url": "..."
}
```

Stashh will detect that the MediaFile element contains a key then attempt to use that key to decrypt the content before displaying it.

## Reference Implementation

Stashh uses the following TypeScript implementation to encrypt and decrypt assets.

``` ts
const ALGORITHM = "aes-256-gcm";
const IV_LENGTH = 16;

export const encrypt = (dataBuffer: Buffer, key: string): Buffer => {
  // Create an initialization vector
  const iv = crypto.randomBytes(IV_LENGTH);
  // Create cipherKey
  const cipherKey = Buffer.from(key);
  // Create cipher
  const cipher = crypto.createCipheriv(ALGORITHM, cipherKey, iv);

  const encryptedBuffer = Buffer.concat([
    cipher.update(dataBuffer),
    cipher.final(),
  ]);
  const authTag = cipher.getAuthTag();
  let bufferLength = Buffer.alloc(1);
  bufferLength.writeUInt8(iv.length, 0);

  return Buffer.concat([bufferLength, iv, authTag, encryptedBuffer]);
};

export const decrypt = (dataBuffer: Buffer, key: string): Buffer => {
  // Create cipherKey
  const cipherKey = Buffer.from(key);
  // Get iv and its size
  const ivSize = dataBuffer.readUInt8(0);
  const iv = dataBuffer.slice(1, ivSize + 1);
  // Get authTag - is default 16 bytes in AES-GCM
  const authTag = dataBuffer.slice(ivSize + 1, ivSize + 17);

  // Create decipher
  const decipher = crypto.createDecipheriv(ALGORITHM, cipherKey, iv);
  decipher.setAuthTag(authTag);

  return Buffer.concat([
    decipher.update(dataBuffer.slice(ivSize + 17)),
    decipher.final(),
  ]);
};
```
