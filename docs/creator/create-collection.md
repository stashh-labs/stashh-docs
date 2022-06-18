---
title: Create a Collection
---

# Create a Collection

!!! warning

    Currently you need to be a whitelisted creator in order to create or import collections on Stashh. For more details about how this works please read the [Early Access Creator Program](early-access-creator-program.md) page

1. Make sure you are authenticated with your whitelisted wallet then click the **Create** button on the navigation bar.
2. Click the **Create New Collection** button.
3. Customise your collection then click the **Create Collection** button.
4. Your wallet will ask to Instantiate a Contract for the Collection. Click **Approve**

    === "Keplr"

        ![Keplr requesting to  Instantiate a Contract](../images/keplr-instantiate-contract.png#pop)

5. Click the **Create Permit for This Collection** button.
6. Your wallet will ask to create a Permit. Click **Approve**

    === "Keplr"

    ![Keplr requesting a Permit](../images/keplr-query-permit.png#pop)

## Collection Properties

### Logo

The logo is shown everywhere on your Collection, on the Collection Card and is used on social media cards when someone links to your collection on a platform that supports them.

For best results we recommend using a 300 x 300 pixel image in PNG or JPG format with a maximum size of 1mb.

!!! tip
    The logo be cropped to a circle so try to avoid text that goes across the top or bottom of the image as it will be obscured.

### Banner

The banner sits at the top of your Collection, and is shown on your Collection Card throughout the marketplace.

For best results we recommend using a 1195 x 150 pixel image in PNG or JPG format with a maximum size of 3mb.

!!! tip
    The banner is center cropped on Collection cards, so avoid putting text or important visual elements at the far left or right.

### Name

This is the name your collection will be known by on Stashh. 

!!! note
    The name of your collection must be unique

### Description

This is the sales pitch for your collection. It is shown at the top of your collection page, and the first ~110 characters are shown on the Collection card.

### Categories

Categories help people to discover new content. Choose the category that best fits your collection.

### Symbol

This is the on-chain symbol for the tokens that will be created in your collection. It is not used for anything on Stashh.

It can be up to 5 characters long, and can only use A-Z and 0-9. If you don't set one then one will be generated for you using the Name of your collection.

This value does not have to be globally unique.

### Configuration

#### Enable Royalties

This allows you to set up the default [royalties](../concepts/royalty.md) for the collection that will be applied to any new sNFTs created within it. 

The addresses and percentages you set here will be automatically populated when you enable royalties for a sNFT in this collection.

!!! warning
    You must still enable Royalties for each sNFT.

#### Hide Collection

When enabled this setting hides the collection and its contents from everyone except the creator. This setting is enabled by default, and we recommend keeping it enabled while you set up your collection.

!!! tip 
    To unhide your collection follow the instructions to [Reveal your Collection](reveal-collection.md)

#### Hide sNFT Ownership

When enabled this setting will cause the wallet address of the owner of all tokens within the collection to be private.

#### Enable Burn Feature

When enabled this setting will allow tokens in your collection to be [burnt](../concepts/burn.md) by their owner.

!!! note
    Badges that are marked as non-transferable will always be [burnable](../concepts/burn.md) regardless of how this is set.

#### Minter can change sNFT metadata

 When enabled this setting will allow the metadata of tokens in the collection to be modified by the creator after the tokens have been minted. This is useful for dApps that need to update metadata, however it can be abused so we recommend that you leave this setting disabled unless you have a specific use case for it.

#### Terra Clone

This setting should be enabled only if you are creating a collection to be bridged across from an existing Luna collection.