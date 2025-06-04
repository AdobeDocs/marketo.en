---
unique-page-id: 3571809
description: Step 3 of 3 -Connect Microsoft Dynamics with Marketo (2011 On-Premises) - Marketo Docs - Product Documentation
title: Step 3 of 3 -Connect Microsoft Dynamics with Marketo (2011 On-Premises)
exl-id: e6a5d49d-025a-4899-9e92-7a4c32086c67
feature: Microsoft Dynamics
---
# Step 3 of 3: Connect Microsoft Dynamics with Marketo (2011 On-Premises) {#step-of-connect-microsoft-dynamics-with-marketo-on-premises}

Alright! We installed the solution and configured the sync user. Next, we need to connect Marketo and Dynamics.

>[!PREREQUISITES]
>
>* [Step 1 of 3: Install the Marketo Solution (2011 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2011.md){target="_blank"}
>* [Step 2 of 3: Set Up Marketo Sync User in Dynamics (2011 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2011.md){target="_blank"}

>[!NOTE]
>
>**Admin Permissions Required**

## Enter Dynamics Sync User Information {#enter-dynamics-sync-user-information}

1. Log in to Marketo and click **[!UICONTROL Admin]**.

   ![](assets/login-admin.png)

1. Click **[!UICONTROL CRM]**.

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. Click **[!DNL Microsoft]**.

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. Click **[!UICONTROL Edit]** in **[!UICONTROL Enter Credentials]**.

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >Please make sure your credentials are correct as we are unable to revert the subsequent schema changes after submission. If incorrect credentials are saved, you'll have to obtain a new Marketo subscription.

1. Enter the **[!UICONTROL Username]**, **[!UICONTROL Password]** and CRM **[!UICONTROL URL]**, then click **[!UICONTROL Save]**.

   ![](assets/image2015-4-2-14-3a50-3a7.png)

   >[!NOTE]
   >
   >* The Username in Marketo must match the User Name for the sync user in CRM. The format can be `user@domain.com` or DOMAIN\user.
   >* If you don't know the URL, [learn how to find it here](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"}.

## Select Fields to Sync {#select-fields-to-sync}

Now we need to select the fields we want to sync over.

1. Click **[!UICONTROL Edit]** in **[!UICONTROL Select Fields to Sync]**.

   ![](assets/image2015-3-16-9-51-28a.png)

1. There are preselected fields that will be synced. Add more if you want, and click **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-13-3a26-3a14.png)

   >[!NOTE]
   >
   >Marketo stores a reference to the fields to sync. If you delete a field in Dynamics, we recommended doing so with the [sync disabled](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md){target="_blank"}. Then refresh the schema in Marketo by editing and saving the [Select Fields to Sync](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md){target="_blank"}.

## Sync Fields for a Custom Filter {#sync-fields-for-a-custom-filter}

If you've created a custom filter, be sure to go in and select the new fields to be synced with Marketo.

1. Go to Admin and select **[!UICONTROL Microsoft Dynamics]**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Click **[!UICONTROL Edit]** on Field Sync Details.

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Scroll down to the field and check it. The actual name must be new_synctomkto but the Display Name can be anything. Click **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-14-3a14-3a57.png)

## Enable Sync {#enable-sync}

1. Click **[!UICONTROL Edit]** in **[!UICONTROL Enable Sync]**.

   ![](assets/image2015-3-16-9-52-2b.png)

   >[!CAUTION]
   >
   >Marketo will not automatically de-dupe against a Microsoft Dynamics sync, or when you manually enter people or leads.

1. Read everything in the pop-up, enter your email, and click **[!UICONTROL Start Sync]**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. Depending on the number of records, the initial sync can take anywhere from a few hours to a few days. You will receive an email notification upon completion.

   ![](assets/image2014-12-11-11-3a55-3a15.png)
