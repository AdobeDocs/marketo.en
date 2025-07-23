---
unique-page-id: 7504744
description: Install Marketo for Microsoft Dynamics 2015 On-Premises Step 3 of 3 - Marketo Docs - Product Documentation
title: Install Marketo for Microsoft Dynamics 2015 On-Premises Step 3 of 3
exl-id: 054bf725-7a80-4114-8360-2d86e2e33dd7
feature: Microsoft Dynamics
---
# Step 3 of 3: Connect Marketo [!DNL Dynamics] (2015 On-Prem) {#step-of-connect-marketo-dynamics-on-premises-2015}

>[!PREREQUISITES]
>
>* [Install Marketo for [!DNL Microsoft Dynamics] 2015 On-Premises Step 1 of 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2015.md)
>* [Install Marketo for [!DNL Microsoft Dynamics] 2015 On-Premises Step 2 of 3](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-set-up-2015.md)

>[!NOTE]
>
>**Admin Permissions Required**

## Enter [!DNL Dynamics] Sync User information {#enter-dynamics-sync-user-information}

1. Log in to Marketo and click **[!UICONTROL Admin]**.

   ![](assets/login-admin.png)

1. Click **[!UICONTROL CRM]**.

   ![](assets/image2015-3-16-9-47-34.png)

1. Select **[!UICONTROL Microsoft]**.

   ![](assets/image2015-3-16-9-50-6.png)

1. Click **[!UICONTROL Edit]** in **[!UICONTROL Step 1: Enter Credentials]**.

   ![](assets/image2015-3-16-9-48-43.png)

   >[!CAUTION]
   >
   >Please make sure your credentials are correct as we are unable to revert the subsequent schema changes after submission. If incorrect credentials are saved, you'll have to obtain a new Marketo subscription.

1. Enter the **[!UICONTROL Username]**, **[!UICONTROL Password]** a [!DNL Microsoft Dynamics] **URL**, and a **[!UICONTROL Client Id]/[!UICONTROL Client Secret]**. Click **[!UICONTROL Save]** when done.

   ![](assets/step-3-of-3-5.png)

   >[!NOTE]
   >
   >* If your Marketo was provisioned prior to October 2020, Client ID and Secret are optional fields. Otherwise, they're mandatory. Obtaining this information will depend on what version of MSD you're using.
   >* The Username in Marketo must match the User Name for the sync user in CRM. The format can be `user@domain.com` or DOMAIN\user.
   >* If you don't know the URL, [learn how to find it here](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"}.

   >[!TIP]
   >
   >Don't know the URL? We will show you how to find your [Dynamics Organization Service URL](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"} here.

## Select Fields to Sync {#select-fields-to-sync}

1. Click **[!UICONTROL Edit]** in **[!UICONTROL Step 2: Select Fields to Sync]**.

   ![](assets/image2015-3-16-9-51-28.png)

1. Select the fields that you want to sync to Marketo, so they will be pre-selected. Click **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a14-3a28.png)

>[!NOTE]
>
>Marketo stores a reference to the fields to sync. If you delete a field in [!DNL Dynamics], we recommended doing so with the [sync disabled](/help/marketo/product-docs/crm-sync/salesforce-sync/enable-disable-the-salesforce-sync.md). Then refresh the schema in Marketo by editing and saving the [[!UICONTROL Select Fields to Sync]](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/microsoft-dynamics-sync-details/microsoft-dynamics-sync-field-sync/editing-fields-to-sync-before-deleting-them-in-dynamics.md).

## Sync Fields for a Custom Filter {#sync-fields-for-a-custom-filter}

If you've created a custom filter, be sure to go in and select the new fields to be synced with Marketo.

1. Go to [!UICONTROL Admin] and select **[!UICONTROL Microsoft Dynamics]**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Click **[!UICONTROL Edit]** on [!UICONTROL Field Sync Details].

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Scroll down to the field and check it. The actual name must be new_synctomkto but the Display Name can be anything. Click **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a15-3a35.png)

## Enable Sync {#enable-sync}

1. Click **[!UICONTROL Edit]** in **[!UICONTROL Step 3: Enable Sync]**.

   ![](assets/image2015-3-16-9-52-2.png)

   >[!CAUTION]
   >
   >Marketo will not automatically de-dupe against a [!DNL Microsoft Dynamics] sync, or when you manually enter people.

1. Read everything in the pop-up, enter your email, and click **[!UICONTROL Start Sync]**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. Depending on the number of records, the initial sync can take anywhere from a few hours to a few days. You will receive an email notification upon completion.

   ![](assets/image2015-3-16-9-59-51.png)
