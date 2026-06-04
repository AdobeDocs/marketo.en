---
description: Learn how to connect Dynamic Chat to your Marketo Engage subscription. Perform the one-time sync and select person and company attributes for targeting.
title: Adobe Marketo Engage
feature: Dynamic Chat
exl-id: 9ce43de3-0503-4894-89f2-ee24e7df9a73
TQID: https://experienceleague.adobe.com/n8HC8kkHZguZoZ2eBijiUetTrX1rY0ZLN0lIhZGUUcg
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
    internal-label: Configuration
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
subfeature_v2:
  - id: c942e9f6-ed06-481a-abdd-1195363d1452
    internal-label: Dynamic Chat
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
---
# Adobe Marketo Engage {#adobe-marketo-engage}

## Connecting Dynamic Chat {#connecting-dynamic-chat}

After you've completed the [initial setup](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.md){target="_blank"}, it is time to perform the one-time sync connecting Dynamic Chat to your Adobe Marketo Engage subscription.

>[!NOTE]
>
>Dynamic Chat supports syncing [Marketo native](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/field-types){target="_blank"} and custom person fields and company fields.

1. In My Marketo, click the **[!UICONTROL Dynamic Chat]** tile.

   ![](assets/adobe-marketo-engage-1.png)

   >[!NOTE]
   >
   >If you do not see the Dynamic Chat tile in your My Marketo screen, access Dynamic Chat from the App menu on experience.adobe.com and connect to Marketo via **Configuration** > **Integrations**. After connecting, the tile will appear.

1. If you've previously accessed an application with an Adobe ID, you'll be taken straight to Dynamic Chat. If not, [set up your Adobe ID](https://helpx.adobe.com/manage-account/using/create-update-adobe-id.html){target="_blank"}.

1. To connect your Marketo instance, select **[!UICONTROL Integrations]**.

   ![](assets/adobe-marketo-engage-2.png)

1. On the Marketo card, click **[!UICONTROL Initiate Sync]**.

   ![](assets/adobe-marketo-engage-3.png)

1. Select up to 50 attributes (standard or custom fields) from your Marketo instance to sync to Dynamic Chat for use in audience targeting, data mapping, and personalization. Click **[!UICONTROL Next]** when done.

   ![](assets/adobe-marketo-engage-4.png)

1. Review your selections. Click **[!UICONTROL Confirm]** to initiate the sync.

   ![](assets/adobe-marketo-engage-5.png)

>[!NOTE]
>
>It can take anywhere from 2 to 24 hours for the sync to complete, depending on the size of your database.

## Add an Attribute {#add-an-attribute}

After the initial sync, follow these steps to add additional attributes.

1. In **[!UICONTROL Integrations]**, verify that the **[!UICONTROL Adobe Marketo Engage]** tab is selected and click **[!UICONTROL Add Attribute]**.

   ![](assets/adobe-marketo-engage-6.png)

1. Select the attribute(s) you'd like to add and click **[!UICONTROL Next]**.

   ![](assets/adobe-marketo-engage-7.png)

1. Review your selections and click **[!UICONTROL Confirm]**.

   ![](assets/adobe-marketo-engage-8.png)

## Remove an Attribute {#remove-an-attribute}

After the initial sync, follow these steps to remove an attribute.

>[!NOTE]
>
>You'll only see the option to remove an attribute  if it is not currently in use by any Dialogues.

1. In **[!UICONTROL Integrations]**, verify that the **[!UICONTROL Adobe Marketo Engage]** tab is selected and click on the attribute you want to remove.

   ![](assets/adobe-marketo-engage-9.png)

1. Click **[!UICONTROL Remove Attribute]**.

   ![](assets/adobe-marketo-engage-10.png)

>[!MORELIKETHIS]
>
>[Initial Setup](/help/marketo/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.md){target="_blank"}
