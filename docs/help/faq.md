---
title: Frequently Asked Questions
hide:
  - toc
---

# Frequently Asked Questions

## What is Stashh

Stashh is an NFT marketplace built on Secret Network, the first Layer 1 blockchain with programmable privacy by default for smart contracts

## Why is Stashh different to other NFT marketplaces?

Stashh is the first marketplace for NFTs that are private by default - the missing piece to making NFTs truly useful, secure, and sustainable. This unique privacy functionality means you can mint, buy, and trade NFTs on Stashh that aren't possible on any other blockchain. It also means Stashh can offer unique features to users and creators, such as transactional privacy, auctions that are impossible to front-run, full on-chain randomisation, private ownership, and much, much more.

## Why are wallet addresses shown on sNFTs?

On Secret Network any transactions you do with a contract (including instantiation) are available publicly on chain, so anyone can see that an address signed a transaction to instantiate a new listing. It doesn't make sense for Stashh to hide this address as it would give a false sense of privacy.

We make it clear that selling a sNFT will expose the address of the seller before a listing can be created.

## What are Public, Private, and Protected Properties?

sNFTs (as defined by the SNIP-721 standard on Secret Network) are distinct from other NFTs in that each property of a Secret NFT has a privacy level as well as a name and a value. This dramatically expands what's possible with NFTs, with the potential to revolutionize digital art, music, video sharing, gaming, finance, and many more industries. The privacy level for each sNFT property can be set independently, and can be Public, Protected, or Private. 

**Public** properties allow anyone to see the name and the value of the property. There is no privacy there at all. 
**Protected** properties allow anyone to see the name of the property, but only the current owner can see the value. 
**Private** properties allow only the current owner to see the name and the value.

## What is a Collection?

Collections are a way for creators to group related sNFTs together into a single place that can be easily browsed and searched. 

From the blockchains perspective a Collection is a smart contract so you can interact with it programmatically via the CLI which unlocks all kinds of advanced use cases where you can use Stashh as a marketplace while providing bespoke utility via an external application.

## How do I see the NFTs I own?

You can see all your sNFTs in  [My Stashh](https://stashh.io/dashboard/my-stashh). Please read the [Viewing your sNFTs](../collector/view-nfts.md) page for more details.

## Can I make offers on sNFTs?

We're working on the Offers feature now. You can see our progress in the [Roadmap](https://stashh.io/roadmap)

## Does Stashh support auctions?

Yes! We deployed [Auctions](../features/sale-types/auction-sales.md) in April 2022.

## What currencies does Stashh support?

Currently Stashh supports sales denominated in a variety of SNIP20 tokens including sSCRT, sUSDT, sETH, sSTARS, and sHUAHUA as well as SEFI and SIENNA.

Using the Buy With SCRT feature you can also pay in SCRT and the transaction will be conducted using a privacy preserving SNIP20 token.

## How much does it cost to sell a sNFT on Stashh?

We charge a fee of 2.75% of the sale price or 0.05 sSCRT (whichever is higher) from the seller's proceeds when a sNFT is sold.

We do not charge any other fees, however Secret Network will charge a small gas fee for executing transactions. For more information on approximate network fees please see the [Creator Fees](../creator/creator-fees.md) and [Collector Fees](../collector/collector-fees.md) pages.

## How much does it cost to buy a NFT on Stashh?

We do not charge buyers any fees to use Stashh; however, Secret Network will charge a small gas fee for executing transactions. For more information on approximate network fees please see the [Collector Fees](../collector/collector-fees.md) page.

## Where are assets stored?

The private content of your NFT is encrypted on our servers then uploaded to IPFS, and pinned. This content is then served to owners of your NFT from IPFS via a gateway.

The public preview image of your NFT is stored using Azure Storage.

Banners, logos, and profile pictures are also stored using Azure Storage.

## What does it mean to 'follow' a sNFT?

Following a sNFT makes it easier to keep an eye on NFTs you want to watch or potentially buy. When you click the Follow button that NFT will be added to the Following section in your Dashboard. A counter is shown on each NFT showing the number of users following it.

## What does it mean for an sNFT, or Collection to be Trending?

The Trending lists on the Stashh homepage shows sNFTs and Collections that have the highest number of Followers and Views during a rolling time-frame; usually 24 hours.

## Why does Stashh use sSCRT instead of SCRT?

It is possible to buy an NFT with any currency; however, this would be recorded publicly on-chain forever for everyone to see. Transactions involving SNIP20 tokens (like sSCRT, sUSDT, sETH, etc) do not reveal who bought a specific NFT and therefore help to protect your identity and increase your security. This also enables a far wider variety of use cases for sNFTs. You can always choose to reveal your ownership of a sNFT, but they begin private by default. 

The use of SNIP20 tokens on Stashh unlocks a bunch of features that would be impossible on other blockchains. For example, using SNIP20 tokens in an Auction keeps the balance of the bidder hidden so their competitors can't simply inspect the balance of the bidder and outbid them.

You can buy a sNFT on Stashh using the Buy With SCRT feature, however the actual transaction will be conducted using a SNIP20 token to preserve your privacy. In this case Stashh automatically swaps the right amount of SCRT for the corresponding SNIP20 token then uses that to buy your sNFT.

## Why can't I convert all my SCRT to sSCRT?

You can, but it would be a bad idea! 

sNFTs on Stashh can be paid for with a variety of different tokens but the transaction has to go across Secret Network which charges fees in SCRT. Without a small amount of SCRT in your wallet it is impossible to send transactions over the network, including swapping back from sSCRT to SCRT!

## Can the previous owner of an sNFT access its private metadata after selling it?

No. Only the current owner of an NFT can access its private metadata though it is possible that the previous owner made copies of the decrypted private metadata before selling it.

## Why does it take so long to "decrypt" my sNFT?

When you view the private content of your NFT via Stashh we download the encrypted asset to a temporary location on your computer, then use the decryption key in your NFT to decrypt it and show you the contents. Because this process is decentralised it can take a little longer. Usually the private asset you have access to as the owner is higher resolution and therefore larger than the public preview which increases the amount of time it takes to download and process. All great things require patience!

## Can Stashh do random minting?

Yes. You can do this using a Gumball Machine.

## Do I have to upload a separate thumbnail for my sNFT?

You don't have to - but we recommend that you do. Stashh will automatically generate a black and white thumbnail for you if you don't upload one.

## Can I set a whitelist for my sNFTs?

If you're using a Gumball Machine you can set up a whitelist. We're working to allow whitelisting for individual sNFT sales and Collections.