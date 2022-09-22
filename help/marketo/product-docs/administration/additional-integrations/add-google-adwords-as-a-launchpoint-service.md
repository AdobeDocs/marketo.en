---
unique-page-id: 6095008
description: Add Google AdWords as a LaunchPoint Service - Marketo Docs - Product Documentation
title: Add Google AdWords as a LaunchPoint Service
exl-id: 993a057a-3f98-4a9f-a770-c9c80dedfd81
---
# Add Google AdWords as a LaunchPoint Service {#add-google-adwords-as-a-launchpoint-service}

Link your Google AdWords account to Marketo to automatically upload offline conversion data from Marketo to Google AdWords. Then, from the AdWords UI, you will be able to easily see which clicks resulted in qualified leads, opportunities, and new customers (or whatever revenue stages you want to track) after you [add custom columns](https://support.google.com/adwords/answer/3073556){target="_blank"} in AdWords. This information does not appear in the Marketo UI.

Learn more about [Google’s offline conversion import feature](https://support.google.com/adwords/answer/2998031?hl=en){target="_blank"}.

>[!AVAILABILITY]
>
>Not all customers have purchased this feature. Please contact your Customer Success Manager for details.

>[!NOTE]
>
>**Admin Permissions Required**

>[!NOTE]
>
>You can also integrate a [Google AdWords as a Launchpoint service with a manager account](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service-with-a-manager-account.md){target="_blank"}.

1. Go to the **Admin** section.

   ![](assets/add-google-adwords-as-a-launchpoint-service-1.png)

1. Select **LaunchPoint**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-2.png)

1. Select **New** and **New Service**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-3.png)

1. Enter a display name and select **Google AdWords**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-4.png)

1. Select **Authorize Marketo**.

   >[!NOTE]
   >
   >Make sure to log out of your personal Gmail account and enable pop-ups.

   ![](assets/add-google-adwords-as-a-launchpoint-service-5.png)

1. Select your account associated with Google AdWords.

   ![](assets/add-google-adwords-as-a-launchpoint-service-6.png)

1. Select **Accept**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-7.png)

1. Status will display as **Success**. Select **Next**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-8.png)

1. Upload your offline conversions from Marketo to Google AdWords **Weekly** or **Daily**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-9.png)

1. Attribute conversion to the **First Click** or **Last Click**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-10.png)

   | Type |Definition |
   |---|---|
   | First Click |Offline conversions will be attributed to the first AdWords ad that a person clicked in the past 90 days |
   | Last Click |Offline conversions will be attributed to the last AdWords ad that a person clicked |

   >[!NOTE]
   >
   >Using a consistent attribution model in Marketo and AdWords provides the most accurate data.

1. Click **Create**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-11.png)

   >[!NOTE]
   >
   >[Auto-tagging](https://support.google.com/adwords/answer/1752125?hl=en){target="_blank"} must be selected for this feature to work. Deactivation must be done inside AdWords.

Great! Now see the Related Article below to learn how to map AdWords offline conversions in your revenue model.

   >[!MORELIKETHIS]
   >
   >[Set Google AdWords Conversions in the Revenue Model](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/set-google-adwords-conversions-in-the-revenue-model.md){target="_blank"}
