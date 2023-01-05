---
description: Reply Logging - Marketo Docs - Product Documentation
title: Reply Logging
hide: yes
hidefromtoc: yes
exl-id: a89e8212-83cb-4987-abc9-76c5fd74c152
---
# Reply Logging {#reply-logging}

Sales Insight Actions arms you with the ability to automatically log your prospects' replies to [!DNL Salesforce]. The structure that allows you to do this is based on our email reply tracking. If we can track a prospect's reply, we can log that reply to [!DNL Salesforce].

## Requirements {#requirements}

* Must be logging emails via API logging
* Must be able to [track a reply](/help/marketo/product-docs/marketo-sales-insight/actions/send-a-sales-email/email-tracking-overview.md#how-reply-tracking-works)
* Must be connected with [!DNL Salesforce]
* Must have [!DNL Salesforce] [API calls](https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm) available

## Enable Reply Logging {#enable-reply-logging}

1. To enable reply logging you can head over to your [!DNL Salesforce] settings page. Once API logging is checked off you will see the option to check _Log Replies_.

   >[!NOTE]
   >
   >Reply logging follows the same rules you have in place for logging emails sent. This includes how emails are logged; to Leads and Contacts; when there is a duplicate record; if no matching records are found.

## Setting Type to Reply in [!DNL Salesforce] {#setting-type-to-reply-in-salesforce}

Getting meaningful data from your [!DNL Salesforce] reports is important. Having the ability to have the Type field populate as 'Reply' allows you to get that data through your reports. Partner up with your `[!DNL Salesforce] admin` to get this setup.

1. Go to **[!UICONTROL Setup]** > **[!UICONTROL Customize]** > **[!UICONTROL Activities]** > **[!UICONTROL Task Fields]**.
1. Click **[!UICONTROL Type]**.
1. Under [!UICONTROL Task Type Picklist Values], click **[!UICONTROL New]**.
1. Type "Reply" into the empty box. Make sure you capitalize the 'R' and click **[!UICONTROL Save]**.

   >[!NOTE]
   >
   >You will not need to select a Default under the Type picklist. [!DNL Sales Insight Actions] will see that this Activity Type is available in your [!DNL Salesforce] instance and populate the task field on your incoming activities accordingly.
