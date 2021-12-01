---
title: Shopping Carts listing
weight: 1
---

# ORDERS > SHOPPING CARTS

This specific page is for storing and editing all the Prestashop shopping carts, that were generated during the checkout process. All the listed UI elements are the following below.

## Top of the table UI

- **Shopping Carts** - the unique ID name identifier.
- **Numeric value** - total sum of shopping carts identified.
- **Export icon** - once clicked, a file is generated with the all the shopping carts data in a CSV format.
- **Refresh** - once clicked, the whole page reloads to display the latest data.

## Table Filtering UI

- **ID** - input field, that could be typed as numeric value in order to retrieve the required Shopping Cart ID. By default the input is blank empty.
- **Order ID** - input field, chat could be typed as numeric value in order to retrieve the required Order ID. By default the input is blank empty.
- **Customer** - input field, that could be typed as alphabetic value in order to retrieve the required Customer name or last name. By default the input is blank empty.
- **Total** - numeric value that shows the total amount in the Shopping Cart. It is displayed as a total sum of all the items in the appropriate currency, that is being purchased. 
- **Carrier** - input field, that could be typed as alphabetic value in order to retrieve the required Carrier name. By default the input is blank empty.
- **Date** - input form, that could be adjusted by the time values. Setting the date "From" to "To", will retrieve the appropriate date range information of the Shopping Carts. By default, the date range is blank empty.
- **Online** - value indicator between Yes and No. Once the Guest visitor is visiting the Prestashop Front-Office, and adding items to the Shopping Cart, the value then switches to Yes. By default, the indicator is in blank empty state.
- **Shop** - filtering is not available, but the whole column is listed with the Shop names for each Shopping Cart, if there are several multistores configured.
- **Search CTA button** - once clicked, the filtering criteria is executed.

## The body of the Table UI

- **Checkbox** - once the checkbox is checked, the function can be related to Bulk Actions section in the bottom of the Shopping Cart table. The Shopping Cart item can be managed by those Bulk Actions. By default, there are nonde of the Shopping Carts selected.
- **ID number of Shopping Cart** - specific numeric value, that is registered by Prestashop, every time the cart is created. By default, the ID numbering is set by the ascending arrangement.
- **Abandoned cart** - if the Cart is not validated through the last checkout step, and the Order is not created, the Cart is statused as Abandoned, and the status becomes _Abandoned Cart_ without any Order ID number.
- **Customer name and last name** - the unique identifier that shows the Cart creator. If the Cart is created by Guest User, there won't be first and last name in the Shopping Cart, because the Prestashop has not yet transformed the Cart ID into Client ID. If there is registered client, that created the Cart, it will be identified by first and last name.
- **Total sum of Cart** - numeric value that shows the total amount in the Shopping Cart. It is displayed as a total sum of all the items in the appropriate currency, that is being purchased.
- **Carrier** - if the user has reached the Carrier step in the Checkout, then Prestashop will register and display the chosen Carrier in the Shopping Cart item.
- **Date** - the exact time stamp, when the Cart was created.
- **Online** - the text value, that can be displayed as Yes or No, according to conditioins.
- **Shop** - if multistores are enabled, Prestashop will show the appropriate shop, where Cart was created.
- **CTA button View and Delete** - if the Cart is abandoned or the Cart has not been converted to the Orded, the CTA button will be displayed only View. If the Cart has transformed to Order, there will be also a dropdown in View CTA, with the selection of Delete - in order to delete the Cart from Prestashop database.

## The bottom of the Table UI

- **Bulk actions** - a selective UI, where certain global actions can be done, after checking one or multiple Shopping Cart element rows.