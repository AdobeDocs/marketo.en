---
unique-page-id: 2953467
description: SFDC Sync - Opportunity Sync - Marketo Docs - Product Documentation
title: SFDC Sync - Opportunity Sync
exl-id: f8acc528-c631-43f0-8899-2f3c6fdabe9e
feature: Salesforce Integration
---
# SFDC Sync: Opportunity Sync {#sfdc-sync-opportunity-sync}

## How are opportunity details kept in sync between the two systems? {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

The sync is one way: from Salesforce to Marketo. Updates to opportunities in Salesforce will be synced to Marketo.

>[!NOTE]
>
>The [credentials you enter in Marketo for Salesforce](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md) are used to sync data over. Only data those credentials have access to will be included.

## Can I initiate an Opportunity Sync? {#can-i-initiate-an-opportunity-sync}

No, you can't. The changes to any opportunity in Salesforce will be synced over to Marketo automatically.

## Does Marketo support more than one currency in the Opportunity Amount? {#does-marketo-support-more-than-one-currency-in-the-opportunity-amount}

No, Marketo supports only one currency. The opportunity amount will be synced from Salesforce but the currency will be the [default currency](/help/marketo/product-docs/administration/settings/set-default-location-settings-for-a-subscription.md#set-the-default-currency-settings-for-a-subscription) in your Marketo subscription.

## How does Marketo associate opportunities and contacts? {#how-does-marketo-associate-opportunities-and-contacts}

Marketo associates Opportunities and contacts using [Opportunity Contact Roles](https://help.salesforce.com/HTViewHelpDoc?id=contactroles.htm). Opportunities without any Contact Roles assigned will sync to Marketo, but won't belong to anyone. For example, the person won't qualify the Has Opportunity filter.

## How can I see all the opportunities of a person? {#how-can-i-see-all-the-opportunities-of-a-person}

You can view a list of opportunities in the **Opportunity Info** tab in the [Person Detail](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md) page.

## What are the triggers/filters related to opportunity? {#what-are-the-triggers-filters-related-to-opportunity}

Triggers:

* Added to opportunity
* Removed from opportunity
* Opportunity is updated

Filters:

* Has Opportunity
* Opportunity was Updated/Not Opportunity was Updated
* Was Added to Opportunity/Not Was Added to Opportunity
* Was Removed from Opportunity/Not Was Removed from Opportunity
* Total Opty Amount
* Number of Optys
* Total Opty Expected Revenue

>[!TIP]
>
>Check out the constraints on filters and triggers. Lots of cool details in there.
>
>Just make a new field in the opportunity object in Salesforce and it will automatically become a constraint!
