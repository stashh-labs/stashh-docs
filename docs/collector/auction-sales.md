---
title: Auction Sales
---

# Auction Sale

An auction is a mechanism to find the optimal price for your NFT. When you list an NFT for sale as an Auction on Stashh it will be shown in the marketplace for a set period of time during which potential buyers place bids. When the timer expires the NFT is sold to the highest bidder. You can also set an optional Buy Now price that will cause the auction to end early when reached.

Auction sales work within our standard Fees and Royalty schedule.

## Create an Auction

To sell an NFT using Auction

1. Select **Auction** from the Sale Type dropdown menu
2. Select the Currency you want to sell for from the **Currency** dropdown menu.
3. Enter the amount you want bidding to start at into the **Minimum Bid** field.
4. If you want to set a Buy Now price enter it into the **Buy Now** field
4. Click the checkbox confirming that you understand that selling an NFT will make your wallet address visible
5. Click the **List for Sale** button.
6. Click the **Approve** button to approve the transaction.

!!! note 
    When you list an NFT for sale it will be moved from your wallet into the auction contract escrow.

## Cancel an Auction

!!! warning
    Once a bid has been placed it is impossible to cancel an auction

To cancel an Auction

1. Navigate to the NFT you want to take off sale
2. Wait for Stashh to confirm your ownership.
3. Click the **Cancel Sale** button
4. Click the **Approve** button to approve the transaction.
5. Wait a few moments for the auction to be cancelled then click the **Withdraw** button


## Closing an Unsold Auction

If an auction ends with no bids you need to close it to get your NFT back out of the auction contract escrow.

1. Go to the auction
2. Wait for Stashh to confirm you are the owner
3. Click the **Close Auction** button
4. Click **Approve**

The auction will be closed and your NFT will be returned to your wallet.

## Winning an Auction

If you are the highest bidder when an Auction closes the transaction will automatically be finalised by the Auction contract.

If you already have a Permit or a Viewing Key for the Collection the NFT is in you can go to your Dashboard and view it immediately. If not, please follow the instructions for Viewing Your NFTs.

## Buy Now Price

The Buy Now price is the price at which the auction will instantly end if met or exceeded. Sellers do not have to set a Buy Now Price, but if they do it effectively set a ceiling price for an Auction. An auction will end the moment someone places a bid that is equal to or greater than the Buy Now price. 

## Bidding & Minimum Bid Increment

To bid on an NFT...

1. Enter the amount of your bid into the **Amount** field
2. Click the **Bid Now** button.
3. Click the **Approve** button to approve the transaction.

!!! warning 
    When you bid on an NFT the amount of your bid will be moved from your wallet into the auction contract escrow. This amount will be automatically returned if you are outbid.

To prevent dust bids there is a minimum bid increment of 10% of the current price.


## Time Limit & Extensions

Auctions have a time limit during which bidders place their bids. When the time limit runs out the NFT will be sold to the highest bidder.

If a bid is placed in the final 5 minutes of an auction the time limit will be extended by 15 minutes to prevent sniping and other forms of price manipulation.