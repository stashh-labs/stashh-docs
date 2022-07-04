---
title: Secret Badges
---

# Secret Badges

Secret Badges (or sBadges) are privacy-preserving collectable digital assets issued as unique sNFTs on Secret Network. sBadges can represent digital mementos, exclusive content, recognition of achievements, digital entry passes, or anything else you can imagine.

## Claim a sBadge

[](/images/claim-control-default.png#pop)

### Claim Code

!!! tip
    If you claim a badge using a claim code you don't pay for gas

1. Go to the badge you want to claim
2. Enter your claim code into the **Claim Code** field
3. Click the **Claim Badge** button

#### Walletless Minting

You can claim a badge using a claim code without having a wallet. In this situation Stashh will generate a wallet on your device and download the Recovery Phrase to your device so you can access it later.

!!! warning
    If you loose the Recovery Key Stashh has no way to recover it so your badge will be permanently lost!

1. Go to the badge you want to claim
2. Enter your claim code into the **Claim Code** field
3. Click the **Create Wallet & Claim Badge** button

### Whitelist

Before you can claim a badge you are whitelisted for you first need to check you are on the whitelist...

1. Go to the badge you want to claim
2. Click the **Check if I am Whitelisted** button
3. A window will appear asking you to create a permit. Click the **Create Permit** button.
4. Your wallet will ask to create a Permit. Click **Approve**

    === "Keplr"

        ![Keplr requesting a Permit](/images/keplr-query-permit.png#pop)

5. Once the permit has been created Stashh will check if you are on the whitelist and show the number of badges you can claim.

    === "Not Whitelisted"

        If you are not on the whitelist Stashh will show **Not Whitelisted**. If you think this is a mistake you should contact the Creator of the collection.

        ![The claim control when you are not whitelisted](/images/claim-control-not-whitelisted.png#pop)

    === "Whitelisted"

        If you are whitelisted Stashh will show **Whitelisted** and the number of claims you can make.

        ![The claim control when you are whitelisted](/images/claim-control-whitelisted.png#pop)

6. Click **Claim Badge**
7. Your wallet will ask to perform a mint transaction. Click **Approve**

    === "Keplr"

        ![Keplr requesting to Mint](/images/keplr-mint-txn.png#pop)

## View a sBadge

Viewing a sBadge works just like [viewing a sNFT](./view-nfts.md)

## Burn a sBadge

Burning a sBadge works just like burning a sNFT. If the sBadge is non-transferable then burning is enabled even if the Creator has disabled burning.

## Transfer a sBadge

Transferring a sBadge to another wallet works just like transferring a sNFT, though sBadges are more likely to be non-transferable. If a sBadge is non-transferable there is no way to sell it or transfer it to a different wallet.