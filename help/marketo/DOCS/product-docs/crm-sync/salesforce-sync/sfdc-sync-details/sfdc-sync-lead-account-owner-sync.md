---
unique-page-id: 2953463
description: SFDC Sync: Lead/Account Owner Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Lead/Account Owner Sync
---

# SFDC Sync: Lead/Account Owner Sync {#sfdc-sync-lead-account-owner-sync}

SFDC Sync: Lead/Account Owner Sync - Marketo Docs - Product Documentation

These are technically syncing the "user" table in Salesforce, however we will refer to it as Lead/Account Owner fields.

### What's in this article? {#whats-in-this-article}

[Which fields will sync to Marketo?](#which-fields-will-sync-to-marketo)  
[Can I change the lead owner in Marketo?](#can-i-change-the-lead-owner-in-marketo)  
[What can I do with this data?](#what-can-i-do-with-this-data)

#### Which fields will sync to Marketo? {#which-fields-will-sync-to-marketo}

For each person synced to Marketo, we also sync the following owner fields:

* Sales Owner First Name
* Sales Owner Last Name
* Sales Owner Title 
* Sales Owner Phone Number
* Sales Owner Email Address

For each contact, we sync the above five lead owner fields as well as these account owner fields:

* Account Owner First Name 
* Account Owner Last Name 
* Account Owner Email Address

#### Can I change the lead owner in Marketo? {#can-i-change-the-lead-owner-in-marketo}

Absolutely, just use the [Change Owner](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md) flow action.

>[!NOTE]
>
>You cannot change the owner information using the [Using the Person Detail Page](../../../../product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md).

#### What can I do with this data? {#what-can-i-do-with-this-data}

There are lots of reasons to use this data such as

* Send a personalized email with signature from the sales owner
* Filter on specific sales reps for marketing or even analyzing effectiveness
* Assignment (and re-assignment) rules in Marketo
* Use them in the [Change Owner](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md),&nbsp; [Sync Person to SFDC](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md), and&nbsp; [Create Task](../../../../product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md)&nbsp;flow actions

Marketo sure has an awesome Salesforce sync. No one else does it so well!
