---
unique-page-id: 3571827
description: Step 2 of 3 -Set up Marketo Sync User in Dynamics - Marketo Docs - Product Documentation
title: Step 2 of 3 -Set up Marketo Sync User in Dynamics
---

# Step 2 of 3: Set up Marketo Sync User in Dynamics {#step-of-set-up-marketo-sync-user-in-dynamics}

Let's get started by creating a user account.

>[!PREREQUISITES]
>
>[Step 1 of 3: Install the Marketo Solution (Online)](step-1-of-3-install.md)

## Create a new user {#create-a-new-user}

1. Log-in to Dynamics. Click the Settings icon and select **Advanced Settings**.

   ![](assets/one.png)

1. Click** Settings** and select **Security**.

   ![](assets/two.png)

1. Click **Users**.

   ![](assets/three.png)

1. Click **New.**

   ![](assets/four.png)

1. Click **Add and License Users** in the new window.

   ![](assets/five.png)

1. A new tab opens. Click **Admin** at the top of the page.

   ![](assets/six.png)

1. Another new tab opens. Click **Add a user**.

   ![](assets/seven.png)

1. Enter all of your information. When you're done, click **Add**.

   ![](assets/eight.png)

   >[!NOTE]
   >
   >This name must be a dedicated sync user and not an existing CRM user's account. It does not need to be an actual email address.

1. Enter the email to receive the new user credentials and click **Send email and close**.

   ![](assets/nine.png)

## Assign Sync User Role {#assign-sync-user-role}

Assign the Marketo Sync User role only to the Marketo sync user. You don't need to assign it to any other users.

>[!NOTE]
>
>This applies to Marketo version 4.0.0.14 and later. For earlier versions, all users must have the sync user role. To upgrade Marketo, see [Upgrade Marketo Solution for Microsoft Dynamics](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution/upgrade-the-marketo-solution-for-microsoft-dynamics.md).

1. Go back to the Enabled Users tab and refresh the users list.

   ![](assets/ten.png)

1. Hover next to the newly created Marketo Sync user, and a checkbox will appear. Click to select it.

   ![](assets/eleven.png)

1. Click **Manage Roles**.

   ![](assets/twelve.png)

1. Check **Marketo Sync User** and click **OK**.

   ![](assets/thirteen.png)

   >[!NOTE]
   >
   >Any updates made in your CRM by the Sync User will **not** be synced back to Marketo.

## Configure Marketo Solution {#configure-marketo-solution}

Almost there! All we have left is to inform Marketo Solution about the new user created.

1. Go back to the Advanced Settings section and click the ![](assets/image2015-5-13-15-3a49-3a19.png)icon next to Settings, and select **Marketo Config**.

   ![](assets/fourteen.png)

   >[!NOTE]
   >
   >If you don't see **Marketo Config** in the Settings menu, refresh the page. If that doesn't work, try to [publish the Marketo Solution](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) [](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) again or log out and back in.

1. Click **Default**.

   ![](assets/fifteen.png)

1. Click the search button on the **Marketo User** field and select the sync user you created.

   ![](assets/sixteen.png)

1. Click the ![](assets/image2015-3-13-15-3a10-3a11.png)icon in the bottom-right corner to save the changes.

   ![](assets/image2015-3-13-15-3a3-3a3.png)

1. Click the **X** in the upper-right to close the screen.

   ![](assets/seventeen.png)

1. Click the ![](assets/image2015-5-13-15-3a49-3a19-1.png)icon next to Settings, and select **Solutions**.

   ![](assets/eighteen.png)

1. Click the **Publish All Customizations** button.

   ![](assets/nineteen.png)

## Before Proceeding to Step 3 {#before-proceeding-to-step}

    * If you want to restrict the number of records you sync, [set up a custom sync filter](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) now.
    * Run the [Validate Microsoft Dynamics Sync](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) process. It verifies that your initial setups were done correctly.
    * Log into the Marketo Sync User in Microsoft Dynamics CRM.

   >[!NOTE]
   >
   >**Related Articles**
   >
   >
   >[Step 3 of 3: Connect Microsoft Dynamics with Marketo (Online)](step-3-of-3-connect.md)
