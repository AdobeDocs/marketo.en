---
unique-page-id: 2953473
description: SFDC Sync: Activity Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Activity Sync
---

# SFDC Sync: Activity Sync {#sfdc-sync-activity-sync}

SFDC Sync: Activity Sync - Marketo Docs - Product Documentation

Marketo also syncs over the Salesforce activities data. Here are some questions and answers.

### What's in this article? {#what-s-in-this-article}

[What types of activity data does Marketo sync over?](#sfdcsync-activitysync-whattypesofactivitydatadoesmarketosyncover?)  
[How are activity details kept in sync between the two systems?](#sfdcsync-activitysync-howareactivitydetailskeptinsyncbetweenthetwosystems?)  
[Can I create a task using Marketo?](#sfdcsync-activitysync-canicreateataskusingmarketo?)  
[What are the triggers/filters related to activity?](#sfdcsync-activitysync-whatarethetriggers/filtersrelatedtoactivity?)

#### What types of activity data does Marketo sync over? {#sfdcsync-activitysync-whattypesofactivitydatadoesmarketosyncover?}

Marketo syncs over both Events and Tasks associated with a lead or contact.

#### How are activity details kept in sync between the two systems? {#sfdcsync-activitysync-howareactivitydetailskeptinsyncbetweenthetwosystems?}

The sync is one way, from&nbsp;Salesforce to Marketo. But you can create a task in Salesforce using the [Create Task](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) flow step or [Customize Activities Sync](../../../../../welcome-to-marketo-docs/product-docs/crm-sync/salesforce-sync/setup/optional-steps/customize-activities-sync.md) to Salesforce.&nbsp;

#### Can I create a task using Marketo? {#sfdcsync-activitysync-canicreateataskusingmarketo?}

Yes, you can use the [Create Task flow action](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md).

#### What are the triggers/filters related to activity? {#sfdcsync-activitysync-whatarethetriggers/filtersrelatedtoactivity?}

Triggers

* Activity is Logged
* Activity is Updated

Filters

* Activity was Logged/Not Activity was Logged
* Activity was Updated/Not Activity was Updated

>[!TIP]
>
>Not sure about that "Not Activity" wording? The "not" refers to an Inactivity Filter. Learn more about them here: [Use Inactivity Filters in a Smart List](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/use-inactivity-filters-in-a-smart-list.md)

&nbsp; 