---
unique-page-id: 1147027
description: Sync Person to SFDC - Marketo Docs - Product Documentation
title: Sync Person to SFDC
exl-id: 4284ec35-6ac5-4084-beb7-976eb6fd7e3c
feature: Smart Campaigns, Salesforce Integration
---
# Sync Person to SFDC {#sync-person-to-sfdc}

This flow step will insert Marketo-created people as leads into your Salesforce CRM.

![](assets/sync-person-to-sfdc.png)

>[!NOTE]
>
>Only available when integrated with Salesforce.

1. By default, this flow step will assign to lead owners based on the Salesforce auto-assignment rules.

   ![](assets/sync-person-to-sfdc.png)

   >[!TIP]
   >
   >Salesforce requires that the person has Company and Last Name fields filled out. Otherwise, it will reject the lead record.

1. You can set a specific Salesforce user or lead queue as the lead owner.

   ![](assets/sync-person-to-sfdc-2.png)

   When using this flow step, the person is synced as a Salesforce lead immediately and does not need to wait for the regular sync.

   >[!CAUTION]
   >
   >Salesforce does not allow "Contacts" to be assigned to lead queues. In this case Marketo will create a duplicate "Lead" in Salesforce.
