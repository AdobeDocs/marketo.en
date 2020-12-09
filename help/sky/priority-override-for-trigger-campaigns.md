---
title: priority-override-for-trigger-campaigns
description: Priority Override for Trigger Campaigns
---

# Priority Override for Trigger Campaigns

<br>&nbsp;

Admins can override Marketo's determined priority for trigger campaigns to set priorities that better align with business objectives.

>[!NOTE]
>
>This feature is only available for trigger campaigns and to users who have been granted the “Edit Trigger Campaign Priority” permission.

>[!CAUTION]
>
>It is strongly advised that you use this feature on a limited set of business critical campaigns (25 is the recommended maximum). Using the feature loosely on a large set can adversely affect overall campaign execution.

## Override Priority

1. In your trigger campaign, click the **[!UICONTROL Schedule]** tab, then click **[!UICONTROL Override Priority]**.

   ![Image One](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-1.png)

1. Choose a new priority level from the drop-down. Click **[!UICONTROL Confirm]**.

   ![Image Two](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-2.png)

   ![Image Three](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-3.png)

>[!NOTE]
>
>* You can view your campaign's default priority in the [!UICONTROL Campaign Queue] under [!UICONTROL Marketing Activities]. To boost execution rate, we recommend setting your campaign priority to one level higher than its default.
>* User set priority applies only to new people who qualify for the campaign; people who are already in-queue will not be affected.

## Reset Priority

1. To reset campaign priority back to the system default, go to the **[!UICONTROL Schedule]** tab in your trigger campaign and click **[!UICONTROL Reset Priority]**.

   ![Image Four](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-4.png)

1. Click **[!UICONTROL Reset]** to confirm.

   ![Image Five](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-5.png)

>[!NOTE]
>
>Priority overrides and resets are captured in Audit Trail. You can view the [Audit Trail](https://docs.marketo.com/x/GZ2t) through the [!UICONTROL Admin] area in the Classic experience.

## Grant Priority Override Access

>[!CAUTION]
>
>Only Admins or users with admin responsibilities should have campaign priority override access.

1. In the [!UICONTROL Admin] area, click **[!UICONTROL Users & Roles]**.

   ![Image Six](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-6.png)

1. Click the **[!UICONTROL Roles]** tab, select the user you want to grant access to, then click **[!UICONTROL Edit Role]**.

   ![Image Seven](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-7.png)

1. Under [!UICONTROL Access Marketing Activities], check **[!UICONTROL Edit Trigger Campaign Priority]**. Click **[!UICONTROL Save]**.

   ![Image Eight](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-8.png)

## View Campaign Priority in Marketo Classic

You can view campaign priority in the [!DNL Classic] experience by clicking the **[!UICONTROL Schedule]** tab within a trigger campaign.

   ![Image Nine](/help/sky/assets/smart-campaigns/priority-override-for-trigger-campaigns/priority-override-for-trigger-campaigns-9.png)

>[!NOTE]
>
>The priority in the [!DNL Classic] experience is view-only. Changing or resetting campaign priority is only available through Marketo Sky.
