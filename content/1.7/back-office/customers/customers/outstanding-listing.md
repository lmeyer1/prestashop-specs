---
title: Outstanding
weight: 1
---

# SELL > CUSTOMERS > Outstanding

![Outstanding page](static/img/customers-outstanding.png)

This UI is shown after Enabling the _Enable B2B mode_ toggle switch in _CONFIGURE > Customer Settings_ and it allows to track the B2B customer behavior. 

## Top UI elements

- **Outstanding** - page title.
- **Help** - a side-bar with the helpful information, how to navigate in this page.

## Main UI elements

### Top table elements

- **Outstanding** - table title with the total sum of outstanding entries.

### Filtering

- **Search ID** - input for searching certain entry with ID.
- **Date widget** - allows to filter the entries for certaind time range.
- **Customer** - ability to search and filter the customers.
- **Company** - ability to search and filter the company.
- **Risk** - dropdown element, allowing to arrange the risk priority values, and show only risk-prioritized Outstanding entries.
- **Outstanding allowance** - input for arranging appropriate entries for customers with the Outstanding amount.
- **Current outstanding, Invoice, Actions** - has no filtering function, only titles are displayed.
- **Search CTA button** - once there are no entries from none of the filtering fields, the Search CTA button is disabled, once there are at least one filtering value managed, the button becomes enabled.
- Reset (X) - after submission of the Filtering, there are the results shown in the table, together with the Reset and X icon. It resets the Filtering form.

### Table row elements

- **ID** - numeric ID value.
- **Date** - YYYY-MM-DD HH-MinMin-SecSec format.
- **Company** - customer with the company value.
- **Risk label** - the text with colorized outlined label, defining the Risk level of the entry.
- **Outstanding amount** - the value with the numeric amount and currency prefix.
- **Current outstanding amount** - the value with the numeric amount and currency prefix.
- **Invoice sheet icon** - clicking initiates the download of the PDF invoice file.
- **View lasso icon** - clicking initiates redirection to the Order in Back-Office, that customer has made.

### Pagination

- **Page number input** - function that displays the desired page number of the listing, after inputting the number and pressing Enter.
- **Viewing indicator text** - text, indicating what pages the user is seeing.
- **Items per page** - dropdown with the numeric values, how many items can be shown in listing:
  - 10
  - 20
  - 50
  - 100