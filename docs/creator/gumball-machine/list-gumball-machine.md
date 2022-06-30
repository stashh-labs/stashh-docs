---
title: List a Gumball Machine
---

# List a Gumball Machine

!!! warning "Prerequisite"

    You must [Create](create-gumball-machine.md) and [Load](load-gumball-machine.md) a Gumball Machine before you can List it.

1. Navigate to the collection that contains your Gumball Machine
2. Click the Edit icon :duotone-pen-to-square:
3. Navigate to the **List Gumball Machine** section.

    ![The Gumball Listing page](/images/gumball-list.png#pop)

4. Fill out the details in the form then click the **List for Sale** button.
5. Your wallet will ask to Execute a Contract. Click **Approve**

    === "Keplr"

    ![Keplr requesting to Instantiate a Contract](/images/keplr-execute-contract-gumball-list.png#pop)

## Properties

### Whitelisting

A whitelist allows you to restrict sales to a specific set of addresses for a specific period of time, or until a specific allocation of sNFTs have been sold.

To enable the Whitelist turn on the Whitelisting toggle. The Whitelisting control will appear below it.

#### Total Amount Reserved For Whitelist

This field sets the maximum number of sNFTs that can be sold during the whitelisted purchase period. It must be less than or equal to the number of sNFTs in the Gumball Machine.

If a Total Reserved Amount is set with no End Date then the main sale will begin as soon as the allocation of reserved sNFTs is sold.

#### End Date

This field sets the date and time that Whitelist Sales will end. If there are any remaining sNFTs in the whitelist allocation they will be added to the pool available for the Main Sale.

#### Manage Whitelist

##### Manual Input

1. Select **Input**
2. Enter the address into the **Address** field
3. Enter the number of mints that address is allowed gets into the **Quantity** field. 

To add a new address to the list click the **Add Whitelist Address** icon :duotone-circle-plus:. 

To remove an address click the **Remove Address** icon :duotone-circle-minus:

##### Upload List

1. Select **Upload File**.
2. Download the template by clicking the file icon :duotone-file-lines:
3. Fill in the template file and save it
4. Drag the completed file onto the Upload target

!!! warning

    The template file must have "address" and "quantity" on row 1.

To add a new address to the list add a new row with the whitelisted address and the maximum number of mints that wallet is allowed.

To remove an address from the list delete the row.

### Pre-Sale

A pre-sale allows you to sell either a specific number of sNFTs at a different price, or to provide sNFTs at a different price for a specific amount of time.

To enable the Pre-Sales turn on the Pre-Sale toggle. The Pre-Sale control will appear below it.

#### Price

This is the price that will be offered to Collectors during the pre-sale.

#### Total Amount Reserved For Pre-sale

This field sets the maximum number of sNFTs that can be sold during the pre-sale period.

If a Total Reserved Amount is set with no End Date then the main full-price sale will begin as soon as the allocation of reserved sNFTs is sold.

#### End Date

This field sets the date and time that Pre-Sale sales will end. If there are any remaining sNFTs in the pre-sale allocation they will be added to the pool available for the full-price Main Sale.