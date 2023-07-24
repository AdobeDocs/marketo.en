---
description: Set up the ON24 Integration with Marketo - Marketo Docs - Product Documentation
title: Set up the ON24 Integration with Marketo
exl-id: 395ffa37-b87d-4eb4-bf9f-72aa96dc819c
feature: Events
---
# Set up the ON24 Integration with Marketo{#set-up-the-on24-integration-with-marketo}

Here's how to set up your ON24 event integration.

## Create an API Only Role {#create-an-api-only-role}

1. From My Marketo, click **Admin**.

   ![](assets/set-up-the-on24-integration-with-marketo-1.png)

1. Under Security, click **Users & Roles**.

   ![](assets/set-up-the-on24-integration-with-marketo-2.png)

1. Click the **Roles** tab and then **New Role**.

   ![](assets/set-up-the-on24-integration-with-marketo-3.png)

1. Enter a Role Name. Open the **Access API** menu and select "Read-Write Custom Object" and "Read-Write Person." Click **Create**.

   ![](assets/set-up-the-on24-integration-with-marketo-4.png)

## Create a New User {#create-a-new-user}

1. Still in Users & Roles, click the **Users** tab and click **Invite New User**.

   ![](assets/set-up-the-on24-integration-with-marketo-5.png)

1. Enter the new user's information and click **Next**.

   ![](assets/set-up-the-on24-integration-with-marketo-6.png)

1. Select the ON24 API Only Role you just created. Select the **API Only** checkbox. Click **Next**.

   ![](assets/set-up-the-on24-integration-with-marketo-7.png)

1. Click **Send**.

   ![](assets/set-up-the-on24-integration-with-marketo-8.png)

>[!NOTE]
>
>An invitation isn't required for API Only users.

## Set up ON24 Connection {#set-up-on24-connection}

1. Still in the Admin section, click **LaunchPoint**.

   ![](assets/set-up-the-on24-integration-with-marketo-9.png)

1. Click **New** then **New Service**.

   ![](assets/set-up-the-on24-integration-with-marketo-10.png)

1. Choose a display name. Click the **Service** drop-down and select **Custom**. Enter a description. Click the API Only User drop-down and select the user you created [in the steps above](#create-a-new-user). Click **Create**.

   ![](assets/set-up-the-on24-integration-with-marketo-11.png)

1. Find the custom LaunchPoint service you just created and click View Details.

   ![](assets/set-up-the-on24-integration-with-marketo-12.png)

1. Highlight, right-click, copy, and save the Client ID (you'll need it later). Repeat for Client Secret.

   ![](assets/set-up-the-on24-integration-with-marketo-13.png)

1. In the tree on the left, click Web Services.

   ![](assets/set-up-the-on24-integration-with-marketo-14.png)

1. Under "REST API," highlight, right-click, copy, and save the first part of the Identity (up until the 'm' in .com).

   ![](assets/set-up-the-on24-integration-with-marketo-15.png)

1. With your saved Client ID, Client Secret, and Identity, navigate to your ON24 account. The rest of the steps are performed there, and are [outlined here](https://on24support.force.com/Support/s/article/Connect-Marketo-ON24-Connect-Data-Integration#Step6){target="_blank"}.
