---
unique-page-id: 7516241
description: SFDC Sync -Lead Queue - Marketo Docs - Product Documentation
title: SFDC Sync -Lead Queue
---

# SFDC Sync: Lead Queue {#sfdc-sync-lead-queue}

Marketo allows you to add people to [Salesforce lead queues](https://help.salesforce.com/apex/HTViewHelpDoc?id=queues_overview.htm) to help with lead distribution. Here are the details.

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

## How to assign a person to a queue in Marketo? {#how-to-assign-a-person-to-a-queue-in-marketo}

You can assign a person to a Salesforce lead queue using either of these flow actions:

* [Sync Person to SFDC](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)
* [Change Owner](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md)

>[!NOTE]
>
>You can't create or change queues in Marketo.

## How is lead owner information stored if the person belongs to a queue? {#how-is-lead-owner-information-stored-if-the-person-belongs-to-a-queue}

If a lead is owned by a queue in Salesforce, these sales owner fields are kept empty until the lead is assigned to an owner.

* Sales Owner First Name
* Sales Owner Last Name
* Sales Owner Title 
* Sales Owner Phone Number
* Sales Owner Email Address

