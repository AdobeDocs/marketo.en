---
unique-page-id: 2953243
description: "Notification Types - Marketo Docs - Product Documentation"
title: Notification Types
exl-id: 384cea0a-6252-4600-9211-aa5d6a7e875c
---
# Notification Types {#notification-types}

There are several notification types.

## Campaign Failure  {#campaign-failure}

Campaign failures notify you of errors in your smart campaigns.

## CRM Sync {#crm-sync}

CRM sync notifications alert you to critical issues found with the CRM sync, such as incorrect permissions or the sync being down.

**[!DNL Microsoft Dynamics]**

[!DNL Dynamics] notifications are sent once every 24 hours, and contain leads that failed to sync in that time period. Typical reasons for failure are duplicate leads (as above) or field length mismatch errors.

![](assets/image2016-1-20-11-3a19-3a58.png)

**[!DNL Salesforce]**

If you use [!DNL Salesforce], sync error notifications look something like the one below. Typical errors include expired credentials and exceeded API limits.

![](assets/salesforcesyncerror.png)

## Engagement {#engagement}

When people become exhausted in a stream, we send a notification. The notification includes the number of people who became exhausted and some other information.

![](assets/image2014-10-14-10-3a57-3a9.png)

## Facebook {#facebook}

If you try to send people to Facebook without accepting the Terms of Service, or if you try to send people to Facebook after removing the Marketo app.

## Idle Trigger Campaign Cleanup {#idle-trigger-campaign-cleanup}

Deactivate triggered Smart Campaigns that no longer get any activity. Learn more about  [automatic trigger campaign cleanup](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/automatic-trigger-campaign-cleanup.md).

## LinkedIn {#linkedin}

When Marketo is unable to create a new audience, login, or push emails to LinkedIn after three tries.

![](assets/linkedin.png)

## Web Services {#web-services}

You will be notified when you reach your daily quota. The quota resets each night at midnight, Central Time.

>[!NOTE]
>
>Some of the error codes you may receive are outlined in our [Developer Documentation](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/error-codes).
