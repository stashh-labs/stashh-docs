---
title: Getting Started
hide:
  - navigation
  - toc
---

# Getting Started

## Install a Wallet

If you already have a compatible wallet installed and set up you can skip this step, otherwise install one of the wallets below...

- [Keplr](https://chrome.google.com/webstore/detail/keplr/dmkamcknogkgcdfhhbddcghachkejeap) (Chrome & Brave)

## Connect your Wallet & Authenticate

Before you can use Stashh you need to connect your wallet. You only need to do this once so you can skip this step if you have already done it.

1. Your wallet will pop up a message asking if you to connect to `secret-4`. Click **Approve**

    === "Keplr"

        ![Keplr requesting to connect](../images/keplr-add-secret-4.png#zoom)

2. Click the Account Menu icon :fontawesome-solid-user: then click the **Authenticate** button.

    ![Account menu showing the authenticate button](../images/account-menu-unauthenticated.png)

3. Check the message that pops up then click **Authenticate Wallet**
4. Your wallet will ask you to create a Permit. Click **Approve**

    === "Keplr"

    ![Keplr requesting a Permit](../images/keplr-query-permit.png#zoom)

You're now signed into Stashh and ready to go. Check out the [Marketplace](https://stashh.io/marketplace?sort=listing_date+desc&status=buy_now%2Cauction) to see what is for sale, or browse the [Collections](https://stashh.io/collections)

## Create a sSCRT Permit

The majority of transactions on Stashh are denominated in sSCRT which is a privacy preserving version of SCRT. Because it is privacy preserving you need to grant Stashh (or anyone else) permission to view your sSCRT balance with a Viewing Key.

1. Click the Account Menu icon :fontawesome-solid-user:

    ![Account menu showing the View sSCRT Balance button](../images/account-menu-show-balance.png)

2. Click **View sSCRT Balance**
3. If you have not already added sSCRT to your wallet it will pop up a message asking you to add a new token. Click **Submit**

    === "Keplr"

    ![Keplr requesting a Permit](../images/keplr-query-permit.png#zoom)

4. Your wallet will ask you if you would like to create a Viewing Key for sSCRT. Click **Approve**
5. After a few moments your sSCRT balance will appear in the menu where *View sSCRT Balance* was. It will probably be 0 for now.

    ![Account menu showing a sSCRT Balance](../images/account-menu-complete.png)