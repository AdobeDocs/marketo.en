---
unique-page-id: 3571819
description: Step 3 of 3: Connect Marketo and Dynamics (2013 On-Premises) - Marketo Docs - Product Documentation
title: Step 3 of 3: Connect Marketo and Dynamics (2013 On-Premises)
---

# Step 3 of 3: Connect Marketo and Dynamics (2013 On-Premises) {#step-of-connect-marketo-and-dynamics-on-premises}

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Alright! We installed the solution and configured the sync user. Next, we need to connect Marketo and Dynamics.

>[!NOTE]
>
>**Prerequisites**
>
>* [Step 1 of 3: Install the Marketo Solution in Dynamics (2013 On-Premises)](step-1-of-3-install-the-marketo-solution-in-dynamics-2013-on-premises.md)
>* [Step 2 of 3: Configure Sync User for Marketo (2013 On-Premises)](step-2-of-3-configure-sync-user-for-marketo-2013-on-premises.md)
>

>[!NOTE]
>
>**Admin Permissions Required**

## Enter Dynamics Sync User Information {#enter-dynamics-sync-user-information}

1. Log into Marketo and click **Admin**.

   ![](assets/login-admin.png)

1. Click on **CRM**.

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. Select **Microsoft**.

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. Click **EDIT** in **Step 1: Enter Credentials**.

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >Please make sure your credentials are correct as we are unable to revert the subsequent schema changes after submission. If incorrect credentials are saved, you’ll have to obtain a new Marketo subscription.

1. Enter the **Username**, **Password** and Microsoft Dynamics **URL** then click **SAVE**.

   ![](assets/image2015-3-26-11-3a47-3a59.png)

   >[!NOTE]
   >
   >The Username in Marketo must match the User Name for the sync user in CRM. The format can be [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#631610061123070c0e020a0d4d000c0e) or DOMAIN\user.

   >[!TIP]
   >
   >Don't know the URL? We'll show you how to find the [Dynamics Organization Service URL](../../../../../product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md) here.

## Select Fields to Sync {#select-fields-to-sync}

Now we need to select the fields we want to sync over.

1. Click **EDIT **in **Step 2: Select Fields to Sync**.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Select the fields that you want to sync to Marketo, so they will be pre-selected. Click **Save**.

   ![](assets/image2016-8-25-15-3a10-3a17.png)

## Sync Fields for a Custom Filter {#sync-fields-for-a-custom-filter}

If you've created a custom filter, be sure to go in and select the new fields to be synced with Marketo.

1. Go to Admin and select **Microsoft Dynamics**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Click **Edit** on Field Sync Details.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Scroll down to the field and check it. The actual name must be new_synctomkto but the Display Name can be anything. Click **Save**.

   ![](assets/image2016-8-25-15-3a11-3a4.png)

## Enable Sync {#enable-sync}

1. Click **EDIT **in **Step 3: Enable Sync**.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo will not automatically de-dupe against a Microsoft Dynamics sync, or when you manually enter people or leads.

1. Read everything in the pop-up, enter your email, and click **START SYNC**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. The first sync may take a few hours. After it's done, you'll receive an email notification.

   ![](assets/image2014-12-11-11-3a55-3a15.png)

Excellent work! You have just unleashed the power of the bi-directional sync between Marketo and Microsoft Dynamics. If you have purchased Marketo Sales Insight, there is more fun to be had:

>[!NOTE]
>
>**Related Articles**
>
>* [Install and Configure Marketo Sales Insight in Microsoft Dynamics 2013](../../../../../product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2013.md)
>

