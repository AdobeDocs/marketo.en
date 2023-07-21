---
unique-page-id: 7504923
description: Set Google AdWords Conversions in the Revenue Model with a Manager Account - Marketo Docs - Product Documentation
title: Set Google AdWords Conversions in the Revenue Model with a Manager Account
exl-id: 8c9f50cf-0a8b-4f9a-a0bd-bb57eeac24cf
feature: "Reporting, Revenue Cycle Analytics"
---
# Set Google AdWords Conversions in the Revenue Model with a Manager Account {#set-google-adwords-conversions-in-the-revenue-model-with-a-manager-account}

Link your Google AdWords account to Marketo to automatically upload offline conversion data from Marketo to Google AdWords. Then, from the AdWords UI, you will be able to easily see which clicks resulted in qualified leads, opportunities and new customers (or whatever revenue stages you want to track) after you [add custom columns](https://support.google.com/adwords/answer/3073556) in AdWords.

If you have multiple Google Adwords accounts, you can use a [Google AdWords Manager Account](https://www.google.com/adwords/manager-accounts/) (formerly known as My Client Center) to integrate them with Marketo.

You can map AdWords offline conversions to one or more stages in a Revenue model. There are two ways:

* Stage Action
* AdWords Mapping

>[!PREREQUISITES]
>
>[Add Google AdWords as a Launchpoint Service with a Manager Account](/help/marketo/product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service-with-a-manager-account.md)

## Use Stage Action {#use-stage-action}

Map an AdWords Conversion under Stage Actions.

1. Select the step you want to map to an AdWords conversion.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. Under the **Stage Actions** drop down, select **Set AdWords Conversion**.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Set an **AdWords Conversion**.

   >[!NOTE]
   >
   >A different AdWords conversion can be selected for each child account.

   ![](assets/image2015-3-27-17-3a16-3a37.png)

   Tip: If you don't have any AdWords conversions, create one by clicking **+New Conversion**.

   ![](assets/image2015-3-27-17-3a18-3a58.png)

1. Click **Save**.

   ![](assets/image2015-3-27-17-3a21-3a15.png)

1. After you are done mapping all of your AdWords conversions to revenue stages, go back to the summary page. Select **Model Actions** and choose **Approve Stages**.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

## Pro tip: Add a New Conversion {#pro-tip-add-a-new-conversion}

Pro tip! A new AdWords offline conversion can be created from Marketo.

>[!CAUTION]
>
>New conversions created from Marketo have the "optimization" setting enabled. This means that AdWords bid strategies are allowed to optimize your bids for those conversions. You can change this setting from your AdWords account.

1. Under the **Stage Actions** drop down, select **Set AdWords Conversion**.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Select **New Conversion**.

   ![](assets/image2015-3-27-17-3a23-3a13.png)

1. Enter a **Conversion Name**. Click **Save**.

   ![](assets/image2015-3-27-17-3a24-3a49.png)

   Excellent! This new conversion will appear in your AdWords account.

## Use AdWords Mapping {#use-adwords-mapping}

You can associate all your model stages with your AdWords Conversion in one place using AdWords Mappings.

1. Select **Edit AdWords Mappings**.

   ![](assets/image2015-2-26-17-3a3-3a29.png)

1. Select the desired **AdWords Account** and desired **AdWords Conversion** for each stage that you want to track.

   ![](assets/image2015-3-27-17-3a30-3a15.png)

1. Once you've mapped your stages, click **Save**.

   ![](assets/image2015-3-27-17-3a30-3a48.png)

1. After you are done mapping all of your AdWords conversions to revenue stages, go back to the summary page. Select **Model Actions** and choose **Approve Stages**.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

In order to view the offline conversion data, you will need to log into your AdWords account. We recommend you use their [Custom Columns feature](https://support.google.com/adwords/answer/3073556) to create conversion count columns for each offline conversion you import from Marketo.
