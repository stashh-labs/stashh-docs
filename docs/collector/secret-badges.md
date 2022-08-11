---
title: Secret Badges
---

# Secret Badges

Secret Badges (or sBadges) are privacy-preserving collectable digital assets issued as unique Secret NFTs (sNFTs) on Secret Network. sBadges can represent digital mementos, exclusive content, recognition of achievements, digital entry passes, or anything else you can imagine.

Because they are "secret" and privacy-preserving by default, sBadges are much more powerful than NFTs on other blockchains. They allow for **private or public ownership**, meaning you can choose to display your sBadges to other users or not. They also allow for **private or public metadata**, meaning your sBadges can have hidden properties inside them. Claiming a Secret Badge is the only way to decrypt the private metadata and see what's hidden inside. Secret Badges can also be transferable (letting you trade them or send them to new wallets) or **non-transferable** (associated with the original account forever).

We believe introducing this kind of flexibility is critical to 100x'ing NFT utility and use cases! That's why Stashh is constantly trying to expand what's possible with Secret Badges and Secret NFTs more generally.

## Claim a Secret Badge

[](/images/claim-control-default.png#pop)

There's a few different ways to claim a Secret Badge that someone else has created. Here's the most common ones:

### Claim Code
Claim codes allow you to claim a Secret Badge without paying for gas. This is great if you've just created your very first wallet or if you're claiming your very first sBadge!

1. Navigate to the badge you want to claim
2. Enter your claim code into the **Claim Code** field
3. Click the **Claim Badge** button

!!! tip
    A link to a Secret Badge can also auto-populate a claim code! This is a great way to simplify the claiming experience.

#### Walletless Minting

No wallet? No problem. If you find a badge you want but haven't installed a wallet yet, Stashh will generate a wallet on your device and download the Recovery Phrase to your device so you can access it later.

!!! warning
    If you lose this Recovery Key, Stashh has no way to recover it - so your badge will be permanently lost!

1. Navigate to the badge you want to claim
2. Enter your claim code into the **Claim Code** field
3. Click the **Create Wallet & Claim Badge** button

The badge will be minted into the new wallet address. When convenient, you can set up your wallet by importing that Recovery Key.

### Whitelist

Instead of using claim codes, badge creators can opt to whitelist certain addresses who will then have access to claim the badge. Of course, before you can claim a badge you are whitelisted for, you first need to check you are on the whitelist...

1. Navigate to the badge you want to claim.
2. Click the **Check If I Am Whitelisted** button.
3. A window will appear asking you to create a permit. Click the **Create Permit** button.
4. Your wallet will ask to create a Permit. Click **Approve**.

    === "Keplr"

        ![Keplr requesting a Permit](/images/keplr-query-permit.png#pop)

5. Once the permit has been created, Stashh will check if you are on the whitelist and show the number of badges you can claim.

    === "Not Whitelisted"

        If you are not on the whitelist, Stashh will show **Not Whitelisted**. If you think this is a mistake, you should contact the creator of the collection.

        ![The claim control when you are not whitelisted](/images/claim-control-not-whitelisted.png#pop)

    === "Whitelisted"

        If you are whitelisted, Stashh will show **Whitelisted** and the number of claims you can make.

        ![The claim control when you are whitelisted](/images/claim-control-whitelisted.png#pop)

6. Click **Claim Badge**.
7. Your wallet will ask to perform a mint transaction. Click **Approve**.

    === "Keplr"

        ![Keplr requesting to Mint](/images/keplr-mint-txn.png#pop)

## View a sBadge

Viewing a sBadge works just like [viewing a sNFT](./view-nfts.md)

## Burn a sBadge

Burning a sBadge works just like burning a sNFT. If the sBadge is non-transferable, then burning is enabled even if the Creator has disabled burning.

## Transfer a sBadge

Transferring a sBadge to another wallet works just like transferring a sNFT, though sBadges are more likely to be non-transferable.

!!! warning
    If a sBadge is non-transferable there is no way to sell it or transfer it to a different wallet.
    
**Happy badge hunting!**
