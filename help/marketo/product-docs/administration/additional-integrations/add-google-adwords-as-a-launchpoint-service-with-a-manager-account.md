---
unique-page-id: 7504893
description: Add Google AdWords as a Launchpoint Service with a Manager Account - Marketo Docs - Product Documentation
title: Add Google AdWords as a Launchpoint Service with a Manager Account
exl-id: aac106f4-6615-49d5-a561-0dd965c7b0ff
---
# Add Google AdWords as a Launchpoint Service with a Manager Account {#add-google-adwords-as-a-launchpoint-service-with-a-manager-account}

Link your Google AdWords account to Marketo to automatically upload offline conversion data from Marketo to Google AdWords. Then, from the AdWords UI, you will be able to easily see which clicks resulted in qualified leads, opportunities and new customers (or whatever revenue stages you want to track) after you  [add custom columns](https://support.google.com/adwords/answer/3073556){target="_blank"} in AdWords. This information does not appear in the Marketo UI.

If you have multiple Google Adwords accounts, you can use a [Google AdWords Manager Account](https://www.google.com/adwords/manager-accounts/){target="_blank"} (formerly known as My Client Center) to integrate them with Marketo.

Learn more about [Google’s offline conversion import feature](https://support.google.com/adwords/answer/2998031?hl=en){target="_blank"}.

>[!AVAILABILITY]
>
>Not all customers have purchased this feature. Please contact your Customer Success Manager for details.

>[!NOTE]
>
>**Admin Permissions Required**

>[!NOTE]
>
>You can also integrate a [stand-alone Google AdWords account as a Launchpoint service](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service.md){target="_blank"}.

1. Go to the **Admin** section.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-1.png)

1. Select **LaunchPoint**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-2.png)

1. Click the **New** drop-down and select **New Service**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-3.png)

1. Enter a Display Name and select **Google AdWords**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-4.png)

1. Select **Authorize Marketo**.

   >[!NOTE]
   >
   >Make sure to log out of your personal Gmail account and enable pop-ups.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-5.png)

1. Select your account associated with **Google AdWords**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-6.png)

1. Click **Accept**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-7.png)

1. Status will display as **Success**. Select **Next**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-8.png)

1. Upload your offline conversions from Marketo to Google AdWords **Weekly** or **Daily**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-9.png)

1. Attribute conversion to the **First Click** or **Last Click**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-10.png)

   | Type |Definition |
   |---|---|
   | First Click |Offline conversions will be attributed to the first AdWords ad that a person clicked in the past 90 days |
   | Last Click |Offline conversions will be attributed to the last AdWords ad that a person clicked |

   >[!NOTE]
   >
   >[Auto-tagging](https://support.google.com/adwords/answer/1752125?hl=en){target="_blank"} must be selected for this feature to work. It must be activated inside AdWords.

1. Click **Next**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-11.png)

1. Deselect accounts you do not want to update. Click **Create**.

   ![](assets/add-google-adwords-as-a-launchpoint-service-with-a-manager-12.png)

   Now see the Related Article below for how to map AdWords offline conversions in your revenue model.

   >[!MORELIKETHIS]
   >
   >[Set Google AdWords Conversions in the Revenue Model with a Manager Account](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/set-google-adwords-conversions-in-the-revenue-model-with-a-manager-account.md){target="_blank"}
