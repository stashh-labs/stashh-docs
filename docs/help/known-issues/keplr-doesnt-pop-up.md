---
title: Keplr Doesn't Pop Up
---

# Keplr Doesn't Pop Up

When Stashh needs to do something involving your wallet it has to ask Keplr to ask you to approve the action Stashh wants to take. We have seen instances where Keplr silently ignores these requests. This usually manifests as...

- No prompt to unlock Keplr is shown when loading Stashh
- No Keplr unlock prompt is shown when clicking the **Wallet** button
- No Keplr Permit prompt appears when the **Authenticate** button is clicked, or creating a Collection Permit
- No Keplr Transaction prompt is shown when buying, selling, minting, burning, or Transferring a sNFT

In addition, no error message is shown in the browser console.

We don't know the exact cause of the issue, but it appears to be something to do with the connection between Keplr and the nodes it uses to interface with Secret Network.

## Captive WiFi

The team have experienced this issue personally on public WiFi connections where they were asked to sign in via a portal before using the WiFi. Many public WiFi providers block or intercept secure connections which can cause connectivity issues for things other than basic web traffic.

All you can do in this situation is switch to a different connection.

## VPNs, Antivirus, and Browser Extensions

VPNs, Antivirus software, and some Browser Extensions can also interfere with the connection between Keplr and its API nodes. If you're certain that your internet connection is not causing the issue try each of the following steps and reload Stashh to narrow down the cause of the issue...

- Disable any software or hardware VPN connections and try again
- Disable antivirus features that intercept traffic
- Disable browser extensions that intercept or modify traffic

## Reinstall Keplr

!!! danger
    Before doing this please make sure you have a copy of your recovery phrase. You will need it to re-add your wallet. If you loose your recovery phrase you loose your wallet and all of its content permanently!

If none of the above helps reinstalling Keplr can sometimes solve the issue. This should be considered as a last resort and you will need to recreate any Permits or Viewing Keys you have created.

1. Right click the Keplr icon
2. Click **Remove from Chrome/Brave...**
3. Click the **Remove** button
4. Close and re-open your browser
5. Reinstall [Keplr](https://chrome.google.com/webstore/detail/keplr/dmkamcknogkgcdfhhbddcghachkejeap/related) from the Chrome store

