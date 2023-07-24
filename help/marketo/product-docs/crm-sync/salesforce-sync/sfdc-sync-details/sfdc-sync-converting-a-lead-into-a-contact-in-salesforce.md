---
unique-page-id: 2953465
description: SFDC Sync - Converting a Lead into a Contact in Salesforce - Marketo Docs - Product Documentation
title: SFDC Sync - Converting a Lead into a Contact in Salesforce
exl-id: 9c9dbe9a-80a6-4153-ac86-96f85025fe77
feature: Salesforce Integration
---
# SFDC Sync: Converting a Lead into a Contact in Salesforce {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

Imagine three different scenarios in Salesforce: (not using the [Convert Person flow step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md) in Marketo)

1. Converting a Lead into a **new contact and new account**
1. Converting a Lead into a **new contact** in an **existing account**

1. Converting a Lead to an **existing contact** in an **existing account** (this works identical to [merging](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-merging-a-lead-contact-person.md))

In all three cases you end up with **1 contact and no leads in Salesforce and 1 contact and no people in Marketo.**

In Marketo, the record will now have an SFDC Type = Contact.

>[!TIP]
>
>When converting in Salesforce, make sure your [lead custom fields are mapped well](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm). You don't want to lose any data.

You can trigger and filter using: “Lead is Converted” and “Lead was Converted.”
