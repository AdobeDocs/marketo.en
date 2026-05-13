---
unique-page-id: 1147034
description: Learn how to add people to a Salesforce campaign with a flow step. Sync Marketo leads to SFDC campaigns.
title: Add to SFDC Campaign
exl-id: a5e14cc7-fd83-4a2c-aacb-e515669c9d21
feature: Smart Campaigns, Salesforce Integration
TQID: https://experienceleague.adobe.com/7fp6JSlxwdg0Yoniw9E4VvmRNvyaVyhwyOc10veDvR4
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
---
# Add to SFDC Campaign {#add-to-sfdc-campaign}

This flow step can be used in Marketo Engage campaigns or as a single flow step to add people as leads in a Salesforce campaign. If the lead does not yet exist in Salesforce, it will automatically be synced over and added to the campaign with the specified status.

>[!NOTE]
>
>Only available when integrated with [!DNL Salesforce].

![](assets/add-to-sfdc-campaign-1.png)

## Usage {#usage}

1. Find and select the [!DNL Salesforce] campaign you want to add your leads to.

   ![](assets/add-to-sfdc-campaign-2.png)

   >[!TIP]
   >
   >If you cannot see a Salesforce campaign in the campaign list:
   >
   > 1. Verify the [campaign sync is enabled](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md){target="_blank"}.
   > 1. Confirm that your [Marketo Sync User](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"} is a [Marketing User](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync/make-marketo-sync-user-a-marketing-user.md){target="_blank"} in Salesforce.

   >[!TIP]
   >
   >You can use Salesforce campaign [My Tokens](/help/marketo/product-docs/core-marketo-concepts/programs/tokens/managing-my-tokens.md){target="_blank"} to make program cloning easier.

1. Select the [!DNL Salesforce] campaign member status you want to assign to leads when they're added.

   ![](assets/add-to-sfdc-campaign-3.png)

   >[!CAUTION]
   >
   >If a person is already a lead member of the Salesforce campaign, they will be skipped and their status will NOT be updated. You can use [change their status in an SFDC campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/change-status-in-sfdc-campaign.md){target="_blank"} instead.
