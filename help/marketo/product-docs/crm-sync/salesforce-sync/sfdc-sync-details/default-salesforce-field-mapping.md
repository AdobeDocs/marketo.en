---
unique-page-id: 4719314
description: Default Salesforce Field Mapping - Marketo Docs - Product Documentation
title: Default Salesforce Field Mapping
exl-id: d6639733-f85d-4f4c-ac41-5d2a68a9c6b2
---
# Default [!DNL Salesforce] Field Mapping {#default-salesforce-field-mapping}

When you initially sync your Marketo account with [!DNL Salesforce], Marketo automatically makes these associations between your built-in [!DNL Salesforce] and Marketo fields. Marketo will also sync your custom fields on your Leads, Accounts, Opportunities, and Contacts.

## Lead Fields {#lead-fields}

| SFDC field |Marketo field |
|---|---|
| [!UICONTROL Annual Revenue] |[!UICONTROL Annual Revenue] |
| [!UICONTROL City] |[!UICONTROL City] |
| [!UICONTROL Company] |[!UICONTROL Company Name] |
| [!UICONTROL Converted Date] |[!UICONTROL SFDC Converted Date] |
| [!UICONTROL Country] |[!UICONTROL Country] |
| [!UICONTROL Created Date] |[!UICONTROL SFDC Created Date] |
| [!UICONTROL Description] |[!UICONTROL Person Notes] |
| [!UICONTROL Email] |[!UICONTROL Email Address] |
| [!UICONTROL Fax] |[!UICONTROL Fax Number] |
| [!UICONTROL First Name] |[!UICONTROL First Name] |
| [!UICONTROL Email Opt Out] |[!UICONTROL Unsubscribed] |
| [!UICONTROL Industry] |[!UICONTROL Industry] |
| [!UICONTROL Converted] |[!UICONTROL SFDC Is Converted] |
| [!UICONTROL Deleted] |[!UICONTROL SFDC Is Deleted] |
| [!UICONTROL Last Name] |[!UICONTROL Last Name] |
| [!UICONTROL Lead Source] |[!UICONTROL Source] |
| [!UICONTROL Lead Score] |[!UICONTROL Score] |
| [!UICONTROL Mobile Phone] |[!UICONTROL Mobile Phone Number] |
| [!UICONTROL Employees] |[!UICONTROL Num Employees] |
| [!UICONTROL Phone] |[!UICONTROL Phone Number] |
| [!UICONTROL Zip/Postal Code] |[!UICONTROL Postal Code] |
| [!UICONTROL Rating] |[!UICONTROL Rating] |
| [!UICONTROL Salutation] |[!UICONTROL Salutation] |
| [!UICONTROL State/Province] |[!UICONTROL State] |
| [!UICONTROL Status] |[!UICONTROL Status] |
| [!UICONTROL Street] |[!UICONTROL Address] |
| [!UICONTROL Title] |[!UICONTROL Job Title] |
| [!UICONTROL Website] |[!UICONTROL Website] |

## Contact Fields {#contact-fields}

| SFDC field |Marketo field |
|---|---|
| [!UICONTROL Birthdate] |[!UICONTROL Date of Birth] |
| [!UICONTROL Created Date] |[!UICONTROL SFDC Created Date] |
| [!UICONTROL Contact Description] |[!UICONTROL Person Notes] |
| [!UICONTROL Email] |[!UICONTROL Email Address] |
| [!UICONTROL Business Fax] |[!UICONTROL Fax Number] |
| [!UICONTROL First Name] |[!UICONTROL First Name] |
| [!UICONTROL Email Opt Out] |[!UICONTROL Unsubscribed] |
| [!UICONTROL Deleted] |[!UICONTROL SFDC Is Deleted] |
| [!UICONTROL Last Name] |[!UICONTROL Last Name] |
| [!UICONTROL Lead Source] |[!UICONTROL Source] |
| [!UICONTROL Lead Score] |[!UICONTROL Score] |
| [!UICONTROL MailingCity] |[!UICONTROL City] |
| [!UICONTROL MailingCountry] |[!UICONTROL Country] |
| [!UICONTROL MailingPostalCode] |[!UICONTROL Postal Code] |
| [!UICONTROL MailingState] |[!UICONTROL State] |
| [!UICONTROL MailingStreet] |[!UICONTROL Address] |
| [!UICONTROL Mobile Phone] |[!UICONTROL Mobile Phone Number] |
| [!UICONTROL Business Phone] |[!UICONTROL Phone Number] |
| [!UICONTROL Salutation] |[!UICONTROL Salutation] |
| [!UICONTROL Title] |[!UICONTROL Job Title] |

## Account Fields {#account-fields}

| [!UICONTROL SFDC field] |[!UICONTROL Marketo field] |
|---|---|
| [!UICONTROL Annual Revenue] |[!UICONTROL Annual Revenue] |
| [!UICONTROL Billing City] |[!UICONTROL Billing City] |
| [!UICONTROL Billing Country] |[!UICONTROL Billing Country] |
| [!UICONTROL Billing Zip/Postal Code] |[!UICONTROL Billing Postal Code] |
| [!UICONTROL Billing State/Province] |[!UICONTROL Billing State] |
| [!UICONTROL Billing Street] |[!UICONTROL Billing Address] |
| [!UICONTROL Account Description] |[!UICONTROL Company Notes] |
| [!UICONTROL Industry] |[!UICONTROL Industry] |
| [!UICONTROL Deleted] |[!UICONTROL SFDC Is Deleted] |
| [!UICONTROL Account Name] |[!UICONTROL Company Name] |
| [!UICONTROL Employees] |[!UICONTROL Num Employees] |
| [!UICONTROL Account Phone] |[!UICONTROL Main Phone] |
| [!UICONTROL SIC Code] |[!UICONTROL SIC Code] |
| [!UICONTROL Account Site] |[!UICONTROL Site] |
| [!UICONTROL Account Type] |[!UICONTROL SFDC Type] |
| [!UICONTROL Website] |[!UICONTROL Website] |

## [!DNL Salesforce]-Related System Fields in Marketo (Read-only) {#salesforce-related-system-fields-in-marketo-read-only}

These fields are created in Marketo but can't be adjusted by customers.

| Field |Description |
|---|---|
| SFDC Id |The 18-character [!DNL Salesforce] Id |
| SFDC Type |Lead or Contact. If empty, the lead exists only as a person in Marketo |
| SFDC Created Date |Date created in SFDC (can be different from Created in Marketo) |
| SFDC is Deleted |Person used to be in SFDC but was deleted and now lives only in Marketo |
