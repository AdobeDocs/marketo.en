---
unique-page-id: 6095008
description: Add Google AdWords as a LaunchPoint Service - Marketo Docs - Product Documentation
title: Add Google AdWords as a LaunchPoint Service
---

# Add Google AdWords as a LaunchPoint Service {#add-google-adwords-as-a-launchpoint-service}

Link your Google AdWords account to Marketo to automatically upload offline conversion data from Marketo to Google AdWords. Then, from the AdWords UI, you will be able to easily see which clicks resulted in qualified leads, opportunities, and new customers (or whatever revenue stages you want to track) after you [add custom columns](https://support.google.com/adwords/answer/3073556) in AdWords. This information does not appear in the Marketo UI.

Learn more about [Google’s offline conversion import feature](https://support.google.com/adwords/answer/2998031?hl=en).

>[!NOTE]
>
>**Admin Permissions Required**

>[!NOTE]
>
>You can also integrate a [Google AdWords as a Launchpoint service with a manager account](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service-with-a-manager-account.md).

1. Go to the **Admin** section.

   ![](assets/login-admin.png)

1. Select **LaunchPoint**.

   ![](assets/image2014-12-5-14-3a35-3a27.png)

1. Select **New** and **New Service**.

   ![](assets/image2015-2-23-14-3a54-3a50.png)

1. Enter a display name and select **Google AdWords**.

   ![](assets/new-service-google.png)

1. Select **Authorize Marketo**.

   >[!NOTE]
   >
   >Make sure to log out of your personal Gmail account and enable pop-ups.

   ![](assets/image2015-2-26-20-3a54-3a1.png)

1. Select your account associated with Google AdWords.

   ![](assets/image2015-2-23-15-3a31-3a16.png)

1. Select **Accept**.

   ![](assets/image2015-2-23-16-3a32-3a45.png)

1. Status will display as **Success**. Select **Next**.

   ![](assets/image2015-2-26-20-3a55-3a21.png)

1. Upload your offline conversions from Marketo to Google AdWords **Weekly** or **Daily**.

   ![](assets/image2015-2-23-16-3a53-3a4.png)

1. Attribute conversion to the **First Click** or **Last Click**.

   | Type |Definition |
   |---|---|
   | First Click |Offline conversions will be attributed to the first AdWords ad that a person clicked in the past 90 days |
   | Last Click |Offline conversions will be attributed to the last AdWords ad that a person clicked |

   >[!NOTE]
   >
   >Using a consistent attribution model in Marketo and AdWords provides the most accurate data.

   ![](assets/image2015-2-23-16-3a57-3a49.png)

1. Click **Create**.

   ![](assets/image2015-2-23-17-3a50-3a9.png)

   >[!NOTE]
   >
   >[Auto-tagging](https://support.google.com/adwords/answer/1752125?hl=en) must be selected for this feature to work. Deactivation must be done inside AdWords.

Great! Now see the Related Article below to learn how to map AdWords offline conversions in your revenue model.

   >[!MORELIKETHIS]
   >
   >[Set Google AdWords Conversions in the Revenue Model](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/set-google-adwords-conversions-in-the-revenue-model.md)
