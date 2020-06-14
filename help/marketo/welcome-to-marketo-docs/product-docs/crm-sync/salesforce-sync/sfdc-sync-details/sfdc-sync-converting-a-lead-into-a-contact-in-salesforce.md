---
unique-page-id: 2953465
description: SFDC Sync: Converting a Lead into a Contact in Salesforce - Marketo Docs - Product Documentation
title: SFDC Sync: Converting a Lead into a Contact in Salesforce
---

# SFDC Sync: Converting a Lead into a Contact in Salesforce {#sfdc-sync-converting-a-lead-into-a-contact-in-salesforce}

SFDC Sync: Converting a Lead into a Contact in Salesforce - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Imagine three different scenarios in Salesforce: (not using the [Convert Person flow step](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/convert-person.md)&nbsp;in Marketo)

1. Converting a Lead into a **new contact and new account**
1. Converting a Lead into a **new contact** in an **existing account**

1. Converting a Lead to an **existing contact** in an **existing account** (this works identical to [merging](sfdc-sync-merging-a-lead/contact/person.md))

In all three cases you end up with **1 contact and no leads in Salesforce and 1 contact and no people in Marketo.**

In Marketo, the record will now have an SFDC Type = Contact.

>[!TIP]
>
>When converting in Salesforce, make sure your [lead custom fields are mapped well](https://help.salesforce.com/apex/HTViewHelpDoc?id=customize_mapleads.htm). You don't want to lose any data.

You can trigger and filter using: “Lead is Converted” and “Lead was Converted.” 