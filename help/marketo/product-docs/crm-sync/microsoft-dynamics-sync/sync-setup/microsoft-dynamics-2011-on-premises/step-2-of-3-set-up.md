---
unique-page-id: 3571807
description: Step 2 of 3 -Set Up Marketo Sync User in Dynamics (2011 On-Premises) - Marketo Docs - Product Documentation
title: Step 2 of 3 -Set Up Marketo Sync User in Dynamics (2011 On-Premises)
---

# Step 2 of 3: Set Up Marketo Sync User in Dynamics (2011 On-Premises) {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises}

Great job completing the previous steps, let's keep moving through this.

>[!NOTE]
>
>**Prerequisites**
>
>* [Step 1 of 3: Install the Marketo Solution (2011 On-Premises)](step-1-of-3-install-the-marketo-solution-2011-on-premises.md)
>

## Assign Sync User Role {#assign-sync-user-role}

Assign the Marketo Sync User role only to the Marketo sync user. You don't need to assign it to any other users.

>[!NOTE]
>
>This applies to Marketo plugin version 4.0.0.14 and later. For earlier versions, all users must have the sync user role. To upgrade Marketo, see [Upgrade the Marketo Solution for Microsoft Dynamics](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution/upgrade-the-marketo-solution-for-microsoft-dynamics.md).

1. In the bottom left menu, select **Settings**.

   ![](assets/image2015-4-2-14-3a2-3a40.png)

1. In the tree, select **Administration**.

   ![](assets/image2015-4-2-14-3a3-3a30.png)

1. Select **Users**.

   ![](assets/image2015-4-2-14-3a4-3a37.png)

1. You will see a list of users here. Select your dedicated Marketo sync user or contact your [Active Directory Federation Services (AFDS)](https://msdn.microsoft.com/en-us/library/bb897402.aspx) administrator to create a new user that's dedicated to Marketo. Click **Manage Roles**.

   ![](assets/image2015-4-2-14-3a11-3a7.png)

1. Check **Marketo Sync User** and click **OK**.

   ![](assets/image2015-4-2-14-3a15-3a0.png)

   >[!TIP]
   >
   >If you don't see the role, go back to [step 1 of 3](step-1-of-3-install-the-marketo-solution-2011-on-premises.md) and import the solution.

   >[!NOTE]
   >
   >Any updates made in your CRM by the Sync User will **not** be synced back to Marketo.

## Configure Marketo Solution {#configure-marketo-solution}

Almost done! We just have a few last pieces of configuration before moving onto the next article.

1. Select **Settings**. Then select **Marketo Config **in the tree.

   ![](assets/image2015-4-2-14-3a20-3a51.png)

   >[!NOTE]
   >
   >If Marketo Config is missing, try refreshing the page. If the issue persists, [publish the Marketo solution again](step-1-of-3-install-the-marketo-solution-2011-on-premises.md) or log out and back in.

1. Click **Default**.

   ![](assets/image2015-4-2-14-3a27-3a30.png)

1. Click on ![](assets/image2015-4-2-14-3a29-3a1.png)

   ![](assets/image2015-4-2-14-3a28-3a40.png)

1. In the popup, select the sync user. Then click **OK**.

   ![](assets/image2015-4-2-14-3a32-3a43.png)

1. Click **Save** to save the changes.

   ![](assets/image2015-4-2-14-3a34-3a15.png)

1. Click **Publish All Customizations**.

   ![](assets/publish-all-customizations1.png)

## Before Proceeding to Step 3 {#before-proceeding-to-step}

    * If you want to restrict the number of records you sync, [set up a custom sync filter](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) now.
    * Run the [Validate Microsoft Dynamics Sync](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) process. It verifies that your initial setups were done correctly.
    * Log into the Marketo Sync User in Microsoft Dynamics CRM.

   Great job!

>[!NOTE]
>
>**Related Articles**
>
>[Step 3 of 3: Connect Microsoft Dynamics with Marketo (2011 On-Premises)](step-3-of-3-connect.md)

