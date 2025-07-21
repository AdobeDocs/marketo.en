---
description: "Step 3 of 3 - Connect Marketo Engage and [!DNL Veeva] CRM - Marketo Docs - Product Documentation"
title: "Step 3 of 3 - Connect Marketo Engage and [!DNL Veeva] CRM"
exl-id: aff91540-1d9d-448c-aae9-e6fa92a8ae01
feature: Veeva CRM
---
# Step 3 of 3: Connect Marketo Engage and [!DNL Veeva] CRM {#step-3-of-3-connect-marketo-engage-and-veeva-crm}

In this article, you'll configure Marketo Engage to sync with your configured [!DNL Veeva] CRM instance. **You'll see [!DNL Salesforce] in some of the pop-ups** as [!DNL Veeva] CRM is built on the [!DNL Salesforce] platform.

>[!PREREQUISITES]
>
>* [Step 1 of 3: Add Marketo Fields to [!DNL Veeva]](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-1-of-3-add-marketo-fields-to-veeva-crm.md){target="_blank"}
>* [Step 2 of 3: Create a [!DNL Veeva] User for Marketo](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-2-of-3-create-a-veeva-crm-user-for-marketo-engage.md){target="_blank"}

>[!IMPORTANT]
>
>Only one Marketo Instance can be connected to a [!DNL Veeva] CRM instance at a time.

## Connect to [!DNL Veeva] CRM using OAuth {#connect-to-veeva-crm-using-oauth}

1. In Marketo, Click **[!UICONTROL Admin]**. Select **[!UICONTROL CRM]** and click **[!UICONTROL Sync with Veeva]**.

   ![](assets/step-3-of-3-connect-marketo-engage-1.png)

   >[!NOTE]
   >
   >Be sure to [hide all fields you don't need](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/hide-a-salesforce-field-from-the-marketo-sync.md){target="_blank"} in Marketo from the sync user before clicking Sync Fields. Once you click Sync Fields all fields the user can see will be created in Marketo permanently and cannot be deleted.

1. Click **[!UICONTROL Login with Veeva]**.

   ![](assets/step-3-of-3-connect-marketo-engage-2.png)

   >[!NOTE]
   >
   >Check [!UICONTROL Sandbox] if you're syncing a Marketo Sandbox to a [!DNL Veeva] CRM Sandbox.

1. Click **[!UICONTROL Confirm Credentials]**.

   ![](assets/step-3-of-3-connect-marketo-engage-3.png)

1. A pop-up with the [!DNL Salesforce] login page will show up. Enter your “Marketo Sync User” credentials and click **[!UICONTROL Log In]**.

   ![](assets/step-3-of-3-connect-marketo-engage-4.png)

1. Enter the verification code you received via email (sent by [!DNL Salesforce]) and click **[!UICONTROL Verify]**.

   ![](assets/step-3-of-3-connect-marketo-engage-5.png)

1. Upon successful verification, the access page will show up requesting access. Click **[!UICONTROL Allow]**.

   ![](assets/step-3-of-3-connect-marketo-engage-6.png)

1. In a few minutes, a pop-up will appear in Marketo Engae. Click **[!UICONTROL Confirm Credentials]**.

   ![](assets/step-3-of-3-connect-marketo-engage-7.png)

## Start [!DNL Veeva] Sync {#start-veeva-sync}

1. Click **[!UICONTROL Start Veeva Sync]** to begin the persistent [!DNL Marketo-Veeva] CRM sync.

   ![](assets/step-3-of-3-connect-marketo-engage-8.png)

   >[!CAUTION]
   >
   >Marketo will not automatically de-dupe against a [!DNL Veeva] CRM sync, or when you manually enter leads.

1. Click **[!UICONTROL Start Sync]**.

   ![](assets/step-3-of-3-connect-marketo-engage-9.png)

>[!NOTE]
>
>The time to complete the initial sync varies depending on the size and complexity of your database.

## Verify Sync {#verify-sync}

Marketo provides status messages for the [!DNL Veeva] CRM sync in the Admin area. You can verify the sync is working correctly by following these steps.

1. In Marketo, click **[!UICONTROL Admin]**, then **[!UICONTROL Veeva]**.

   ![](assets/step-3-of-3-connect-marketo-engage-10.png)

1. The sync status is visible in the upper-right corner. It will show one of three messages: Last Synced, Sync in Progress, or Failed.

>[!MORELIKETHIS]
>
>[Configure Custom Objects](/help/marketo/product-docs/crm-sync/veeva-crm-sync/sync-details/custom-object-sync.md){target="_blank"}
