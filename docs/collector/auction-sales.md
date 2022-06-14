---
title: Auction Sales
---

# Auction Sale

An auction is a mechanism to find the optimal price for your sNFT. When you list an sNFT for sale as an Auction on Stashh it will be shown in the marketplace for a set period of time during which potential buyers place bids.

There are many different kinds of Auction. Stashh currently supports English auctions where the seller sets an initial price then buyers bid incrementally until a timer runs out at which point the highest bid wins.

Auction sales work within our standard Fees and Royalty schedule.

## Create an Auction

1. Select **Auction** from the Sale Type dropdown menu
2. Select the Currency you want to sell for from the **Currency** dropdown menu.
3. Enter the amount you want bidding to start at into the **Minimum Bid** field.
4. If you want to set a Buy Now price enter it into the **Optional Ending Price** field
5. Either set the date and time you want the auction to end on by clicking the **Select End Date** field or use one of the default duration buttons to quickly set a duration.
6. If you want to add any additional details about the sNFT enter them into the **Sales Pitch** field. 
6. Click the checkbox confirming that you understand that selling a sNFT will make your wallet address publicly visible
7. Click the **List for Sale** button.
8. Your wallet will ask you to Execute a Contract. Click **Approve**

    === "Keplr"

        ![Keplr requesting to Execute a Contract](../images/keplr-execute-contract-auction-create.png#zoom)

!!! note 
    When you list a sNFT for sale it will be moved from your wallet into the auction contract escrow.

## Cancel an Auction

!!! warning
    Once a bid has been placed it is impossible to cancel an auction

1. Navigate to the sNFT you want to take off sale
2. Wait for Stashh to confirm your ownership.
3. Click the **Cancel Auction** button
4. Your wallet will ask you to Execute a Contract. Click **Approve**

    === "Keplr"

        ![Keplr requesting to Execute a Contract](../images/keplr-execute-contract-auction-cancel.png#zoom)
    
!!! tip
    When you cancel an auction your sNFT is automatically returned to your wallet.

## Winning an Auction

If you are the highest bidder when an Auction closes the transaction will automatically be finalised by the Auction contract

If you already have a Permit or a Viewing Key for the Collection the sNFT is in you can go to your Dashboard and view it immediately. If not, please follow the instructions for [Viewing Your sNFTs](view-your-nfts.md).

## Buy Now Price

The Buy Now price is an optional price you can set at which the auction will instantly end if met or exceeded. An auction will end the moment someone places a bid that is equal to or greater than the Buy Now price.

To set a Buy Now price enter the amount you are willing to accept into the **Optional Ending Price** field when you are creating an Auction. If this field is left blank the Buy Now option will not be enabled.

## Bid on an Auction

To bid on a sNFT...

1. Enter the amount of your bid into the **Amount** field
2. Click the **Bid Now** button.
4. Your wallet will ask you to Execute a Contract. Click **Approve**

    === "Keplr"

        ![Keplr requesting to Execute a Contract](../images/keplr-execute-contract-auction-bid.png#zoom)

!!! warning 
    When you bid on a sNFT the amount of your bid will be moved from your wallet into the auction contract escrow. This amount will be automatically returned to your wallet if you are outbid.

## Minimum Bid Increment

To prevent dust bids there is a minimum bid increment of 1% of the current price.

## Time Limit & Extensions

Auctions have a time limit during which bidders place their bids. When the time limit runs out the sNFT will be sold to the highest bidder.

If a bid is placed in the final 15 minutes of an auction the time limit will be extended by 15 minutes to prevent sniping and other forms of price manipulation.
