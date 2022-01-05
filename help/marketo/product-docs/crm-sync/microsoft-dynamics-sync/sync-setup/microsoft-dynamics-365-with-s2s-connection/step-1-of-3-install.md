---
description: Step 1 of 3 - Install the Marketo Solution with S2S Connection - Marketo Docs - Product Documentation
title: Step 1 of 3 - Install the Marketo Solution with S2S Connection
---
# Step 1 of 3: Install the Marketo Solution with S2S Connection {#step-1-of-3-install-the-marketo-solution-s2s}

Before you can sync Microsoft Dynamics 365 and Marketo, you need to first install the Marketo solution in Dynamics. **Dynamics Admin Permissions are required.**

>[!CAUTION]
>
>* Do not enable custom entity sync before the initial sync is completed. You will be notified via email once the initial sync is completed.
>* If you have Multi-Factor Authentication (MFA) enabled for your Dynamics Sync, you must disable it in order for Dynamics to properly sync with Marketo. For additional information, please contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support).

>[!NOTE]
>
>After you sync Marketo to a CRM, you cannot perform a new sync without replacing the instance.

>[!PREREQUISITES]
>
>[Download the Marketo Lead Management Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md)

1. Log in to **[Microsoft Office 365](https://login.microsoftonline.com/)**.

   ![](assets/image2015-3-16-15-3a58-3a55.png)

1. Click ![](assets/image2015-3-16-16-3a1-3a13.png) menu and select **CRM**.

   ![](assets/image2015-3-16-16-3a0-3a10.png)

1. Click ![](assets/image2015-5-13-10-3a5-3a8.png) menu. In the dropdown menu select **Settings** then select **Solutions**.

   ![](assets/image2015-5-13-10-3a4-3a1.png)

1. Click **Import.**

   ![](assets/image2015-3-19-8-3a34-3a8.png)

1. Click **Choose File.** Select the Marketo Lead Management solution you [downloaded](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). Click **Next**.

   ![](assets/image2015-10-9-14-3a44-3a14.png)

1. View the Solution Information and click **View solution package details**.

   ![](assets/image2015-10-9-15-3a4-3a16.png)

1. When you're done checking all the details, click **Close**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Now, back on the Solution Information page, click **Next**.

   ![](assets/image2015-10-9-14-3a59-3a24.png)

1. Make sure the SDK option checkbox is selected. Click **Import**.

   ![](assets/image2015-10-9-15-3a7-3a12.png)

   >[!TIP]
   >
   >You will need to enable pop-ups on your browser to complete the installation process.

1. Now wait for the import to finish. Get up and do some stretches.

   ![](assets/image2015-3-11-11-3a34-3a9.png)

1. Click **Close.**

   >[!NOTE]
   >
   >You may see a message saying "Marketo Lead Management completed with warning". This is fully expected.

   ![](assets/image2015-3-13-9-3a54-3a39.png)

1. Marketo Lead Management will now show up in the list of solutions.

   ![](assets/image2015-3-19-8-3a40-3a38.png)

1. Select **Marketo Lead Management** and click **Publish All Customizations.**

   ![](assets/image2015-3-19-8-3a41-3a21.png)

   High five! The installation is finished.

   >[!MORELIKETHIS]
   >
   >[Step 2 of 3: Set up the Marketo Solution with S2S Connection](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md)
