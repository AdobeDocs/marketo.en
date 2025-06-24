---
unique-page-id: 3571813
description: Step 1 of 3 -Install the Marketo Solution in Dynamics (2013 On-Premises) - Marketo Docs - Product Documentation
title: Step 1 of 3 -Install the Marketo Solution in Dynamics (2013 On-Premises)
exl-id: 89f90bca-b459-447f-bbdd-363f232a1059
feature: Microsoft Dynamics
---
# Step 1 of 3: Install the Marketo Solution in Dynamics (2013 On-Premises) {#step-of-install-the-marketo-solution-in-dynamics-on-premises}

Before you can sync Microsoft Dynamics On-Premises and Marketo Engage, you need to first install the Marketo solution in Dynamics.

>[!NOTE]
>
>After you sync Marketo to a CRM, you cannot perform a new sync without replacing the instance.

>[!PREREQUISITES]
>
>You must have [Internet Facing Deployment](https://learn.microsoft.com/en-us/dynamics365/customerengagement/on-premises/deploy/configure-an-internet-facing-deployment){target="_blank"} (IFD) with [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} 2.0, 2.1 or 3.0 (ADFS) configured. Note: The IFD document downloads automatically when you click the link.
>
>[Download the Marketo Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"} before you start.

>[!NOTE]
>
>**Dynamics Admin Permissions required**.
>
>You need CRM administrator privileges to perform this sync.

1. Log into Dynamics. Click the **[!UICONTROL Microsoft Dynamics CRM]** drop-down menu and select **[!UICONTROL Settings]**.

   ![](assets/image2014-12-11-10-3a39-3a41.png)

1. Under **[!UICONTROL Settings]**, select **[!UICONTROL Solutions]**.

   ![](assets/image2014-12-11-10-3a39-3a51.png)

1. Click **[!UICONTROL Import]**.

   ![](assets/image2015-3-26-9-3a52-3a10.png)

1. Click **[!UICONTROL Browse]** and select the [downloaded solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}. Click **[!UICONTROL Next]**.

   ![](assets/image2015-3-26-9-3a54-3a1.png)

1. View the Solution Information and click **[!UICONTROL View solution package details]**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. When you're done checking all the details, click **[!UICONTROL Close]**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Back on the Solution Information page, click **[!UICONTROL Next]**.

   ![](assets/image2015-3-26-9-3a55-3a17.png)

1. Make sure the SDK option is checked. Click **[!UICONTROL Import]**.

   ![](assets/image2015-3-26-10-3a3-3a11.png)

1. Wait for the import to finish.

   >[!TIP]
   >
   >You will need to enable pop-ups on your browser to complete the installation process.

   ![](assets/image2014-12-11-10-3a41-3a5.png)

1. Download a log file (if you want) and click **[!UICONTROL Close]**.

   >[!NOTE]
   >
   >You may see a message saying "Marketo Lead Management completed with warning". This is fully expected.

   ![](assets/image2014-12-11-10-3a41-3a14.png)

1. Marketo Lead Management will now appear on the **[!UICONTROL All Solutions]** page.

   ![](assets/image2015-3-26-10-3a1-3a21.png)

1. Select the Marketo solution and click **[!UICONTROL Publish all Customizations]**.

   ![](assets/image2014-12-11-10-3a41-3a32.png)

>[!CAUTION]
>
>Disabling any of the Marketo SDK Messaging Processes will result in a broken install!

>[!MORELIKETHIS]
>
>[Step 2 of 3: Configure Sync User for Marketo (2013 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-configure-2013.md){target="_blank"}
