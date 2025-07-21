---
unique-page-id: 3571819
description: Step 3 of 3 -Connect Marketo and Dynamics (2013 On-Premises) - Marketo Docs - Product Documentation
title: Step 3 of 3 -Connect Marketo and Dynamics (2013 On-Premises)
exl-id: e28f1cc3-ee15-4981-a537-6c4a1682c4c1
feature: Microsoft Dynamics
---
# Step 3 of 3: Connect Marketo and [!DNL Dynamics] (2013 On-Premises) {#step-of-connect-marketo-and-dynamics-on-premises}

Alright! We installed the solution and configured the sync user. Next, we need to connect Marketo and [!DNL Dynamics].

>[!PREREQUISITES]
>
>* [Step 1 of 3: Install the Marketo Solution in [!DNL Dynamics] (2013 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-1-of-3-install-2013.md)
>* [Step 2 of 3: Configure Sync User for Marketo (2013 On-Premises)](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/connecting-to-legacy-versions/step-2-of-3-configure-2013.md)

>[!NOTE]
>
>**Admin Permissions Required**

## Enter [!DNL Dynamics] Sync User Information {#enter-dynamics-sync-user-information}

1. Log in to Marketo and click **[!UICONTROL Admin]**.

   ![](assets/login-admin.png)

1. Click on **[!UICONTROL CRM]**.

   ![](assets/image2014-12-11-11-3a53-3a59.png)

1. Select **[!DNL Microsoft]**.

   ![](assets/image2014-12-11-11-3a54-3a10.png)

1. Click **[!UICONTROL Edit]** in **[!UICONTROL Step 1: Enter Credentials]**.

   ![](assets/image2014-12-11-11-3a54-3a19.png)

   >[!CAUTION]
   >
   >Please make sure your credentials are correct as we are unable to revert the subsequent schema changes after submission. If incorrect credentials are saved, you'll have to obtain a new Marketo subscription.

1. Enter the **[!UICONTROL Username]**, **[!UICONTROL Password]** and [!DNL Microsoft Dynamics] **URL** then click **[!UICONTROL Save]**.

   ![](assets/image2015-3-26-11-3a47-3a59.png)

   >[!NOTE]
   >
   >* The Username in Marketo must match the User Name for the sync user in CRM. The format can be `user@domain.com` or DOMAIN\user.
   >* If you don't know the URL, [learn how to find it here](/help/marketo/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/view-the-organization-service-url.md){target="_blank"}.

## Select Fields to Sync {#select-fields-to-sync}

Now we need to select the fields we want to sync over.

1. Click **[!UICONTROL Edit]** in **[!UICONTROL Step 2: Select Fields to Sync]**.

   ![](assets/image2015-3-16-9-3a51-3a28.png)

1. Select the fields that you want to sync to Marketo, so they will be pre-selected. Click **[!UICONTROL Save]**.

   ![](assets/image2016-8-25-15-3a10-3a17.png)

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

   ![](assets/image2016-8-25-15-3a11-3a4.png)

## Enable Sync {#enable-sync}

1. Click **[!UICONTROL Edit]** in **[!UICONTROL Step 3: Enable Sync]**.

   ![](assets/image2015-3-16-9-3a52-3a2.png)

   >[!CAUTION]
   >
   >Marketo will not automatically de-dupe against a [!DNL Microsoft Dynamics] sync, or when you manually enter people or leads.

1. Read everything in the pop-up, enter your email, and click **[!UICONTROL Start Sync]**.

   ![](assets/image2015-3-30-14-3a23-3a13.png)

1. Depending on the number of records, the initial sync can take anywhere from a few hours to a few days. You will receive an email notification upon completion.

   ![](assets/image2014-12-11-11-3a55-3a15.png)

Excellent work! You have just unleashed the power of the bi-directional sync between Marketo and [!DNL Microsoft Dynamics]. If you have purchased [!DNL Marketo Sales Insight], there is more fun to be had:

>[!MORELIKETHIS]
>
>[Install and Configure [!DNL Marketo Sales Insight] in [!DNL Microsoft Dynamics] 2013](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/install-and-configure-marketo-sales-insight-in-microsoft-dynamics-2013.md)
