---
unique-page-id: 10095307
description: Custom Sync Filter Rules for an Email Address - Marketo Docs - Product Documentation
title: Custom Sync Filter Rules for an Email Address
exl-id: d1d51310-0c59-447c-818c-b25aa281c15c
---
# Custom Sync Filter Rules for an Email Address {#custom-sync-filter-rules-for-an-email-address}

To prevent syncing of records that don't have an email address, follow these rules.

* When a lead is created OR when the lead’s email address field is updated, check if the lead has an email address and if it does, change Sync to Mkto to **[!UICONTROL True]**. Otherwise change to **[!UICONTROL False]**

* When a contact is created OR when the contact’s email address field is updated, check if the contact has an email address and if it does, change Sync to Mkto to **[!UICONTROL True]** and change Sync to Mkto to **[!UICONTROL True]** on the Account record. Otherwise, change to **[!UICONTROL False]**

* When the contact’s Company Name (parentcustomerid) field is updated, check if the contact’s Sync to Mkto field is true. If it is, change Sync to Mkto on the account to **[!UICONTROL True]** also
* When the opportunity’s Potential Customer (customerid) field or Contact (parentcontactid) is updated, check if the account’s Sync to Mkto field is true or if the contact’s Sync to Mkto field is true. If it is, change Sync to Mkto on the opportunity to **[!UICONTROL True]** also
