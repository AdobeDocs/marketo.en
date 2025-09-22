---
description: "Step 1 of 4 - Install the Marketo Solution with Resource Owner Password Control Connection - Marketo Docs - Product Documentation"
title: Step 1 of 4 - Install the Marketo Solution with Resource Owner Password Control Connection
exl-id: aab3bbb8-4e52-4c40-94d1-631af1d63f9f
feature: Microsoft Dynamics
---
# Step 1 of 4: Install the Marketo Solution with Resource Owner Password Control Connection {#step-1-of-4-install-the-marketo-solution-ropc}

Before you can sync [!DNL Microsoft Dynamics] 365 and Marketo, you need to first install the Marketo solution in [!DNL Dynamics]. **[!DNL Dynamics] Admin Permissions are required.**

>[!CAUTION]
>
>* Do not enable custom entity sync before the initial sync is completed. You will be notified via email once the initial sync is completed.
>* If you have Multi-Factor Authentication (MFA) enabled for your [!DNL Dynamics] Sync, you must disable it in order for [!DNL Dynamics] to properly sync with Marketo. For additional information, please contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support).

>[!NOTE]
>
>After you sync Marketo to a CRM, you cannot perform a new sync without replacing the instance.

>[!PREREQUISITES]
>
>[Download the Marketo Lead Management Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md)

1. Log in to **[[!DNL Microsoft Office 365]](https://login.microsoftonline.com/)**.

   ![](assets/image2015-3-16-15-3a58-3a55.png)

1. Click ![](assets/image2015-3-16-16-3a1-3a13.png) menu and select **[!UICONTROL CRM]**.

   ![](assets/image2015-3-16-16-3a0-3a10.png)

1. Click ![](assets/image2015-5-13-10-3a5-3a8.png) menu. In the dropdown menu select **[!UICONTROL Settings]** then select **[!UICONTROL Solutions]**.

   ![](assets/image2015-5-13-10-3a4-3a1.png)

1. Click **[!UICONTROL Import]**.

   ![](assets/image2015-3-19-8-3a34-3a8.png)

1. Click **[!UICONTROL Choose File]**. Select the Marketo Lead Management solution you [downloaded](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). Click **[!UICONTROL Next]**.

   ![](assets/image2015-10-9-14-3a44-3a14.png)

1. View the Solution Information and click **[!UICONTROL View solution package details]**.

   ![](assets/image2015-10-9-15-3a4-3a16.png)

1. When you're done checking all the details, click **[!UICONTROL Close]**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Now, back on the Solution Information page, click **[!UICONTROL Next]**.

   ![](assets/image2015-10-9-14-3a59-3a24.png)

1. Make sure the SDK option checkbox is selected. Click **[!UICONTROL Import]**.

   ![](assets/image2015-10-9-15-3a7-3a12.png)

   >[!TIP]
   >
   >You will need to enable pop-ups on your browser to complete the installation process.

1. Now wait for the import to finish. Get up and do some stretches.

   ![](assets/image2015-3-11-11-3a34-3a9.png)

1. Click **[!UICONTROL Close]**.

   >[!NOTE]
   >
   >You may see a message saying "Marketo Lead Management completed with warning". This is fully expected.

   ![](assets/image2015-3-13-9-3a54-3a39.png)

1. "Marketo Lead Management" will now show up in the list of solutions.

   ![](assets/image2015-3-19-8-3a40-3a38.png)

1. Select **[!UICONTROL Marketo Lead Management]** and click **[!UICONTROL Publish All Customizations]**.

   ![](assets/image2015-3-19-8-3a41-3a21.png)

   Nice work! The installation is finished.

   >[!MORELIKETHIS]
   >
   >[Step 2 of 4: Set up the Marketo Solution with Resource Owner Password Control Connection](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md){target="_blank"}
