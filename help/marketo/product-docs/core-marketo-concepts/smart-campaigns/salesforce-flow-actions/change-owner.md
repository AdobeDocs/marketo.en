---
unique-page-id: 1147021
description: Change Owner - Marketo Docs - Product Documentation
title: Change Owner
exl-id: b22c5cd8-1b53-4802-8b49-7f607c8a601b
feature: Smart Campaigns, Salesforce Integration
---
# Change Owner {#change-owner}

If you have existing people that are already assigned to an owner, you can use this flow step to re-assign them to another owner.

![](assets/image2014-9-22-15-3a1-3a3.png)

**Usage**

1. Simply pick the owner or the lead queue you want to change to and go!

   ![](assets/image2014-9-22-15-3a1-3a6.png)

   >[!CAUTION]
   >
   >Salesforce does not allow contacts to be assigned to lead queues. For a record that's an SFDC contact:
   >
   >1. Marketo will create a duplicate lead **only** when the contact is synced to Salesforce. In other words, if you use the **[Sync Person to SFDC](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/sync-person-to-sfdc.md)** flow step with `AssignTo=<a lead queue>`, Marketo will create a duplicate lead in Salesforce and assign it to the lead queue.
   >
   >1. If you use the **[!UICONTROL Change Owner]** flow step on a contact, Marketo creates a duplicate lead in Salesforce. To avoid this, use a filter on the 'SFDC Type' field that limits the action to leads only.

   >[!NOTE]
   >
   >If the record does not yet exist in your Salesforce account, we will sync it over, then assign it to the selected user.
