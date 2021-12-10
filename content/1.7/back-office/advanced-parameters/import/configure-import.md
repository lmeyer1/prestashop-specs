---
title: Import configuration page
weight: 1
---

# CONFIGURE > Advanced Parameters > Import

[Product Import](static/img/advanced-parameters-import.png)

This UI page and functionality is based on the product import actions of the Prestashop application. The listing is specified of all the visible sections in page.

## Top UI section

- **Multishop switcher** - it is an ability to switch the available multistores while beiing on the Import page, and to view the shop homepage by redirection.
- **Breadcrumbs, page title, Recommended modules and Help CTA's** - default Prestashop UI in the top position, helping administrators to improve the navigation.

## Import section

- **Blue information notification** - the segment with the useful links to the documentation about import and CSV format. The text is:<br>
_You can read information on import at: https://doc.prestashop.com/display/PS17/Import_ and _Read more about the CSV format at: https://en.wikipedia.org/wiki/Comma-separated_values_.
- **_What do you want to import?_ and Dropdown** - this functionality can be used for choosing the subjects that can be imported to Prestashop. The importing subjects are _Categories_, _Products_, _Combinations_, _Customers_, _Addressess_, _Brands_, _Suppliers_, _Alias_ and _Store contacts_. Categories and Products import is associated with the following yellow type warnings - _Note that the Category import does not support having two categories with the same name._ and _Note that you can have several products with the same reference._
- **_Select a file to import_ and the import input** - the file input field, where CSV files can be browsed and imported to the Prestashop. There is a short explanation and description about the uploading file types and the text encoding. The message says _Allowed formats: .csv, .xls, .xlsx, .xlst, .ods, .ots <br> Only UTF-8 and ISO 8859-1 encodings are allowed <br>You can also upload your file via FTP to the following directory: /Applications/MAMP/htdocs/prestashop_1780/admin1780/import/ ._