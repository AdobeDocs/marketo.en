---
unique-page-id: 4719314
description: Default Salesforce Field Mapping - Marketo Docs - Product Documentation
title: Default Salesforce Field Mapping
exl-id: d6639733-f85d-4f4c-ac41-5d2a68a9c6b2
feature: Salesforce Integration
---
# Default Salesforce Field Mapping {#default-salesforce-field-mapping}

When you initially sync your Marketo Engage account with Salesforce, Marketo automatically makes these associations between your built-in Salesforce and Marketo fields. Marketo will also sync your custom fields on your Leads, Accounts, Opportunities, and Contacts.

## Lead Fields {#lead-fields}

| SFDC field |Marketo field |
|---|---|
| Annual Revenue |Annual Revenue |
| City |City |
| Company |Company Name |
| Converted Date |SFDC Converted Date |
| Country |Country |
| Created Date |SFDC Created Date |
| Description |Person Notes |
| Email |Email Address |
| Fax |Fax Number |
| First Name |First Name |
| Email Opt Out |Unsubscribed |
| Industry |Industry |
| Converted |SFDC Is Converted |
| Deleted |SFDC Is Deleted |
| Last Name |Last Name |
| Lead Source |Source |
| Lead Score |Score |
| Mobile Phone |Mobile Phone Number |
| Employees |Num Employees |
| Phone |Phone Number |
| Zip/Postal Code |Postal Code |
| Rating |Rating |
| Salutation |Salutation |
| State/Province |State |
| Status |Status |
| Street |Address |
| Title |Job Title |
| Website |Website |

## Contact Fields {#contact-fields}

| SFDC field |Marketo field |
|---|---|
| Birthdate |Date of Birth |
| Created Date |SFDC Created Date |
| Contact Description |Person Notes |
| Email |Email Address |
| Business Fax |Fax Number |
| First Name |First Name |
| Email Opt Out |Unsubscribed |
| Deleted |SFDC Is Deleted |
| Last Name |Last Name |
| Lead Source |Source |
| Lead Score |Score |
| MailingCity |City |
| MailingCountry |Country |
| MailingPostalCode |Postal Code |
| MailingState |State |
| MailingStreet |Address |
| Mobile Phone |Mobile Phone Number |
| Business Phone |Phone Number |
| Salutation |Salutation |
| Title |Job Title |

## Account Fields {#account-fields}

| SFDC field |Marketo field |
|---|---|
| Annual Revenue |Annual Revenue |
| Billing City |Billing City |
| Billing Country |Billing Country |
| Billing Zip/Postal Code |Billing Postal Code |
| Billing State/Province |Billing State |
| Billing Street |Billing Address |
| Account Description |Company Notes |
| Industry |Industry |
| Deleted |SFDC Is Deleted |
| Account Name |Company Name |
| Employees |Num Employees |
| Account Phone |Main Phone |
| SIC Code |SIC Code |
| Account Site |Site |
| Account Type |SFDC Type |
| Website |Website |

## Salesforce-Related System Fields in Marketo (Read-only) {#salesforce-related-system-fields-in-marketo-read-only}

These fields are created in Marketo but can't be adjusted by customers.

| Field |Description |
|---|---|
| SFDC Id |The 18-character Salesforce Id |
| SFDC Type |Lead or Contact. If empty, the lead exists only as a person in Marketo |
| SFDC Created Date |Date created in SFDC (can be different from Created in Marketo) |
| SFDC is Deleted |Person used to be in SFDC but was deleted and now lives only in Marketo |
