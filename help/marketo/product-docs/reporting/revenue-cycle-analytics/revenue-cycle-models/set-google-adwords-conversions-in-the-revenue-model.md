---
unique-page-id: 6095029
description: Set Google AdWords Conversions in the Revenue Model - Marketo Docs - Product Documentation
title: Set Google AdWords Conversions in the Revenue Model
---

# Set Google AdWords Conversions in the Revenue Model {#set-google-adwords-conversions-in-the-revenue-model}

Link your Google AdWords account to Marketo to automatically upload offline conversion data from Marketo to Google AdWords. Then, from the AdWords UI, you will be able to easily see which clicks resulted in qualified leads, opportunities and new customers (or whatever revenue stages you want to track) after you  [add custom columns](https://support.google.com/adwords/answer/3073556)  in AdWords.

>[!NOTE]
>
>This is a push integration from Marketo to Google AdWords. Conversion data will appear *only* in your Google AdWords portal,** not in the Marketo UI. **

Learn more about  [Google’s offline conversion import feature](https://support.google.com/adwords/answer/2998031?hl=en).  Map AdWords offline conversions to one or more stages in a Revenue model. There are three ways to do the mapping:

* 
  AdWords Conversion 
* 
  Stage Action 
* AdWords Mapping

You can create a new AdWords offline conversion from Marketo if you use Stage Action.

>[!NOTE]
>
>**Prerequisites**
>
>* [Add Google AdWords as a LaunchPoint Service](../../../../product-docs/administration/additional-integrations/add-google-adwords-as-a-launchpoint-service.md)
>

## Use AdWords Conversion {#use-adwords-conversion}

1. Go to the **Analytics** area.

   ![](assets/image2015-2-23-18-3a9-3a34.png)

1. Select a model.

   ![](assets/image2015-2-23-18-3a3-3a12.png)

1. Click **Edit Draft**.

   ![](assets/image2015-3-10-15-3a3-3a20.png)

1. Select the revenue stage you want to map to an AdWords conversion.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. Select the **AdWords Conversion** you'd like to map to your Marketo stage.

   ![](assets/image2015-2-26-16-3a46-3a15.png)

   Nice! Your AdWords conversion data will be uploaded to your Google AdWords at the cadence you selected.

## Use Stage Action {#use-stage-action}

You can also map an AdWords Conversion under Stage Actions.

1. Select the step you want to map to an AdWords conversion.

   ![](assets/image2015-2-26-16-3a40-3a2.png)

1. Under the **Stage Actions** drop down, select **Set AdWords Conversion**.

   ![](assets/image2015-2-26-16-3a52-3a24.png)

1. Select an **AdWords Conversion**.

   ![](assets/image2015-2-26-16-3a54-3a47.png)

   **Tip**: If you don't have any AdWords conversions, create one by clicking **+New Conversion**.

   ![](assets/image2015-2-26-21-3a22-3a10.png)

1. Click **Save**.

   ![](assets/image2015-2-26-16-3a56-3a2.png)

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

   ![](assets/image2015-2-26-21-3a22-3a10.png)

1. Enter a **Conversion Name**. Click **Save**.

   ![](assets/image2015-2-26-21-3a24-3a7.png)

   Excellent! This new conversion will appear in your AdWords account.

## Use AdWords Mapping {#use-adwords-mapping}

You can associate all your model stages with your AdWords Conversion in one place using AdWords Mappings.

1. Select **Edit AdWords Mappings**.

   ![](assets/image2015-2-26-17-3a3-3a29.png)

1. Select the desired **AdWords Conversion** for each stage that you want to track.

   ![](assets/image2015-2-26-17-3a6-3a15.png)

1. Once you've mapped your stages, click **Save**.

   ![](assets/image2015-2-26-17-3a7-3a48.png)

1. After you are done mapping all of your AdWords conversions to revenue stages, go back to the summary page. Select **Model Actions** and choose **Approve Stages**.

   ![](assets/image2015-2-27-12-3a20-3a20.png)

In order to view the offline conversion data, you will need to log into your AdWords account. We recommend you use their [Custom Columns feature](https://support.google.com/adwords/answer/3073556) to create conversion count columns for each offline conversion you import from Marketo.
