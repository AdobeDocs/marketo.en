---
unique-page-id: 1147154
description: Sync an SFDC Campaign with a Program - Marketo Docs - Product Documentation
title: Sync an SFDC Campaign with a Program
---

# Sync an SFDC Campaign with a Program {#sync-an-sfdc-campaign-with-a-program}

Marketo allows you to sync your programs with Salesforce campaigns to maintain the same list of people in both systems, including their statuses. Let's get started!  

>[!PREREQUISITES]
>
>You will need to [enable Salesforce campaign sync](../../../../product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md) first.

>[!CAUTION]
>
>When syncing an SFDC campaign with a Marketo program, the implied SFDC actions (e.g., add to SFDC Campaign, Sync to SFDC) will be disabled for child campaigns of the program.

1. Go to **Marketing Activities**.

   ![](assets/login-marketing-activities-1.png)

1. Select your program.

   ![](assets/image2015-7-22-8-3a47-3a28.png)

1. Click **Program Actions**, then select **Salesforce Campaign Sync**.

   ![](assets/image2015-7-22-8-3a48-3a5.png)

1. Select **Create New **or choose an existing Salesforce campaign.

   >[!TIP]
   >
   >If you select an existing Salesforce campaign, make sure to [match the program statuses of the Salesforce campaign and the Marketo program](../../../../product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-errors/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md).

1. Enter a name for the new campaign and click **Save**.

   ![](assets/image2015-7-22-8-3a57-3a19.png)

1. Now you can verify the campaign sync details in the program summary page.

   ![](assets/image2015-7-22-8-3a59-3a33.png)

   Excellent! Now any program status changes in Marketo are synced to the SFDC campaign and vice versa.

