---
unique-page-id: 11379622
description: Set up Facebook Lead Ads - Marketo Docs - Product Documentation
title: Set up Facebook Lead Ads
exl-id: 24cb74da-6b46-45de-ba4a-66e3d490afd7
feature: Integrations
---
# Set up Facebook Lead Ads {#set-up-facebook-lead-ads}

Use [Facebook Lead Ads](https://www.facebook.com/business/ads/ad-objectives/lead-generation){target="_blank"} to run ad campaigns in Facebook and generate leads for Marketo.

>[!NOTE]
>
>**Admin Permissions Required**

>[!AVAILABILITY]
>
>To get Facebook Lead Ads added to your instance, please contact the Adobe Account Team (your Account Manager).

1. In Marketo Engage, go to the **Admin** area.

   ![](assets/set-up-facebook-lead-ads-1.png)

1. Go to **LaunchPoint**, click the **New** drop-down and select **New Service**.

   ![](assets/set-up-facebook-lead-ads-2.png)

1. Enter a **Display Name** for your service, select the **Facebook Lead Ads** service from the drop-down, and click **Create**.

   ![](assets/set-up-facebook-lead-ads-3.png)

1. Open a new tab in the same browser and go to [facebook.com](https://www.facebook.com){target="_blank"}. Log in to Facebook using the account you want to use for the integration.

   >[!NOTE]
   >
   >The Facebook account will need access to all the Facebook business pages you want to pull lead ads from.

   ![](assets/set-up-facebook-lead-ads-4.png)

1. After you're logged into Facebook, return to Marketo and click **Authorize**.

   ![](assets/set-up-facebook-lead-ads-5.png)

1. If prompted, click **OK** to accept the Marketo app installation into Facebook.

   ![](assets/set-up-facebook-lead-ads-6.png)

1. You'll notice you are now authorized. Click **Next**.

   ![](assets/set-up-facebook-lead-ads-7.png)

1. Select the page(s) you want Marketo to pull Facebook Lead Ads from and click **Next**.

   >[!TIP]
   >
   >If you don't see a page you're expecting, ensure that the Facebook account used to authenticate is added to the page on Facebook and try again.

   ![](assets/set-up-facebook-lead-ads-8.png)

1. To accept default Facebook to Marketo field mappings, simply click **Create**.

   >[!TIP]
   >
   >By modifying the mappings, you can customize where the lead ads data is stored in Marketo. You can also [pull in data from Lead Ads Custom Questions](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads/map-custom-fields-to-marketo.md){target="_blank"}.

   >[!CAUTION]
   >
   >Marketo doesn't support mapping two Facebook fields to a single Marketo field, only 1 to 1. If you map 2 to 1, leads may fail to enter the Marketo system.

   ![](assets/set-up-facebook-lead-ads-9.png)

   Nicely done! Leads will start flowing into Marketo as you run successful Facebook Lead Ad campaigns.

   ![](assets/set-up-facebook-lead-ads-10.png)

>[!MORELIKETHIS]
>
>* [Assign/Remove Permissions in Leads Access Manager (Facebook)](https://www.facebook.com/business/help/540596413257598?id=735435806665862){target="_blank"}
>* [Use Lead Ads Filters and Triggers in a Smart Campaign](/help/marketo/product-docs/demand-generation/facebook/use-lead-ads-filters-and-triggers-in-a-smart-campaign.md){target="_blank"}
>* [Map Custom Fields to Marketo](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads/map-custom-fields-to-marketo.md){target="_blank"}
