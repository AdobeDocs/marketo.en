---
description: Step 4 of 4 - Connect the Marketo Solution with Resource Owner Password Control Connection - Marketo Docs - Product Documentation
title: Step 4 of 4 - Connect the Marketo Solution with Resource Owner Password Control Connection
exl-id: 71a52a3e-f31e-45ee-8196-d536528e42ca
feature: Microsoft Dynamics
---
# Step 4 of 4: Connect the Marketo Solution with Resource Owner Password Control Connection {#step-4-of-4-connect-the-marketo-solution-ropc}

This is the last step of the sync. You're almost there!

>[!PREREQUISITES]
>
>* [Step 1 of 4: Install the Marketo Solution with Resource Owner Password Control Connection](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-1-of-4-install.md)
>* [Step 2 of 4: Set up the Marketo Solution with Resource Owner Password Control Connection](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-2-of-4-set-up.md)
>* [Step 3 of 4: Set up Client App on MS Dynamics](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-ropc-connection/step-3-of-4-set-up.md)

>[!NOTE]
>
>**Admin Permissions Required**

>[!NOTE]
>
>If you’re upgrading from Basic Authentication to OAuth, you can use [this article](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md) to reconfigure your authentication.

## Enter Dynamics Sync User information {#enter-dynamics-sync-user-information}

1. Log into Marketo and click **Admin**.

   ![](assets/login-admin.png)

1. Click on **CRM**.

   ![](assets/image2015-3-16-9-3a47-3a34.png)

1. Select **Microsoft**.

   ![](assets/image2015-3-16-9-3a50-3a6.png)

1. Click **Edit** in **Step 1: Enter Credentials**.

   ![](assets/image2015-3-16-9-3a48-3a43.png)

   >[!CAUTION]
   >
   >Please make sure your org URL is correct as we are unable to revert the subsequent schema changes after submission. If an incorrect Org URL is used, you’ll have to obtain a new Marketo subscription. If you don't know the URL, [learn how to find it here](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md).

   >[!NOTE]
   >
   >Before you enter new credentials, you can [validate them here](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md).

1. Enter the **Username**, **Password**, Microsoft Dynamics **URL**, **Client ID**, and **Client Secret**. Click **Save** when done.

   ![](assets/step-4-of-4-connect-ropc-5.png)

   >[!NOTE]
   >
   >The Username in Marketo must match the User Name for the sync user in CRM. The format can be `user@domain.com` or DOMAIN\user.

## Select Fields to Sync {#select-fields-to-sync}

1. Click **Edit** in **Step 2: Select Fields to Sync**.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Select the fields that you want to sync to Marketo, so they will be pre-selected. Click **Save**.

   ![](assets/image2016-8-25-15-3a6-3a11.png)

>[!NOTE]
>
>Marketo stores a reference to the fields to sync. If you delete a field in Dynamics, we recommended doing so with the [sync disabled](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). Then refresh the schema in Marketo by editing and saving the [Select Fields to Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md).

## Sync Fields for a Custom Filter {#sync-fields-for-a-custom-filter}

If you've created a custom filter, be sure to go in and select the new fields to be synced with Marketo.

1. Go to Admin and select **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Click **Edit** on Field Sync Details.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Scroll down to the field and check it. The actual name must be new_synctomkto but the Display Name can be anything. Click **Save**.

   ![](assets/image2016-8-25-15-3a7-3a35.png)

## Enable Sync {#enable-sync}

1. Click **Edit** in **Step 3: Enable Sync**.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo will not automatically de-dupe against a Microsoft Dynamics sync, or when you manually enter people or leads.

1. Read everything in the pop-up, enter your email address, and click **Start Sync**.

   ![](assets/image2015-3-16-9-3a55-3a10.png)

1. The first sync may take a few hours. Once it's done, you'll receive an email notification.

   ![](assets/image2015-3-16-9-3a59-3a51.png)

Excellent work!

>[!MORELIKETHIS]
>
>[Reconfigure Dynamics Authentication Method](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/reconfigure-dynamics-authentication-method.md)