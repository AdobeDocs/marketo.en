---
unique-page-id: 7504744
description: Install Marketo for Dynamics 2015 On-Prem and 2016 365 On-Prem Step 3 of 3 - Marketo Docs - Product Documentation
title: Install Marketo for Dynamics 2015 On-Prem and 2016 365 On-Prem Step 3 of 3
---

# Install Marketo for Dynamics 2015 On-Prem and 2016 365 On-Prem Step 3 of 3 {#install-marketo-for-dynamics-on-prem-and-on-prem-step-of}

>[!PREREQUISITES]
>
>* [Install Marketo for Dynamics 2015 On-Prem and 2016 365 On-Prem Step 1 of 3](step-1-of-3-install.md)
>* [Install Marketo for Dynamics 2015 On-Prem and 2016 365 On-Prem Step 2 of 3](step-2-of-3-set-up.md)
>

>[!NOTE]
>
>**Admin Permissions Required**

## Enter Dynamics Sync User information {#enter-dynamics-sync-user-information}

1. Log into Marketo and click **Admin**.

   ![](assets/login-admin.png)

1. Click **CRM**.

   ![](assets/image2015-3-16-9-47-34.png)

1. Select **Microsoft**.

   ![](assets/image2015-3-16-9-50-6.png)

1. Click **Edit** in **Step 1: Enter Credentials**.

   ![](assets/image2015-3-16-9-48-43.png)

   >[!CAUTION]
   >
   >Please make sure your credentials are correct as we are unable to revert the subsequent schema changes after submission. If incorrect credentials are saved, you’ll have to obtain a new Marketo subscription.

1. Enter the **Username**, **Password** a Microsoft Dynamics **URL**, and an optional **Client Id**. Click **Save** when done.

   ![](assets/client-id.png)

   >[!NOTE]
   >
   >The Username in Marketo must match the User Name for the sync user in CRM. The format can be [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#8cf9ffe9fecce8e3e1ede5e2a2efe3e1) or DOMAIN\user.

   >[!TIP]
   >
   >Don't know the URL? We will show you how to find your [Dynamics Organization Service URL](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md) here.

## Select Fields to Sync {#select-fields-to-sync}

1. Click **Edit** in **Step 2: Select Fields to Sync**.

   ![](assets/image2015-3-16-9-51-28.png)

1. Select the fields that you want to sync to Marketo, so they will be pre-selected. Click **Save**.

   ![](assets/image2016-8-25-15-3a14-3a28.png)

## Sync Fields for a Custom Filter {#sync-fields-for-a-custom-filter}

If you've created a custom filter, be sure to go in and select the new fields to be synced with Marketo.

1. Go to Admin and select **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Click **Edit** on Field Sync Details.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Scroll down to the field and check it. The actual name must be new_synctomkto but the Display Name can be anything. Click **Save**.

   ![](assets/image2016-8-25-15-3a15-3a35.png)

## Enable Sync {#enable-sync}

1. Click **Edit** in **Step 3: Enable Sync**.

   ![](assets/image2015-3-16-9-52-2.png)

   >[!CAUTION]
   >
   >Marketo will not automatically de-dupe against a Microsoft Dynamics sync, or when you manually enter people.

1. Read everything in the pop-up, enter your email, and click **Start Sync**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. The first sync may take a few hours. After it's done, you'll receive an email notification.

   ![](assets/image2015-3-16-9-59-51.png)

Excellent work!
