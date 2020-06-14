---
unique-page-id: 2953467
description: SFDC Sync: Opportunity Sync - Marketo Docs - Product Documentation
title: SFDC Sync: Opportunity Sync
---

# SFDC Sync: Opportunity Sync {#sfdc-sync-opportunity-sync}

SFDC Sync: Opportunity Sync - Marketo Docs - Product Documentation

### What's in this article? {#what-s-in-this-article}

[How are opportunity details kept in sync between the two systems?](#sfdcsync-opportunitysync-howareopportunitydetailskeptinsyncbetweenthetwosystems?)  
[Can I initiate an Opportunity Sync?](#sfdcsync-opportunitysync-caniinitiateanopportunitysync?)  
[Does Marketo support more than one currency in the Opportunity Amount?](#sfdcsync-opportunitysync-doesmarketosupportmorethanonecurrencyintheopportunityamount?)  
[How does Marketo associate opportunities and contacts?](#sfdcsync-opportunitysync-howdoesmarketoassociateopportunitiesandcontacts?)  
[How can I see all the opportunities of a person?](#sfdcsync-opportunitysync-howcaniseealltheopportunitiesofaperson?)  
[What are the triggers/filters related to opportunity?](#sfdcsync-opportunitysync-whatarethetriggers/filtersrelatedtoopportunity?)

#### How are opportunity details kept in sync between the two systems? {#sfdcsync-opportunitysync-howareopportunitydetailskeptinsyncbetweenthetwosystems?}

The sync is one way:&nbsp;from Salesforce to Marketo. Updates to opportunities in Salesforce will be synced to Marketo.

>[!NOTE]
>
>`The` [credentials you enter in Marketo for Salesforce](../../../../../welcome-to-marketo-docs/product-docs/crm-sync/salesforce-sync/setup/enterprise/unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-(enterprise/unlimited).md) `are used to sync data over. Only data those credentials have access to will be included.`

#### Can I initiate an Opportunity Sync? {#sfdcsync-opportunitysync-caniinitiateanopportunitysync?}

No, you can't. The changes to any opportunity in Salesforce will be synced over to Marketo automatically.

#### Does Marketo support more than one currency in the Opportunity Amount? {#sfdcsync-opportunitysync-doesmarketosupportmorethanonecurrencyintheopportunityamount?}

No, Marketo supports only one currency. The opportunity amount will be synced from Salesforce but the currency will be the&nbsp; [default currency](https://docs.marketo.com/display/DOCS/Set+Default+Location+Settings+for+a+Subscription#SetDefaultLocationSettingsforaSubscription-SettheDefaultCurrencySettingsforaSubscription)&nbsp;in your Marketo subscription.

#### How does Marketo associate opportunities and contacts? {#sfdcsync-opportunitysync-howdoesmarketoassociateopportunitiesandcontacts?}

Marketo associates Opportunities and contacts using&nbsp; [Opportunity Contact Roles](https://help.salesforce.com/HTViewHelpDoc?id=contactroles.htm). Opportunities without any Contact Roles assigned will sync to Marketo, but won't belong to anyone. For example, the person won't qualify the Has Opportunity filter.&nbsp;

#### How can I see all the opportunities of a person? {#sfdcsync-opportunitysync-howcaniseealltheopportunitiesofaperson?}

You can view a list of opportunities in the **Opportunity Info** tab in the [Person Detail](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md)&nbsp;page.

#### What are the triggers/filters related to opportunity? {#sfdcsync-opportunitysync-whatarethetriggers/filtersrelatedtoopportunity?}

Triggers:

* Added to opportunity
* Removed from opportunity
* Opportunity is updated

Filters:

* Has Opportunity
* Opportunity was Updated/Not  `Opportunity was Updated`
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

Marketo has the best Salesforce sync in the world! 