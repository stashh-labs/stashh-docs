---
title: Royalties
---

# Royalties

!!! note
    Royalties can be set only by the wallet that is both the Owner and Creator of a sNFT

You can configure up to 5 royalty addresses on each sNFT. To configure royalties on one of your sNFTs

!!! tip
    If you configure royalties on your Collection they will be automatically applied when you enable royalties on a sNFT in the collection.

1. Enable the **Enable Royalties** toggle
2. Input the Wallet Address the royalty should be paid to
3. Enter the percentage of the sales price that should be sent to this wallet

## Payment

Royalty payments are deducted from the proceeds after Sales Fees have been accounted for then sent instantly to the configured wallets.

## Currency

Royalty payments are made in the same SNIP20 currency as the sale. This may not be the same currency as the Primary Listing.

## Changing Royalties

It is possible to change Royalties after they have been configured if all of the following conditions are met...

1. The sNFT is not listed for sale
2. The wallet making the change is the Creator of the sNFT
3. The wallet making the change is the Owner of the sNFT

In practice this makes it hard to change the royalty on a sNFT after it has been sold.

## Off Platform & OTC Sales

Royalties are processed by the Stashh sales contracts. If a sale is handled by another contract external to Stashh it could choose to ignore the royalty payment.