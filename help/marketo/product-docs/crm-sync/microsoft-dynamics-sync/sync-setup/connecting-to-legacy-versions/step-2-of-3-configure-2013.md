---
unique-page-id: 3571816
description: Step 2 of 3 -Configure Sync User for Marketo (2013 On-Premises) - Marketo Docs - Product Documentation
title: Step 2 of 3 -Configure Sync User for Marketo (2013 On-Premises)
exl-id: 27c4407e-0623-4ae0-8aa1-0b28c6c5c4f8
feature: Microsoft Dynamics
---
# Step 2 of 3: Configure Sync User for Marketo (2013 On-Premises) {#step-of-configure-sync-user-for-marketo-on-premises}

Great job completing the previous steps, let's keep moving through this.

>[!PREREQUISITES]
>
>[Step 1 of 3: Install the Marketo Solution in Dynamics (2013 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2013.md){target="_blank"}

## Assign Sync User Role {#assign-sync-user-role}

Assign the Marketo Sync User role only to the Marketo sync user. You don't need to assign it to any other users.

>[!NOTE]
>
>This applies to Marketo plugin version 4.0.0.14 and later. For earlier versions, all users must have the sync user role. To upgrade Marketo, see [Upgrade the Marketo Solution for Microsoft Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/update-the-marketo-solution-for-microsoft-dynamics.md){target="_blank"}.

>[!IMPORTANT]
>
>The language setting of the Sync User [should be set to English](https://learn.microsoft.com/en-us/power-platform/admin/enable-languages){target="_blank"}.

1. Under **Settings**, click **Administration**.

   ![](assets/image2014-12-11-11-3a13-3a19.png)

1. Select **Users**.

   ![](assets/image2014-12-11-11-3a13-3a29.png)

1. You will see a list of users here. Select your dedicated Marketo Sync user or contact your [Active Directory Federation Services (AFDS)](https://msdn.microsoft.com/en-us/library/bb897402.aspx){target="_blank"} administrator to create a new user that's [dedicated to Marketo](https://blogs.technet.com/b/askpfeplat/archive/2014/04/21/introduction-to-active-directory-federation-services-ad-fs-alternateloginid-feature.aspx){target="_blank"}.

   ![](assets/image2015-3-26-10-3a39-3a35.png)

1. Select the sync user. Click ![](assets/image2015-3-26-11-3a16-3a22.png) and select **[!UICONTROL Manage Roles]**.

   ![](assets/image2015-3-26-11-3a18-3a6.png)

1. Check **[!UICONTROL Marketo Sync User]** and click **[!UICONTROL OK]**.

   ![](assets/image2014-12-11-11-3a14-3a52.png)

   >[!TIP]
   >
   >If you don't see the role, go back to [step 1 of 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2013.md){target="_blank"} and import the solution.

   >[!NOTE]
   >
   >Any updates made in your CRM by the Sync User will _not_ be synced back to Marketo.

## Configure Marketo Solution {#configure-marketo-solution}

Almost done! We just have a few last pieces of configuration before moving onto the next article.

1. Under **[!UICONTROL Settings]**, click **[!UICONTROL Marketo Config]**.

   ![](assets/image2014-12-11-11-3a15-3a1.png)

   >[!NOTE]
   >
   >If "Marketo Config" is missing, try refreshing the page. If the issue persists, [publish the Marketo solution](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2013.md) again or try logging out and back in.

1. Click **[!UICONTROL Default]**.

   ![](assets/image2015-3-26-11-3a30-3a20.png)

1. Click the **[!UICONTROL Marketo User]** field and select the sync user.

   ![](assets/image2015-3-26-11-3a29-3a13.png)

1. Click ![](assets/image2015-3-13-15-3a10-3a11.png) in the bottom right corner to save the changes.

   ![](assets/image2014-12-11-11-3a15-3a32.png)

1. Click **[!UICONTROL Publish All Customizations]**.

   ![](assets/publish-all-customizations1.png)

## Before Proceeding to Step 3 {#before-proceeding-to-step}

* If you want to restrict the number of records you sync, [set up a custom sync filter](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md){target="_blank"} now.
* Run the [Validate Microsoft Dynamics Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md){target="_blank"} process. It verifies that your initial setups were done correctly.
* Log in to the Marketo Sync User in Microsoft Dynamics CRM.

Great job!

>[!MORELIKETHIS]
>
>[Step 3 of 3: Connect Marketo and Dynamics (2013 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-3-of-3-connect-2013.md){target="_blank"}
