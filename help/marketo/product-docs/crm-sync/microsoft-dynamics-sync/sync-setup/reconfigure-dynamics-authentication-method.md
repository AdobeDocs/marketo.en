---
description: Reconfigure Dynamics Authentication Method - Marketo Docs - Product Documentation
title: Reconfigure Dynamics Authentication Method
exl-id: 2bd6a992-3dfd-4e91-bec5-9fb3f7bbb840
---
# Reconfigure Dynamics Authentication Method {#reconfigure-dynamics-authentication-method}

Follow the steps below to update your Dynamics Authentication Method.

>[!PREREQUISITES]
>
>Set up the application in Microsoft Dynamics and active directory (Azure AD/ADFS) using the desired authentication method from either of the following articles:
>* [Step 2 of 3: Set up Marketo Solution with Server to Server Connection](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md)
>* [Step 2 of 4: Set up the Marketo Solution with Resource Owner Password Control Connection](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md)

1. In Marketo click **Admin**.

   ![](assets/reconfigure-dynamics-authentication-method-1.png)

1. Click **Microsoft Dynamics**, then **Disable Sync**.

   ![](assets/reconfigure-dynamics-authentication-method-2.png)

   >[!NOTE]
   >
   >You must disable the global sync temporarily in order to update the Authentication Method.

1. Click the **Reconfigure New Auth Method** tab.

   ![](assets/reconfigure-dynamics-authentication-method-3.png)

1. Select the desired new Authentication Method (in this example we're choosing Web API).

   ![](assets/reconfigure-dynamics-authentication-method-4.png)

1. Enter the credentials required for the new Authentication Method and click **Validate**.

   ![](assets/reconfigure-dynamics-authentication-method-5.png)

   >[!NOTE]
   >
   >* The specific fields will vary by the chosen authentication method and the form will be automatically updated depending on previous authentication method.
   >* If you’ve synced before, the data in the above form may be pre-populated. Please re-enter all credentials to ensure the correct values.

1. If everything is fine, the Validate Sync will generate all green checkmarks ![](assets/green-check.png). Review the message and click **Switch** to update the Authentication Method.

   ![](assets/reconfigure-dynamics-authentication-method-6.png)

   >[!NOTE]
   >
   >If you see a ![](assets/red-x.png), that step has an issue. See [Fix Dynamics Validation Sync Issues](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync/fix-dynamics-validation-sync-issues.md) to identify and fix the problem(s). Then rerun the sync validation steps until the result looks like the image above.

1. Click **Confirm** to proceed.

   ![](assets/reconfigure-dynamics-authentication-method-7.png)

1. Click **Confirm** again.

1. Click **OK**.

   >[!IMPORTANT]
   >
   >Remember to re-enable the sync!
