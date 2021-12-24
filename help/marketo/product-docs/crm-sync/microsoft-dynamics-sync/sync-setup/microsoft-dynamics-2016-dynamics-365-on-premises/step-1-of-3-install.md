---
description: Install Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises 1 of 3 - Marketo Docs - Product Documentation
title: Install Marketo for Microsoft Dynamics 2016/Dynamics 365 On-Premises Step 1 of 3
exl-id: 0a494ae7-87da-4ff9-bb47-990b957533e1
---
# Step 1 of 3: Configure Sync User for Marketo (2016 On-Prem /Dynamics 365 On-Premises) {#step-of-configure-sync-user-for-marketo-on-premises-2016}

Before you can sync Microsoft Dynamics 2015 On-Premises or 2016 (Dynamics 365) with Marketo, you need to first install the Marketo solution in Dynamics.

>[!NOTE]
>
>After you sync Marketo to a CRM, you cannot sync a new CRM to the existing Marketo instance.

>[!PREREQUISITES]
>
>If you're using Microsoft Dynamics On-Premise, you must have [Internet Facing Deployment](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) with [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0+ (ADFS) configured. Note: The IFD document downloads automatically when you click the link.
>
>[Download the Marketo Lead Management Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) before you start.

>[!NOTE]
>
>**Dynamics Admin Permissions required.**
>
>You need CRM administrator privileges to perform this sync.

1. Log in to **Dynamics.** Click the **Microsoft Dynamics CRM** drop-down menu and select **Settings**.

   ![](assets/image2015-3-19-8-33-29.png)

1. Under **Settings**, select **Solutions**.

   ![](assets/image2015-3-19-8-33-3.png)

1. Click **Import**.

   ![](assets/image2015-3-19-8-34-8.png)

1. Click **Browse** and select the solution you [downloaded](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). Click **Next**.

   ![](assets/image2015-3-19-9-20-56.png)

1. View the Solution Information and click **View solution package details**.

   ![](assets/image2015-11-18-11-12-8.png)

1. When you're done checking all the details, click **Close**.

   ![](assets/step6.png)

1. Back on the Solution Information page, click **Next**.

   ![](assets/image2015-3-19-9-21-50.png)

1. Make sure the SDK option checkbox is selected. Click **Import**.

   ![](assets/image2015-3-19-9-19-12.png)

1. Wait for the import to finish.

   >[!TIP]
   >
   >You will need to enable pop-ups on your browser to complete the installation process.

   ![](assets/image2015-3-11-11-34-9.png)

1. Download a log file (if you want) and click **Close**.

   >[!NOTE]
   >
   >You may see a message saying "Marketo Lead Management completed with warning". This is fully expected.

   ![](assets/image2015-3-13-9-54-39.png)

1. Marketo Lead Management will now appear on the **All Solutions** page.

   ![](assets/image2015-3-19-8-40-38.png)

1. Select the Marketo solution and click **Publish All Customizations**.

   ![](assets/image2015-3-19-8-41-21.png)

   High five! The installation is finished.

   >[!CAUTION]
   >
   >Disabling any of the Marketo SDK Messaging Processes will result in a broken install!

   >[!MORELIKETHIS]
   >
   >[Install Marketo for Dynamics 2015 On-Prem and 2016 365 On-Prem Step 2 of 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2016-dynamics-365-on-premises/step-2-of-3-set-up.md)
