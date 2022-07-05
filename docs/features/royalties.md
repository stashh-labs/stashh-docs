---
title: Royalties
---

# Royalties

Royalties are an optional payment made to the creator of a sNFT when it is sold on the secondary market. Royalties are expressed as a percentage of the sale price. For example, 10%.

A sNFT can have up to 5 royalty addresses, and the sum of all 5 royalty percentages cannot be greater than 100%.

## Modifying Royalties

It is possible to change Royalties after they have been configured if all of the following conditions are met...

- The sNFT is not listed for sale
- The wallet making the change is the Creator of the sNFT
- The wallet making the change is the Owner of the sNFT

In practice this makes it hard to change the royalty on a sNFT after it has been sold.

## Payment

Royalty payments are deducted from the sellers proceeds after Sales Fees have been accounted for then sent to each configured address instantly.

## Calculation

Royalties are calculated on the sale price after any platform fees have been deducted.

## Currency

Royalty payments are made in the same SNIP20 currency as the sale. This may not be the same currency as the Primary Listing.

## Off Platform & OTC Sales

Royalties are processed by the Stashh sales contracts. If a sale is handled by a third party contract or an OTC dealer they may choose to ignore the royalty payment.

## Privacy

Royalty percentages and the number of royalty wallets attached to a sNFT are always public.

Royalty addresses are visible to anyone who is both the creator and owner of an NFT as well as anyone (or any contract) that has permissions to transfer the sNFT to another wallet.