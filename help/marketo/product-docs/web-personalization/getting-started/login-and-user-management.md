---
unique-page-id: 7513771
description: Login and User Management - Marketo Docs - Product Documentation
title: Login and User Management
exl-id: 3cf5a50a-1926-4fb6-a1fe-39ba5eb2560f
---
# Login and User Management {#login-and-user-management}

## Create a Web Personalization User Role {#create-a-web-personalization-user-role}

1. Go to the **[!UICONTROL Admin]** section, then click **[!UICONTROL Users & Roles]**.

   ![](assets/image2015-4-28-19-3a50-3a49.png)

1. Click **[!UICONTROL Roles]**.

   ![](assets/image2015-4-28-19-3a57-3a58.png)

   >[!NOTE]
   >
   >If the Web Personalization (WP) user role already exists, make sure it's configured as shown in Step 4.

1. Click **[!UICONTROL New Role]**.

   ![](assets/three-1.png)

1. Enter a [!UICONTROL Role Name] and select Permissions. Click **[!UICONTROL Create]** (this role must [apply to all workspaces](/help/marketo/product-docs/administration/users-and-roles/managing-marketo-users.md)).

   ![](assets/four.png)

   >[!TIP]
   >
   >To give users permission to access everything in Targeting and Personalization, be sure to select _all_ the checkboxes.

## [!UICONTRO Web Personalization] and Predictive Content User Permissions {#web-personalization-and-predictive-content-user-permissions}

**[!UICONTROL Targeting and Personalization]**: User has view only permissions, if this permission is only selected.

**[!UICONTROL Admin Web Personalization + Predictive]**: User has access to only the Account Settings and Content Setting for the Web Personalization and Predictive Content app. Users can view pages in the app but have no create, edit, delete, launch permissions.

**[!UICONTROL Predictive Content Editor]**: User has editor access to the Predictive Content app. The permission allows to create, edit, delete content pieces. It does not allow to enable content for Predictive use on web or email.

**[!UICONTROL Predictive Content Launcher]**: User has access to all Predictive Content features, except Account and Content Settings. The permission allows to create, edit and delete and enable content pieces.

**[!UICONTROL Web Campaign Editor]**: User has editor access to all Web Personalization feature to create, edit and delete but not launch Web campaigns.

**[!UICONTROL Web Campaign Launcher]**: User has access to all Web Personalization app features, except Account and Content Settings. The permission allows to create, edit, delete and launch Web campaigns.

## Assign WP Role to User {#assign-wp-role-to-user}

1. Go to **[!UICONTROL Users]**.

   ![](assets/image2015-4-29-11-3a31-3a3.png)

1. Select the user to grant WP access to and click **[!UICONTROL Edit User]**.

   ![](assets/image2015-4-29-11-3a38-3a46.png)

1. Select the WP user role for all workspaces.

   ![](assets/seven.png)

1. Newly enabled users will see the **[!UICONTROL Web Personalization]** tile in My Marketo the next time they log-in.

   ![](assets/eight.png)
