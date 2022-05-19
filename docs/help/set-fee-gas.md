---
title: Set Transaction Fee and Gas
---

# Set Transaction Fee and Gas

On Secret Network the Transaction Fee and Gas are separate concepts.

## Transaction Fee

The Transaction Fee is the the fee you pay to a validator to process your transaction. Paying a higher fee will cause the validator to prioritise your transaction over those paying a lower fee, *but it will not increase the amount of gas available for your transaction*. 

In the majority of cases you should select **Average**. Some validators will not process your transaction if you select **Low**

![](../images/keplr-fee.png)

## Gas

The Gas value sets the amount of resources that are available to execute your transaction. If your transaction fails and the **Gas Used** is higher than the **Gas Wanted** you should manually increase the amount of Gas. 

To do this, click **Set Gas** below the fees and enter an amount ~50,000 above the **Gas Used** value.

Increasing the Gas will increase the cost of the overall cost of the transaction, so it is important not to set it to an excessive amount. Always check the total you will pay for the transaction before clicking Approve. 

![](../images/keplr-manual-gas.png)