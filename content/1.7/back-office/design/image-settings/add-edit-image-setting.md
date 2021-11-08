---
title: Add new Image setting
weight: 1
---

# Design > Image Settings > Add new Image setting

## Adding or editing Image setting UI

This configuration UI is about adding the new Image setting into the Image settings listing.

There are the following input text fields, that can be set:

- **Name for the image type**  - this is a required field, that describes the main name of the image type. The image type name should be used with underscores and hyphens only. Fore example, that could be _small_custom_, _large_, _custom-modified_small_. By default this input text field is empty.
- **Width** - this is a required field, that sets the numeric value of Image setting width in pixels. By default, this input text field is empty.
- **Height** - this is a required field, that sets the numeric value of Image setting height in pixels. By default, this input text field is empty.
- **Products** - this toggle switch button can be set for using images setting for Prestashop Products. By default, the button is disabled.
- **Categories** - this toggle switch button can be set for using images setting for Prestashop Categories. By default, the button is disabled.
- **Brands** - this toggle switch button can be set for using images setting for Prestashop Brands. By default, the button is disabled.
- **Suppliers** - this toggle switch button can be set for using images setting for Prestashop Suppliers. By default, the button is disabled.
- **Stores** - this toggle switch button can be set for using images setting for Prestashop Stores. By default, the button is disabled.

There is CTA **Save** for saving the Images setting that is configured, and CTA **Cancel** for discarding the Image setting creating or editing action, and navigating to the listing page.

## UI notifications after submitting

During default Image setting configuration, the notification is prompted as error: <br>
_By default, all images settings are already installed in your store. Do not delete them, you will need it!_

After the invalid set of the configuration in this page, for all the input text fields, the UI is prompting the error: <br>
_There are 3 errors.<br>
The name field is invalid.<br>
The width field is invalid.<br>
The height field is invalid._<br>

After leaving the required fields empty in this page, for all the input text fields, the UI is prompting the error: <br>
_There are 3 errors.<br>
The name field is required.<br>
The width field is required.<br>
The height field is required._<br>

After setting up the Image setting configuration, the UI prompts the warning notification: <br>
_After modification, do not forget to regenerate thumbnails_

When the Image setting is configured successfully, the UI will prompt the success notification:<br>
_Successful creation._

## Multistore behavior

The fields listed above don't have checkboxes and are available in all contexts (all shops, group, single store).
Images settings are set for all shops, no matter the context selected.