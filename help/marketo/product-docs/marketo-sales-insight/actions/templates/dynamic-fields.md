---
description: Dynamic Fields - Marketo Docs - Product Documentation
title: Dynamic Fields
exl-id: d9e52eae-d5bb-462f-8b7b-c28a560f6ea4
feature: Sales Insight Actions
---
# Dynamic Fields {#dynamic-fields}

We allow you to personalize your email templates with predefined attributes like `{{first_name}}` or `{{company}}`. These fields allow you to email multiple contacts and auto-complete these fields without having to type them out separately for each contact.

>[!TIP]
>
>The "first_name" and "company" field are the only fields that will look to both Sales Insight Actions and Salesforce. That means if a contact does not exist in the [web application](https://toutapp.com/login), we look in Salesforce to see if we can find a contact/lead record with a matching email address. We then use information from that record to populate the field.

## Insert a Dynamic Field into a Template {#insert-a-dynamic-field-into-a-template}

1. In **Templates & Campaigns**, find the template you want to edit and click **Edit Template**.

1. Click **Insert Dynamic Field**.

   >[!NOTE]
   >
   >When emailing contacts who exist in Sales Insight Actions, you can use the basic dynamic fields. These will pull directly from the contact.

If you're emailing contacts who exist in Salesforce, you can take advantage of the Salesforce dynamic fields. These all begin with "sfdc". As long as you have a connection to Salesforce, these fields will call directly to the lead/contact in Salesforce to populate information in the template.

## Insert Dynamic Fields in a Subject Line {#insert-dynamic-fields-in-a-subject-line}

Simply manually copy and paste them into the subject field of an email, taking care to ensure you have the proper formatting.

## Dynamic Field Default Values {#dynamic-field-default-values}

When adding dynamic fields to your email templates, you can add a default value that the dynamic field will resolve to if there's no other value available.  

To do this, add "|" after the dynamic field label, then add "default:" (both without quotes). Then, add the value you want the field to resolve to (wrapped in quotes) if no other value can be found.

**Example:**

`{{first name | default: "loyal customer"}}`

`{{sfdc_contact_account_name | default: "your company"}}`

## Dynamic Fields Glossary {#dynamic-fields-glossary}

When creating a template in Sales Insight Actions, we always recommend integrating dynamic fields, using the **Insert Dynamic Field** button.

This tool is used to `auto-personalize your email` and save you tons of time by `pulling information from the People page`.

| Dynamic Field | Example of what appears in your email |
|---|---|
| `{{company}}` | Adobe |
| `{{company_friendly}}` | Adobe |
| `{{first_name}}` | Keith |
| `{{team_unsubscribe}}` | If you no longer wish to receive emails from us, click here |
| `{{friendly_unsubscribe}}` | Tired of all the emails? Please let me know here |
| `{{my_name}}` | Keith Flynn |
| `{{my_signature}}` | Keith Flynn, Senior Technical Writer - Adobe |
| `{{personal_email}}` | keith@pickyouremail.com |
| `{{title}}` | Senior Technical Writer |
| `{{work_website}}` | https://www.adobe.com |

**Things to note**:

* If a contact's information is entered incorrectly or is missing from the People page, it will not pull over correctly into your template.
* The difference between `{{company}}` and `{{company_friendly}}` is that `{{company_friendly}}` will remove any formal title, such as Inc., LLC., etc., from the name of your contact's company.
* When using `{{company_friendly}}`, make sure you separate Inc. or Co. with a comma in the contact details. This is how Sales Insight Actions knows what to remove when pulling in the value.
* We allow you to personalize your email templates with predefined attributes like `{{my_name}}` or `{{my_title}}`. These fields allow you to quickly reference yourself in your email templates.
* The system automatically appends the user's signature to each email sent. If the user is using a template with the `{{my_signature}}` dynamic field, the system will populate the signature where the `{{my_signature}}` dynamic field has been placed. It's only added there as to avoid duplication. The system will handle `{{team_unsubscribe}}` the same way when the global append unsubscribe setting is enabled.

>[!TIP]
>
>If your dynamic fields aren't populating, check out [this article](/help/marketo/product-docs/marketo-sales-insight/actions/faq/why-arent-my-dynamic-fields-filling-out.md).
