---
unique-page-id: 2360243
description: Set a maximum number of people who can qualify for a Smart Campaign to avoid accidentally emailing the whole database.
title: Enable Person Restrictions for Smart Campaigns
exl-id: 45bdaf3f-874c-493f-9746-440f7703713c
feature: Email Setup
TQID: https://experienceleague.adobe.com/6VwkOwN9nTqSyNcXvzyggPTk0Um5x1GPXIp2DBf2kww
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Enable Person Restrictions for Smart Campaigns {#enable-person-restrictions-for-smart-campaigns}

There is a feature in Marketo to limit the _maximum_ number of people who can qualify for a Smart Campaign. This avoids accidentally emailing your whole database.

>[!NOTE]
>
>**Admin Permissions Required**

>[!CAUTION]
>
>This applies only to batch campaigns and email programs.

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/enable-person-restrictions-for-smart-campaigns-1.png)

1. Click **[!UICONTROL Smart Campaign]**.

   ![](assets/enable-person-restrictions-for-smart-campaigns-2.png)

1. Click **[!UICONTROL Edit]**.

   ![](assets/enable-person-restrictions-for-smart-campaigns-3.png)

   >[!CAUTION]
   >
   >If the number of people who qualify to run through a Smart Campaign exceeds the limit set, then it will not run at all.

1. Enter a limit and click **[!UICONTROL Save]**.

   ![](assets/enable-person-restrictions-for-smart-campaigns-4.png)

   >[!TIP]
   >
   >Disable this feature by making this field blank.

   >[!CAUTION]
   >
   >This limit is applied to all the Smart Campaigns but can be overridden at the campaign level. Learn how to [override person restrictions in a Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/override-person-restrictions-in-a-smart-campaign.md).

>[!MORELIKETHIS]
>
>[Override Person Restrictions in a Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/override-person-restrictions-in-a-smart-campaign.md)
