---
unique-page-id: 3571807
description: "Step 2 of 3 -Set up Marketo Sync User in [!DNL Dynamics] (2011 On-Premises) - Marketo Docs - Product Documentation"
title: Step 2 of 3 -Set up Marketo Sync User in [!DNL Dynamics] (2011 On-Premises)
exl-id: 807c8902-24a6-48b6-a5c9-96a72764fdef
feature: Microsoft Dynamics
---
# Step 2 of 3: Set up Marketo Sync User in [!DNL Dynamics] (2011 On-Premises) {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises}

Great job completing the previous steps, let's keep moving through this.

>[!PREREQUISITES]
>
>[Step 1 of 3: Install the Marketo Solution (2011 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md){target="_blank"}

## Assign Sync User Role {#assign-sync-user-role}

Assign the Marketo Sync User role only to the Marketo sync user. You don't need to assign it to any other users.

>[!NOTE]
>
>This applies to Marketo plugin version 4.0.0.14 and later. For earlier versions, all users must have the sync user role. To upgrade Marketo, see [Upgrade the Marketo Solution for [!DNL Microsoft Dynamics]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md).

>[!IMPORTANT]
>
>The language setting of the Sync User [should be set to English](https://learn.microsoft.com/en-us/power-platform/admin/enable-languages){target="_blank"}.

1. In the bottom left menu, select **[!UICONTROL Settings]**.

   ![](assets/image2015-4-2-14-3a2-3a40.png)

1. In the tree, select **[!UICONTROL Administration]**.

   ![](assets/image2015-4-2-14-3a3-3a30.png)

1. Select **[!UICONTROL Users]**.

   ![](assets/image2015-4-2-14-3a4-3a37.png)

1. You will see a list of users here. Select your dedicated Marketo sync user or contact your [Active Directory Federation Services (AFDS)](https://msdn.microsoft.com/en-us/library/bb897402.aspx) administrator to create a new user that's dedicated to Marketo. Click **[!UICONTROL Manage Roles]**.

   ![](assets/image2015-4-2-14-3a11-3a7.png)

1. Check **[!UICONTROL Marketo Sync User]** and click **[!UICONTROL OK]**.

   ![](assets/image2015-4-2-14-3a15-3a0.png)

   >[!TIP]
   >
   >If you don't see the role, go back to [step 1 of 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md){target="_blank"} and import the solution.

   >[!NOTE]
   >
   >Any updates made in your CRM by the Sync User will _not_ be synced back to Marketo.

## Configure Marketo Solution {#configure-marketo-solution}

Almost done! We just have a few last pieces of configuration before moving onto the next article.

1. Select **[!UICONTROL Settings]**. Then select **[!UICONTROL Marketo Config]** in the tree.

   ![](assets/image2015-4-2-14-3a20-3a51.png)

   >[!NOTE]
   >
   >If [!UICONTROL Marketo Config] is missing, try refreshing the page. If the issue persists, [publish the Marketo solution again](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md) or log out and back in.

1. Click **[!UICONTROL Default]**.

   ![](assets/image2015-4-2-14-3a27-3a30.png)

1. Click on ![](assets/image2015-4-2-14-3a29-3a1.png)

   ![](assets/image2015-4-2-14-3a28-3a40.png)

1. In the pop-up, select the sync user. Then click **[!UICONTROL OK]**.

   ![](assets/image2015-4-2-14-3a32-3a43.png)

1. Click **[!UICONTROL Save]** to save the changes.

   ![](assets/image2015-4-2-14-3a34-3a15.png)

1. Click **[!UICONTROL Publish All Customizations]**.

   ![](assets/publish-all-customizations1.png)

## Before Proceeding to Step 3 {#before-proceeding-to-step}

    * If you want to restrict the number of records you sync, [set up a custom sync filter](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) now.
    * Run the [Validate [!DNL Microsoft Dynamics] Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) process. It verifies that your initial setups were done correctly.
    * Log into the Marketo Sync User in [!DNL Microsoft Dynamics] CRM.

   Great job!

>[!MORELIKETHIS]
>
>[Step 3 of 3: Connect [!DNL Microsoft Dynamics] with Marketo (2011 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-3-of-3-connect-2011.md)
