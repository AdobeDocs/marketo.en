---
unique-page-id: 4719308
description: Learn how to add an existing Salesforce field to the Marketo sync. Make the field visible to the sync user in Salesforce so it syncs on the next cycle.
title: Add an Existing Salesforce Field to the Marketo Sync
exl-id: 6030aedd-9c4b-411f-89c7-f35fd39b0066
feature: Salesforce Integration
TQID: https://experienceleague.adobe.com/Vb-1DhNwUPQSPYuCkVzzSDDqWd4tvO-XoPhXn58hj6E
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
topic_v2:
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
---
# Add an Existing [!DNL Salesforce] Field to the Marketo Sync {#add-an-existing-salesforce-field-to-the-marketo-sync}

>[!NOTE]
>
>**Admin Permissions Required**

Usually, new custom fields in Salesforce sync over to Marketo Engage automatically. If not, the fields may not be visible to the Marketo Sync user. Here's how you can fix this.

1. Click your name and then select **[!UICONTROL Setup]**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-1.png)

1. Enter "profile" in the left search bar and click **[!UICONTROL Profiles]** under **[!UICONTROL Manage Users]**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-2.png)

1. Click the sync user's profile.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-3.png)

1. Under the **[!UICONTROL Field-Level Security]** section, click **[!UICONTROL View]** next to the object that contains the field.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-4.png)

1. Click **[!UICONTROL Edit]**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-5.png)

1. Check the **[!UICONTROL Visible]** checkbox for the field you want to add to the sync and click **[!UICONTROL Save]**.

   ![](assets/add-an-existing-salesforce-field-to-the-marketo-sync-6.png)

   On the next sync cycle, Marketo will see the field and start the magic.

   >[!NOTE]
   >
   > If the field already has values in [!DNL Salesforce], those values don't sync over to Marketo until the next record update.
