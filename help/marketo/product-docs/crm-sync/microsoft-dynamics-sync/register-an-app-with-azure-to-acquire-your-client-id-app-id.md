---
unique-page-id: 12983390
description: Register an App with Azure to Acquire Your Client ID/App ID - Marketo Docs - Product Documentation
title: Register an App with Azure to Acquire Your Client ID/App ID
exl-id: 006cd130-a2fc-41ce-b5ee-890ef6167b34
---
# Register an App with Azure to Acquire Your Client ID/App ID {#register-an-app-with-azure-to-acquire-your-client-id-app-id}

Azure Active Directory extends your on-premises directories into the cloud, providing support for MS Dynamics 365 CRM with on-premise ADFS authentication.

## Registering a New App {#registering-a-new-app}

1. [Log in](https://login.microsoftonline.com/){target="_blank"} to the Microsoft Azure management portal using an account with admin permissions. You can also access the Microsoft Azure portal through the Office 365 Admin Center by expanding the **Admin** item in the left navigation pane and selecting **Azure AD**.

   >[!CAUTION]
   >
   >You must use an account in the same Office 365 subscription as the one you intend to register the app with.

   >[!NOTE]
   >
   >If you don’t have an Azure account, you can [sign up](https://azure.microsoft.com/en-us/free/){target="_blank"} for one. Please refer to Microsoft's documentation or reach out to your Microsoft representative for more information. Once you've created an Azure account, you can register one or more apps using the procedure outlined below.
   >
   >
   >If you have an Azure account but your Office 365 subscription with Microsoft Dynamics 365 isn't available in your Azure subscription, follow [these instructions](https://msdn.microsoft.com/office/office365/howto/setup-development-environment#bk_CreateAzureSubscription){target="_blank"} to associate the two accounts.

1. Find and click **Azure Active Directory** in the left navigation pane.

   ![](assets/two.png)

1. Under Manage, click **App registrations**.

   ![](assets/three.png)

1. Click **New registration** at the top of the page.

   ![](assets/four.png)

1. Enter a name for your app, choose your applicable account type, and enter a Redirect URL. Then click **Register** at the bottom of the page.

   ![](assets/five.png)

1. You should now see your app in the **App registrations** tab.

   ![](assets/six.png)

## Configuring App Permissions {#configuring-app-permissions}

1. Under the **App registrations** tab in your Active Directory, click the app you want to configure permissions for.

   ![](assets/seven.png)

1. Under Manage, click **API permissions**.

   ![](assets/eight.png)

1. Click the **Add a permission** button.

   ![](assets/nine.png)

1. Choose **Dynamics CRM**.

   ![](assets/ten.png)

1. Check the **Access Common Data Service as organization user****s** box, then click **Add permissions.**

   ![](assets/eleven.png)

1. Once the permissions have been successfully added, wait at least 10 seconds.

   ![](assets/twelve.png)

1. Click the **Grant admin consent** button.

   ![](assets/thirteen.png)

1. Click **Yes** to confirm.

   ![](assets/fourteen.png)

   And you're done!

   ![](assets/fifteen.png)
