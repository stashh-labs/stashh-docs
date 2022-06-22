---
title: Secret Badges
---

# Secret Badges

Secret Badges (or sBadges) are privacy-preserving collectable digital assets issued as unique sNFTs on Secret Network. sBadges can represent digital mementos, exclusive content, recognition of achievements, digital entry passes, or anything else you can imagine.

Collectors get sBadges by claiming them using one of the Claim Mechanisms. As a creator it is up to you to decide what the eligibility criteria for your badges will be, and to set up the claim mechanism on your sBadge.

## Create a sBadge

1. Click the **Create** button on the top bar
2. Either [create a new collection](./collections/create-collection.md) or select an existing collection to create the sBadge in.
3. Click the **Badge** button.
4. Complete the form then click the **Create Template** 

!!! note
    If you are creating a sBadge in a new collection you will need to click **Generate Minter** then **Connect Minter With Collection** before the **Create Template** button is enabled.

## Claim Mechanisms

The Claim Mechanisms for a sBadge can be configured in the Claim Mechanism section 

### Single-Use Codes

Single Use Claim codes are short random unique codes that can be used once to mint a single sBadge.

1. Click the **Single Use Codes** tab on the Create Badge page.
2. Enter the number of claim codes you want.
3. Click the **Generate** button
4. A message will appear saying that your codes have been generated and saved
5. Click the **Download Saved Codes** button to download a spreadsheet containing your claim codes

### Multi-Use Codes

1. Click the **Multi-Use Codes** tab on the Create Badge page.
2. Enter the code you want to use into the **Unique Code** field
3. Enter the maximum number of times this code can be used into the **Maximum Uses** field, or check the **Unlimited** checkbox if there is no limit
4. To add another code click the **Add Unique Code** button

### Whitelist

You can _either_ upload a list of whitelisted addresses, or manually enter them.

#### Upload List

1. Click the **Whitelisting** tab on the Create Badge page.
2. Click the **Upload File** button
3. Click the button to download the template
4. Fill out the template with each address and the number of sBadges they will be allowed to mint.
5. Upload the completed file.

#### Input List

1. Click the **Whitelisting** tab on the Create Badge page.
2. Click the **Input** button
3. Enter the address into the **Address** field and the number of sBadges they will be allowed to mint into the **Quantity** Field.
4. To add another address click the **Add Whitelist Address** button.

### Updating Claim Mechanisms

The claim mechanisms can be changed and updated after a sBadge has been created.

1. Go to the asset page for the sBadge you want to update.
2. Wait for Stashh to confirm you are the owner
3. Click the **Edit Claim Process** button on the claim panel

You can now view and edit all the claim mechanisms set up for this sBadge. 

To add new entries under a mechanism click the Add icon :fontawesome-solid-plus:

!!! note
    Adding or removing whitelist addresses requires a transaction

To remove specific entries click the checkbox next to the entries you want to remove then click the Remove icon :fontawesome-solid-trash-can:

To remove all entries from a specific mechanism click the red Remove icon :fontawesome-solid-trash-can:

To disable the whitelist...

1. Click the **Whitelist** tab
2. Click the Disable whitelist icon :fontawesome-solid-align-justify:
3. **Approve** the transaction

### View Claimed sBadges

To view the current list of Claim Mechanisms and see which ones have been used...

1. Go to the asset page for the sBadge you want to update.
2. Wait for Stashh to confirm you are the owner
3. Click the **Edit Claim Process** button on the claim panel
4. Click through each of the tabs

Stashh will show all the configured entries for the mechanism and the claim state of each one.

## Transferability

Sometimes it doesn't make sense for an sBadge to be transferable to another wallet. You can disable the owners ability to sell or transfer a badge by disabling the **Transferable** toggle on the Create Badge page. Once this has been set is is not possible to change it later, or to set it differently for each owner of the same badge.

When a badge is marked as non-transferable (or "soul bound") it cannot be sold or transferred to another user. It is effectively bound to the wallet that mints it.

!!! warning
    Making a badge non-transferable automatically makes the badge burnable, even if you have disabled burning.