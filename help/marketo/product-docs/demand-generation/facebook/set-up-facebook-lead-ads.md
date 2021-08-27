---
unique-page-id: 11379622
description: Set Up Facebook Lead Ads - Marketo Docs - Product Documentation
title: Set Up Facebook Lead Ads
exl-id: 24cb74da-6b46-45de-ba4a-66e3d490afd7
---
# Set Up Facebook Lead Ads {#set-up-facebook-lead-ads}

Use [Facebook Lead Ads](https://www.facebook.com/business/a/lead-ads) to run ad campaigns in Facebook and generate leads for Marketo.

>[!NOTE]
>
>**Admin Permissions Required**

>[!AVAILABILITY]
>
>To get Facebook Lead Ads added to your instance, please contact your Customer Success Manager.

1. Go to Marketo **Admin**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. Go to **LaunchPoint**, click on **New,** and select **New Service**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. Enter a **Display Name** for your service, select the **Facebook Lead Ads** service from the drop-down, and click **Create**.

   ![](assets/image2016-11-29-10-3a51-3a47.png)

1. Open a new tab in the same browser and go to [facebook.com](https://www.facebook.com). Log in to Facebook using the account you want to use for the integration.

   >[!NOTE]
   >
   >The Facebook account will need access to all the Facebook business pages you want to pull lead ads from.

   ![](assets/image2016-11-29-10-3a52-3a29.png)

1. After you're logged into Facebook, return to Marketo and click **Authorize**.

   ![](assets/image2016-11-29-10-3a52-3a51.png)

1. If prompted, click **OK** to accept the Marketo app installation into Facebook.

   ![](assets/image2016-11-29-10-3a56-3a3.png)

1. You'll notice you are now authorized. Click **Next**.

   ![](assets/image2016-11-29-10-3a56-3a28.png)

1. Select the page(s) you want Marketo to pull Facebook Lead Ads from and click **Next**.

   >[!TIP]
   >
   >If you don't see a page you're expecting, ensure that the Facebook account used to authenticate is added to the page on Facebook and try again.

   ![](assets/image2016-11-29-10-3a58-3a36.png)

1. To accept default Facebook to Marketo field mappings, simply click **Create**.

   >[!TIP]
   >
   >By modifying the mappings, you can customize where the lead ads data is stored in Marketo. You can also [pull in data from Lead Ads Custom Questions](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads/map-custom-fields-to-marketo.md).

   >[!CAUTION]
   >
   >Marketo doesn't support mapping two Facebook fields to a single Marketo field, only 1 to 1. If you map 2 to 1, leads may fail to enter the Marketo system.

   ![](assets/image2016-11-29-11-3a0-3a2.png)

   Nicely done! Leads will start flowing into Marketo as you run successful Facebook Lead Ad campaigns.

   ![](assets/image2016-11-29-12-3a32-3a54.png)

>[!MORELIKETHIS]
>
>* [Assign/Remove Permissions in Leads Access Manager (Facebook)](https://www.facebook.com/business/help/540596413257598?id=735435806665862)
>* [Use Lead Ads Filters and Triggers in a Smart Campaign](/help/marketo/product-docs/demand-generation/facebook/use-lead-ads-filters-and-triggers-in-a-smart-campaign.md)
>* [Map Custom Fields to Marketo](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads/map-custom-fields-to-marketo.md)
