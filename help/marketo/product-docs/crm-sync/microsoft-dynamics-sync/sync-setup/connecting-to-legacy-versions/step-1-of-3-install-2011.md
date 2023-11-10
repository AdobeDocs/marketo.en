---
unique-page-id: 3571805
description: Step 1 of 3 -Install the Marketo Solution (2011 On-Premises) - Marketo Docs - Product Documentation
title: Step 1 of 3 -Install the Marketo Solution (2011 On-Premises)
exl-id: 6e559b10-5273-4dc2-b98d-49c509cbeff7
feature: Microsoft Dynamics
---
# Step 1 of 3: Install the Marketo Solution (2011 On-Premises) {#step-of-install-the-marketo-solution-on-premises}

Before you can sync Microsoft Dynamics On-Premises and Marketo Engage, you need to first install the Marketo solution in Dynamics.

>[!NOTE]
>
>After you sync Marketo to a CRM, you cannot perform a new sync without replacing the instance.

>[!PREREQUISITES]
>
>You must have [Internet Facing Deployment](https://www.microsoft.com/en-us/download/confirmation.aspx?id=41701){target="_blank"} (IFD) with [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} 2.0, 2.1 or 3.0 (ADFS) configured. **Note**: The IFD document downloads automatically when you click the link.
>
>[Download the Marketo Lead Management Solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"} before you start.

>[!NOTE]
>
>**Dynamics Admin Permissions required**.
>
>You need CRM administrator privileges to perform this sync.

1. Log in to Dynamics and select **[!UICONTROL Settings]** in the bottom left menu.

   ![](assets/image2015-4-2-11-3a32-3a53.png)

1. Select **[!UICONTROL Solutions]** in the tree.

   ![](assets/image2015-4-2-11-3a35-3a28.png)

1. Click **[!UICONTROL Import]**.

   ![](assets/image2015-4-2-11-3a37-3a33.png)

1. Click **[!UICONTROL Browse]**. Select the Marketo Lead Management solution you [downloaded](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution.md){target="_blank"}. Click **[!UICONTROL Next]**.

   ![](assets/image2015-4-2-11-3a40-3a33.png)

1. View the Solution Information and click **[!UICONTROL View solution package details]**.

   ![](assets/image2015-11-18-11-3a12-3a8.png)

1. When you're done checking all the details, click **[!UICONTROL Close]**.

   ![](assets/image2015-10-9-14-3a57-3a3.png)

1. Back on the Solution Information page, click **[!UICONTROL Next]**.

   ![](assets/image2015-4-2-11-3a41-3a48.png)

1. Make sure the SDK message option checkbox is checked. Click **[!UICONTROL Next]**.

   ![](assets/image2015-4-2-11-3a42-3a37.png)

   >[!TIP]
   >
   >You will need to enable pop-ups on your browser to complete the installation process.

1. Now wait for the import to finish. Get up and do some stretches.

   ![](assets/image2015-4-2-11-3a43-3a51.png)

1. Click **[!UICONTROL Close]**.

   >[!NOTE]
   >
   >You may see a message saying "Marketo Lead Management completed with warning". This is fully expected.

   ![](assets/image2015-4-2-11-3a44-3a44.png)

1. Marketo Lead Management will now appear on the **All Solutions** page.

   ![](assets/image2015-4-2-11-3a46-3a55.png)

1. Select Marketo Lead Management and click **[!UICONTROL Publish All Customizations]**.

   ![](assets/image2015-4-2-11-3a48-3a21.png)

>[!CAUTION]
>
>Disabling any of the Marketo SDK Messaging Processes will result in a broken install!

>[!MORELIKETHIS]
>
>[Step 2 of 3: Set Up Marketo Sync User in Dynamics (2011 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2011.md){target="_blank"}
