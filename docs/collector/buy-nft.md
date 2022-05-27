---
title: Buy an NFT
---

# Buy an NFT

Buying an NFT on Stashh is similar to buying an NFT on any other marketplace. The key difference is that Stashh maintains your right to privacy. Other marketplaces can look inside your wallet and see everything you own and everything you have ever done, but we think that is a fundamental invasion of your right to privacy. It's like allowing anyone to come into your home and dig around your stuff.

Stashh is different. We can't go digging around in your wallet because _nobody_ on Secret Network can without your permission. The trade-off for this privacy is that there are are couple of extra clicks involved when you buy an NFT. Broadly the two things you will need to do are...

1. Swapping for SNIP20 tokens
2. Creating Permits or Viewing Keys

## SNIP20 Tokens

Stashh uses privacy preserving SNIP20 tokens for all transactions. You can tell that you are dealing with a SNIP20 because they all start with a lower-case s, like sSCRT or sETH. We use SNIP20s because they don't allow anyone else (including Stashh) to view them unless you grant them permission with a Viewing Key. 

If Stashh needs to use your SNIP20 balance it will check to see if you have already have a Viewing Key set up. If you don't Stashh will display a button or a link that you can click to create the Viewing Key and store it locally.

Using SNIP20 tokens allows all your balance and transaction data to be encrypted on-chain. Nobody can access this information without your explicit permission. This means that...

- Scammers can't see your NFT collection or your balance
- You can't be front-run in auctions
- Your transaction history is private

## One-Click Buy

If Stashh detects that you have enough SCRT but not enough SNIP20 tokens to buy an NFT it will show the One-Click Buy button. When you click this Stashh will convert the right amount of SCRT to the correct SNIP20 token, use it to buy the NFT, then create a Permit for the collection in a single transaction.

## Manually Swapping to SNIP20s

If you prefer not to use One-Click Buy you can manually swap or bridge for SNIP20 tokens.

### sSCRT

Swapping SCRT for sSCRT can be done directly on Stashh...

1. Click the Account Menu icon :fontawesome-solid-user:
2. Click the **Swap** button
3. Enter the amount of SCRT you want to swap for sSCRT into the **Amount** field
4. Click the **Swap** button.
5. Click **Approve** on the transaction that pops up.

!!! tip
    You can also swap sSCRT to SCRT using the same tool. Just click the switch icon ICON NEEDED HERE>>>>>>>>>>>>>>>

### Other SNIP20 Tokens

You can swap for other SNIP20 tokens like sETH, sHUAHUA, or sUSDT using tools like Sienna Swap, or you can bridge ETH directly to sETH using the Secret Network Bridge.