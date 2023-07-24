---
unique-page-id: 2953463
description: SFDC Sync - Lead/Account Owner Sync - Marketo Docs - Product Documentation
title: SFDC Sync - Lead/Account Owner Sync
exl-id: b9effcc2-f426-4390-aef1-42f4e525b182
feature: Salesforce Integration
---
# SFDC Sync: Lead/Account Owner Sync {#sfdc-sync-lead-account-owner-sync}

These are technically syncing the "user" table in Salesforce, however we will refer to it as Lead/Account Owner fields.

## Which fields will sync to Marketo? {#which-fields-will-sync-to-marketo}

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

## Can I change the lead owner in Marketo? {#can-i-change-the-lead-owner-in-marketo}

Absolutely, just use the [Change Owner](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md) flow action.

>[!NOTE]
>
>You cannot change the owner information using the [Using the Person Detail Page](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md).

## What can I do with this data? {#what-can-i-do-with-this-data}

There are lots of reasons to use this data such as

* Send a personalized email with signature from the sales owner
* Filter on specific sales reps for marketing or even analyzing effectiveness
* Assignment (and re-assignment) rules in Marketo
* Use them in the [Change Owner](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-owner.md), [Sync Person to SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md), and [Create Task](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) flow actions

Marketo sure has an awesome Salesforce sync. No one else does it so well!
