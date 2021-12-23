---
unique-page-id: 3571813
description: Step 1 of 3 -Install the Marketo Solution in Dynamics (2013 On-Premises) - Marketo Docs - Product Documentation
title: Step 1 of 3 -Install the Marketo Solution in Dynamics (2013 On-Premises)
exl-id: 89f90bca-b459-447f-bbdd-363f232a1059
---
# Step 1 of 3: Install the Marketo Solution in Dynamics (2013 On-Premises) {#step-of-install-the-marketo-solution-in-dynamics-on-premises}

Before you can sync Microsoft Dynamics On-Premises and Marketo, you need to first install the Marketo solution in Dynamics.

>[!NOTE]
>
>After you sync Marketo to a CRM, you cannot perform a new sync without replacing the instance.

>[!PREREQUISITES]
>
>You must have [Internet Facing Deployment](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701) (IFD) with [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx) 2.0, 2.1 or 3.0 (ADFS) configured. Note: The IFD document downloads automatically when you click the link.
>
>[Download the Marketo Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md) before you start.

>[!NOTE]
>
>**Dynamics Admin Permissions required.**
>
>You need CRM administrator privileges to perform this sync.

1. Log into **Dynamics**. Click the **Microsoft Dynamics CRM** drop-down menu and select **Settings**.

   ![](assets/image2014-12-11-10-3a39-3a41.png)

1. Under **Settings**, select **Solutions**.

   ![](assets/image2014-12-11-10-3a39-3a51.png)

1. Click **Import**.

   ![](assets/image2015-3-26-9-3a52-3a10.png)

1. Click **Browse** and select the [downloaded solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md). Click **Next**.

   ![](assets/image2015-3-26-9-3a54-3a1.png)

1. View the Solution Information and click **View solution package details**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. When you're done checking all the details, click **Close**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Back on the Solution Information page, click **Next**.

   ![](assets/image2015-3-26-9-3a55-3a17.png)

1. Make sure the SDK option is checked. Click **Import**.

   ![](assets/image2015-3-26-10-3a3-3a11.png)

1. Wait for the import to finish.

   >[!TIP]
   >
   >You will need to enable pop-ups on your browser to complete the installation process.

   ![](assets/image2014-12-11-10-3a41-3a5.png)

1. Download a log file (if you want) and click **Close**.

   >[!NOTE]
   >
   >You may see a message saying "Marketo Lead Management completed with warning". This is fully expected.

   ![](assets/image2014-12-11-10-3a41-3a14.png)

1. Marketo Lead Management will now appear on the **All Solutions** page.

   ![](assets/image2015-3-26-10-3a1-3a21.png)

1. Select the Marketo solution and click **Publish all Customizations**.

   ![](assets/image2014-12-11-10-3a41-3a32.png)

Wasn't too bad right? Come on, I'll keep walking you through the rest.

>[!CAUTION]
>
>Disabling any of the Marketo SDK Messaging Processes will result in a broken install!

>[!MORELIKETHIS]
>
>[Step 2 of 3: Configure Sync User for Marketo (2013 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2013-on-premises/step-2-of-3-configure.md)
