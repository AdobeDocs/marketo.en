---
unique-page-id: 1147027
description: Learn how to sync a person to Salesforce with a flow step. Push lead or contact data to SFDC when they enter the flow.
title: Sync Person to SFDC
exl-id: 4284ec35-6ac5-4084-beb7-976eb6fd7e3c
feature: Smart Campaigns, Salesforce Integration
TQID: https://experienceleague.adobe.com/jU7Hg1x8TUfxR4GnO1oxvJXh-8X3LVXll9z8k5Eck80
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
---
# Sync Person to SFDC {#sync-person-to-sfdc}

This flow step will insert Marketo-created people as leads into your Salesforce CRM.

>[!NOTE]
>
>Only available when integrated with [!DNL Salesforce].

1. By default, this flow step will assign to lead owners based on the Salesforce auto-assignment rules.

   ![](assets/sync-person-to-sfdc-1.png)

   >[!TIP]
   >
   >[!DNL Salesforce] requires that the person has Company and Last Name fields filled out. Otherwise, it will reject the lead record.

1. You can set a specific [!DNL Salesforce] user or lead queue as the lead owner.

   ![](assets/sync-person-to-sfdc-2.png)

   When using this flow step, the person is synced as a [!DNL Salesforce] lead immediately and does not need to wait for the regular sync.

   >[!CAUTION]
   >
   >[!DNL Salesforce] does not allow "Contacts" to be assigned to lead queues. In this case Marketo will create a duplicate "Lead" in [!DNL Salesforce].
