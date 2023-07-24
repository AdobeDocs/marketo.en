---
unique-page-id: 3571830
description: Step 3 of 3 - Connect the Marketo Solution with Server to Server Connection - Marketo Docs - Product Documentation
title: Step 3 of 3 - Connect the Marketo Solution with Server to Server Connection
exl-id: e3ede749-f787-45d3-adb4-f71ef1221208
feature: Microsoft Dynamics
---
# Step 3 of 3: Connect the Marketo Solution with Server to Server Connection {#step-3-of-3-connect-microsoft-dynamics-with-marketo-solution-s2s}

This is the last step of the sync. We're almost there!

>[!PREREQUISITES]
>
>* [Step 1 of 3: Install the Marketo Solution with Server to Server Connection](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-1-of-3-install.md)
>* [Step 2 of 3: Set up the Marketo Solution with Server to Server Connection](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-365-with-s2s-connection/step-2-of-3-set-up.md)

>[!NOTE]
>
>**Admin Permissions Required**

>[!IMPORTANT]
>
>If you’re upgrading from Basic Authentication to OAuth, you’ll need to contact [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support) for help with updating the additional parameters. Enabling this feature will temporarily stop the sync until new credentials are entered and the sync is re-enabled. The feature can be disabled (until April 2022) should you want to revert to the old Authentication mode.

>[!NOTE]
>
>Before you enter new credentials, you can [validate them here](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md).

## Enter Dynamics Sync User information {#enter-dynamics-sync-user-information}

1. Log in to Marketo and click **Admin**.

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

1. Enter the Dynamics Sync User information and click **Save** when done.

   ![](assets/step-3-of-3-connect-s2s-5.png)

   >[!NOTE]
   >
   >The username in Marketo must match the [email address](https://docs.microsoft.com/en-us/power-platform/admin/manage-application-users#view-or-edit-the-details-of-an-application-user) of the Application User in the CRM. The format can be `user@domain.com` or DOMAIN\user.

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
