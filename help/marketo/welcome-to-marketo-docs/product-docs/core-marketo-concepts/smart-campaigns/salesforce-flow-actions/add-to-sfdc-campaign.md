---
unique-page-id: 1147034
description: Add to SFDC Campaign - Marketo Docs - Product Documentation
title: Add to SFDC Campaign
---

# Add to SFDC Campaign {#add-to-sfdc-campaign}

Add to SFDC Campaign - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

>[!NOTE]
>
>Only available when integrated with Salesforce.

#### Overview {#addtosfdccampaign-overview}

This flow step can be used in Marketo campaigns or as a single flow step to add people as leads in a Salesforce campaign. If the lead does not yet exist in Salesforce, it will automatically be synced over and added to the campaign with the specified status.

![](assets/image2014-9-22-15-3a43-3a36.png) 

#### Usage {#addtosfdccampaign-usage}

1. Find and select the Salesforce campaign you want to add your leads to.

   ![](assets/image2014-9-22-15-3a43-3a45.png)

   >[!TIP]
   >
   >If you can't see a Salesforce campaign in the Campaign list:
   >
   >    
   >    
   >    1. Make sure the [campaign sync is enabled](../../../../../welcome-to-marketo-docs/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable/disable-campaign-sync.md).
   >    1. Confirm that your [Marketo Sync User](../../../../../welcome-to-marketo-docs/product-docs/crm-sync/salesforce-sync/setup/enterprise/unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-(enterprise/unlimited).md) is a [Marketing User](../../../../../welcome-to-marketo-docs/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable/disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md) in Salesforce.
   >    
   >    
   >

   >[!TIP]
   >
   >`You can use Salesforce campaign` [My Tokens](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md) `to make program cloning easier.`

1. Select the Salesforce campaign member status you want to assign to leads when they're added.

   ![](assets/image2014-9-22-15-3a45-3a2.png)

   >[!CAUTION]
   >
   >If a person is already a lead member of the Salesforce campaign, they will be skipped and their status will NOT be updated. You can use [change their status in an SFDC campaign](change-status-in-sfdc-campaign.md) instead.

