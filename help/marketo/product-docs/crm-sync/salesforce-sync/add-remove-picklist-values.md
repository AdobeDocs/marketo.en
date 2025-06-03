---
unique-page-id: 4719312
description: Add/Remove Picklist Values - Marketo Docs - Product Documentation
title: Add/Remove Picklist Values
exl-id: f1230c43-10cb-47ff-89d7-9f835b034db0
feature: Salesforce Integration
---
# Add/Remove Picklist Values {#add-remove-picklist-values}

Here are a few things to know about adding and removing picklist values in Salesforce.

## Adding Picklist Values {#adding-picklist-values}

1. If an additional value is added in Salesforce to a picklist field type, you will receive a [notification](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md){target="_blank"} identifying which forms this will affect.

   ![](assets/image2015-1-21-14-3a4-3a7.png)

1. Go to the form editor and [add the additional value](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md){target="_blank"} to your list of suggestions.

## Remove Picklist Values {#remove-picklist-values}

When a picklist value is removed from a field in Salesforce, you will have to manually remove this value from all the forms hosting this field.

>[!NOTE]
>
>If a lead field and a contact field in Salesforce have different values, the values in common will be available for use in Marketo Engage.

If a lead field and a contact field in Salesforce have different values:

1. Adding an additional value in SFDC to a picklist will get a notification.
1. The notification will tell you where it's used. You can now add this new value as an option on the form if you want.

If a picklist of an SFDC lead has different values than a picklist for an SFDC contact, the common values will be used as default value options in the form.

If you remove a value from a picklist, you will have to manually remove it as an option from your forms.
