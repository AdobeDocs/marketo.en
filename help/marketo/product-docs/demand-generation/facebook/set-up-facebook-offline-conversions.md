---
unique-page-id: 11383953
description: Set up Facebook Offline Conversions - Marketo Docs - Product Documentation
title: Set up Facebook Offline Conversions
exl-id: e1974943-8fc8-41f6-be7e-1b594de13db6
---
# Set up [!DNL Facebook] Offline Conversions {#set-up-facebook-offline-conversions}

By sending offline conversion data back to [!DNL Facebook] for people created via Lead Ads, your advertising team can optimize their ad spend better than ever. Here's how to set it up.

>[!PREREQUISITES]
>
>* You must [set up Facebook Lead Ads](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md).
>* You must have an approved model in [Revenue Cycle Modeler](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-cycle-models/understanding-revenue-models.md).

## Admin Configuration {#admin-configuration}

1. Go to Marketo **[!UICONTROL Admin]**.

   ![](assets/image2016-11-29-13-3a8-3a45.png)

1. Go to **[!UICONTROL LaunchPoint]** and double-click the Facebook Lead Ads service you created previously.

   >[!NOTE]
   >
   >If you haven't done that, go ahead and [Set Up [!UICONTROL Facebook Lead Ads]](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md), then come back here.

   ![](assets/image2016-11-29-13-3a10-3a43.png)

1. If you like, edit the **[!UICONTROL Display Name]** to include Offline Conversions. Click **[!UICONTROL Next]**.

   ![](assets/image2016-11-29-13-3a12-3a19.png)

1. Check **[!UICONTROL Enable Offline Conversions]** and click **[!UICONTROL Next]**.

   ![](assets/image2016-11-29-13-3a13-3a32.png)

1. Click **[!UICONTROL Next]**.

   ![](assets/image2016-11-29-13-3a14-3a17.png)

1. Click **[!UICONTROL Save]**.

   ![](assets/image2016-11-29-13-3a14-3a52.png)

   Sweet! You're halfway done enabling [!DNL Facebook] Offline Conversions. Let's hop over to the Revenue Cycle Modeler to map the stages.

   ![](assets/image2016-11-29-13-3a16-3a55.png)

## Revenue Cycle Modeler Configuration {#revenue-cycle-modeler-configuration}

1. Go to **[!UICONTROL Analytics]**.

   ![](assets/image2016-11-29-13-3a29-3a23.png)

1. Select your model and click **[!UICONTROL Edit Draft]**.

   ![](assets/image2016-11-29-13-3a31-3a6.png)

   >[!NOTE]
   >
   >Currently, there are 10 [!DNL Facebook] events you can map Revenue Cycle Stages to:
   >
   >* Adds of Payment Info
   >* Adds to Cart
   >* Adds to Wish List
   >* Registrations Completed
   >* Checkouts Initiated
   >* Person
   >* Other
   >* Purchase
   >* Searches
   >* Content Views

1. Select the stage you want to map, then from the **[!UICONTROL Facebook Conversion]** drop-down, select the [!DNL Facebook] Event you want to map it to. Repeat this step to map all the stages in your RCM to offline conversion stages on [!DNL Facebook].

   ![](assets/1-1.png)

1. When you're done mapping, close the model.

   ![](assets/2.png)

1. Approve your model and you're done!

   ![](assets/image2016-11-29-15-3a6-3a30.png)

   Now, when Lead Ad leads reach the stages you mapped, the conversions are sent over to [!DNL Facebook] for reporting.

   >[!CAUTION]
   >
   >Check your [!DNL Facebook] account and ensure that all [ads are associated](https://www.facebook.com/business/url/?href=%2Fbusiness%2Fhelp%2Fwww%2F1776828022605281&cmsid&creative=link&creative_detail=advertiser-help-center&create_type&destination_cms_id&orig_http_referrer) to the Marketo Offline Conversions Event Set. If they're not, ad attribution may not work.

   >[!NOTE]
   >
   >Offline Conversion Data is sent from Marketo to [!DNL Facebook] several times daily.

>[!MORELIKETHIS]
>
>[Understanding [!DNL Facebook] Offline Conversions](/help/marketo/product-docs/demand-generation/facebook/understanding-facebook-offline-conversions.md)
