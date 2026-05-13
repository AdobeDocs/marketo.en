---
description: Learn about priority override for trigger campaigns. Control which campaign runs when multiple triggers fire for the same person.
title: Priority Override for Trigger Campaigns
exl-id: cf9b4d27-0e4c-40cf-accd-4f4a102160cc
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/XEyORsYajQEhtF-bajLFTtbOsSFg-lM9zU4gUyFcmWk
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Priority Override for Trigger Campaigns {#priority-override-for-trigger-campaigns}

Admins can override the Marketo Engage determined priority for Trigger Campaigns to set priorities that better align with business objectives.

>[!NOTE]
>
>This feature is only available for Trigger Campaigns and to users who have been granted the ["Edit Trigger Campaign Priority" permission](#grant-priority-override-access).

>[!CAUTION]
>
>It is strongly advised that you use this feature on a limited set of business critical campaigns (25 is the recommended maximum). Using the feature loosely on a large set can adversely affect overall campaign execution.

## Grant Priority Override Access {#grant-priority-override-access}

>[!NOTE]
>
>Only Admins or users with admin responsibilities should have campaign priority override access.

1. In the **[!UICONTROL Admin]** area, click **[!UICONTROL Users & Roles]**.

   ![](assets/priority-override-for-trigger-campaigns-1.png)

1. Click the **[!UICONTROL Roles]** tab, select the user you want to grant access to, then click **[!UICONTROL Edit Role]**.

   ![](assets/priority-override-for-trigger-campaigns-2.png)

1. Under **[!UICONTROL Access Marketing Activities]**, select **[!UICONTROL Edit Trigger Campaign Priority]**. Click **[!UICONTROL Save]**.

   ![](assets/priority-override-for-trigger-campaigns-3.png)

## Override Priority {#override-priority}

1. Locate your Trigger Campaign. Right-click on it and select **[!UICONTROL Override Campaign Priority]**.

   ![](assets/priority-override-for-trigger-campaigns-4.png)

1. Click the **[!UICONTROL Override Campaign Priority]** slider to enable. Choose a new priority level and click **[!UICONTROL Confirm]**.

   ![](assets/priority-override-for-trigger-campaigns-5.png)

   The new priority level will show in the **[!UICONTROL Schedule]** tab.

   ![](assets/priority-override-for-trigger-campaigns-6.png)

>[!NOTE]
>
>* You can view your campaign's default priority in the [!UICONTROL Campaign Queue] under [!UICONTROL Marketing Activities]. To boost execution rate, we recommend setting your campaign priority to one level higher than its default.
>* User set priority applies only to new people who qualify for the campaign; people who are already in-queue will not be affected.
>* Priority overrides are captured in [Audit Trail](/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md){target="_blank"}.
