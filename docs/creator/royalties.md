---
title: Royalties
---

# Royalties

!!! note
    Royalties can only be set by the wallet that is both the Owner and Creator of the sNFT

!!! tip
    If you configure royalties on your Collection they will be automatically applied when you enable royalties on a sNFT in the collection.

Royalties are an optional payment made to the creator of a sNFT when it is sold on the secondary market. Royalties are expressed as a percentage of the sale price. For example, 10%.

A sNFT can have up to 5 royalty addresses, and the sum of all 5 royalty percentages cannot be greater than 100%.

## Configure Royalties

1. Create a new sNFT or edit an existing sNFT
2. While creating a new sNFT enable the **Enable Royalties** toggle
2. Input the Wallet Address the royalty should be paid to
3. Enter the percentage of the sales price that should be sent to this wallet

## Change Royalties

It is possible to change Royalties after they have been configured if all of the following conditions are met...

- The sNFT is not listed for sale
- The wallet making the change is the Creator of the sNFT
- The wallet making the change is the Owner of the sNFT

In practice this makes it hard to change the royalty on a sNFT after it has been sold.

To change the royalties on an existing sNFT that meets the conditions above...

1. Navigate to the sNFT you want to change the royalties for
2. Wait for Stashh to confirm you are the owner of the sNFT
3. Scroll down and locate the **Royalties** panel
    1. To add a new royalty recipient click **Add Recipient** then enter the address and percentage
    2. To remove an existing royalty click the Remove icon :fontawesome-solid-circle-minus: next to the royalty you want to remove
    3. To update an existing royalty find it in the list then enter the new address and percentage
4. Click the **Update** button
5. Your wallet will ask you to Execute a Contract. Click **Approve**

    === "Keplr"

        ![Keplr requesting to update Royalties](../images/keplr-set-royalty-info.png#pop)

## Payment

Royalty payments are deducted from the proceeds after Sales Fees have been accounted for then sent to each configured address instantly.

## Calculation

Royalties are calculated on the sale price after platform fees have been deducted.

## Currency

Royalty payments are made in the same SNIP20 currency as the sale. This may not be the same currency as the Primary Listing.

## Off Platform & OTC Sales

Royalties are processed by the Stashh sales contracts. If a sale is handled by a third party contract or an OTC dealer they may choose to ignore the royalty payment.