---
description: Set up the ON24 Integration with Marketo - Marketo Docs - Product Documentation
title: Set up the ON24 Integration with Marketo
exl-id: 395ffa37-b87d-4eb4-bf9f-72aa96dc819c
---
# Set up the ON24 Integration with Marketo{#set-up-the-on24-integration-with-marketo}

Here's how to set up your ON24 event integration.

## Create an API Only Role {#create-an-api-only-role}

1. From My Marketo, click **[!UICONTROL Admin]**.

   ![](assets/set-up-the-on24-integration-with-marketo-1.png)

1. Under [!UICONTROL Security], click **[!UICONTROL Users & Roles]**.

   ![](assets/set-up-the-on24-integration-with-marketo-2.png)

1. Click the **[!UICONTROL Roles]** tab and then **[!UICONTROL New Role]**.

   ![](assets/set-up-the-on24-integration-with-marketo-3.png)

1. Enter a [!UICONTROL Role Name]. Open the **[!UICONTROL Access API]** menu and select "[!UICONTROL Read-Write Custom Object]" and "[!UICONTROL Read-Write Person]." Click **[!UICONTROL Create]**.

   ![](assets/set-up-the-on24-integration-with-marketo-4.png)

## Create a New User {#create-a-new-user}

1. Still in [!UICONTROL Users & Roles], click the **[!UICONTROL Users]** tab and click **[!UICONTROL Invite New User]**.

   ![](assets/set-up-the-on24-integration-with-marketo-5.png)

1. Enter the new user's information and click **[!UICONTROL Next]**.

   ![](assets/set-up-the-on24-integration-with-marketo-6.png)

1. Select the [!UICONTROL ON24 API Only Role (all workspaces)] you just created. Select the **[!UICONTROL API Only]** checkbox. Click **[!UICONTROL Next]**.

   ![](assets/set-up-the-on24-integration-with-marketo-7.png)

1. Click **[!UICONTROL Send]**.

   ![](assets/set-up-the-on24-integration-with-marketo-8.png)

>[!NOTE]
>
>An invitation isn't required for API Only users.

## Set up ON24 Connection {#set-up-on24-connection}

1. Still in the [!UICONTROL Admin] section, click **[!UICONTROL LaunchPoint]**.

   ![](assets/set-up-the-on24-integration-with-marketo-9.png)

1. Click **[!UICONTROL New]** then **[!UICONTROL New Service]**.

   ![](assets/set-up-the-on24-integration-with-marketo-10.png)

1. Choose a [!UICONTROL display name]. Click the **[!UICONTROL Service]** drop-down and select **[!UICONTROL Custom]**. Enter a [!UICONTROL description]. Click the [!UICONTROL API Only User] drop-down and select the user you created [in the steps above](#create-a-new-user). Click **[!UICONTROL Create]**.

   ![](assets/set-up-the-on24-integration-with-marketo-11.png)

1. Find the custom [!DNL LaunchPoint] service you just created and click [!UICONTROL View Details].

   ![](assets/set-up-the-on24-integration-with-marketo-12.png)

1. Highlight, right-click, copy, and save the [!UICONTROL Client ID] (you'll need it later). Repeat for [!UICONTROL Client Secret].

   ![](assets/set-up-the-on24-integration-with-marketo-13.png)

1. In the tree on the left, click **[!UICONTROL Web Services]**.

   ![](assets/set-up-the-on24-integration-with-marketo-14.png)

1. Under "[!UICONTROL REST API]," highlight, right-click, copy, and save the first part of the [!UICONTROL Identity] (up until the 'm' in .com).

   ![](assets/set-up-the-on24-integration-with-marketo-15.png)

1. With your saved [!UICONTROL Client ID], [!UICONTROL Client Secret], and [!UICONTROL Identity], navigate to your ON24 account. The rest of the steps are performed there, and are [outlined here](https://on24support.force.com/Support/s/article/Connect-Marketo-ON24-Connect-Data-Integration#Step6){target="_blank"}.
