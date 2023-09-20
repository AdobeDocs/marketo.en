---
unique-page-id: 14352509
description: Dynamic Fields Glossary - Marketo Docs - Product Documentation
title: Dynamic Fields Glossary
exl-id: 28351ba9-53da-4408-9526-918200d9bd29
feature: Marketo Sales Connect
---
# Dynamic Fields Glossary {#dynamic-fields-glossary}

When creating a template in Sales Connect, we always recommend integrating dynamic fields, using the **MSE Dynamic Fields** button.

This tool is used to `auto-personalize your email` and save you tons of time by `pulling information from the People page`.

| Dynamic Field | Example of what appears in your email |
|---|---|
| `{{company}}` | Adobe |
| `{{company_friendly}}` | Adobe |
| `{{first_name}}` | Keith |
| `{{friendly_unsubscribe}}` | If you don't want to hear from me again, please let me know here |
| `{{my_name}}` | Keith Flynn |
| `{{personal_email}}` | keith@pickyouremail.com |
| `{{title}}` | Senior Technical Writer |
| `{{work_website}}` | https://www.adobe.com |

**Things to note**:

* If a contact's information is entered incorrectly or is missing from the People page, it will not pull over correctly into your template.
* The difference between `{{company}}` and `{{company_friendly}}` is that `{{company_friendly}}` will remove any formal title, such as Inc., LLC., etc., from the name of your contact's company.
* When using `{{company_friendly}}`, make sure you separate Inc. or Co. with a comma in the contact details. This is how Sales Connect knows what to remove when pulling in the value.

>[!TIP]
>
>You can create your own [custom dynamic field](/help/marketo/product-docs/marketo-sales-connect/templates/dynamic-fields/create-custom-dynamic-fields.md) for anything you'd like to have automatically pulled into your emails
