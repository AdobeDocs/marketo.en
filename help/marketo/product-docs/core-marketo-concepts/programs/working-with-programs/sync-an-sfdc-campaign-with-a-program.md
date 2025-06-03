---
unique-page-id: 1147154
description: Sync an SFDC Campaign with a Program - Marketo Docs - Product Documentation
title: Sync an SFDC Campaign with a Program
exl-id: b95be580-c960-4a76-9d43-c7f624f43d03
feature: Programs
---
# Sync an SFDC Campaign with a Program {#sync-an-sfdc-campaign-with-a-program}

Marketo Engage allows you to sync your programs with [!DNL Salesforce] campaigns to maintain the same list of people in both systems, including their statuses. Let's get started!  

>[!PREREQUISITES]
>
>You will need to [enable [!DNL Salesforce] campaign sync](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/optional-steps/enable-disable-campaign-sync.md){target="_blank"} first.

>[!CAUTION]
>
>When syncing an SFDC campaign with a Marketo Engage program, the implied SFDC actions (e.g., add to SFDC Campaign, Sync to SFDC) will be disabled for child campaigns of the program.

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/login-marketing-activities-1.png)

1. Select your program.

   ![](assets/image2015-7-22-8-3a47-3a28.png)

1. Click **[!UICONTROL Program Actions]**, then select **[!UICONTROL Salesforce Campaign Sync]**.

   ![](assets/image2015-7-22-8-3a48-3a5.png)

1. Select **[!UICONTROL Create New]** or choose an existing [!DNL Salesforce] campaign.

   >[!TIP]
   >
   >If you select an existing [!DNL Salesforce] campaign, make sure to [match the program statuses of the [!DNL Salesforce] campaign and the Marketo program](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md){target="_blank"}.

1. Enter a name for the new campaign and click **[!UICONTROL Save]**.

   ![](assets/image2015-7-22-8-3a57-3a19.png)

1. Now you can verify the campaign sync details in the program summary page.

   ![](assets/image2015-7-22-8-3a59-3a33.png)

   Excellent! Now any program status changes in Marketo are synced to the SFDC campaign and vice versa.
