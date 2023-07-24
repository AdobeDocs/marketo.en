---
unique-page-id: 2953473
description: SFDC Sync - Activity Sync - Marketo Docs - Product Documentation
title: SFDC Sync - Activity Sync
exl-id: 780e9cb7-b8b2-4a79-a0b8-d9d34a655330
feature: Salesforce Integration
---
# SFDC Sync: Activity Sync {#sfdc-sync-activity-sync}

Marketo also syncs over the Salesforce activities data. Here are some questions and answers.

## What types of activity data does Marketo sync over? {#what-types-of-activity-data-does-marketo-sync-over}

Marketo syncs over both Events and Tasks associated with a lead or contact.

## How are activity details kept in sync between the two systems? {#how-are-activity-details-kept-in-sync-between-the-two-systems}

The sync is one way, from Salesforce to Marketo. But you can create a task in Salesforce using the [Create Task](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) flow step or [Customize Activities Sync](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/customize-activities-sync.md) to Salesforce.

## Can I create a task using Marketo? {#can-i-create-a-task-using-marketo}

Yes, you can use the [Create Task flow action](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md).

## What are the triggers/filters related to activity? {#what-are-the-triggers-filters-related-to-activity}

Triggers

* Activity is Logged
* Activity is Updated

Filters

* Activity was Logged/Not Activity was Logged
* Activity was Updated/Not Activity was Updated

>[!TIP]
>
>Not sure about that "Not Activity" wording? The "not" refers to an Inactivity Filter. Learn more about them here: [Use Inactivity Filters in a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md)
