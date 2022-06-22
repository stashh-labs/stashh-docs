---
title: Auction
---

# Auction

An auction is a mechanism to find the optimal price for your sNFT. When you list an sNFT for sale as an Auction on Stashh it will be listed for a period of time during which potential buyers place bids.

There are many different kinds of Auction. Stashh currently supports English auctions where the seller sets an initial price then buyers bid incrementally until a timer runs out at which point the highest bid wins.

Fixed Price sales work within our standard [Fees](./fees.md) and Royalty schedule.

## Winning an Auction

If you are the highest bidder when an Auction closes the transaction will automatically be finalised by the Auction contract and the sNFT will be sent to you.

If you already have a Permit or a Viewing Key for the Collection the sNFT is in you can go to your Dashboard and view it immediately. If not, please follow the instructions for [Viewing Your sNFTs](view-your-nfts.md).

## Buy Now Price

The Buy Now price is an optional price you can set at which the auction will instantly end if met or exceeded. An auction will end the moment someone places a bid that is equal to or greater than the Buy Now price.

To set a Buy Now price enter the amount you are willing to accept into the **Optional Ending Price** field when you are creating an Auction. If this field is left blank the Buy Now option will not be enabled.

## Minimum Bid Increment

To prevent dust bids there is a minimum bid increment of 1% of the current price.

## Time Limit & Extensions

Auctions have a time limit during which bidders place their bids. When the time limit runs out the sNFT will be sold to the highest bidder.

If a bid is placed in the final 15 minutes of an auction the time limit will be extended by 15 minutes to prevent sniping and other forms of price manipulation.
