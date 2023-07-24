---
unique-page-id: 4720257
description: Add Facebook Custom Audiences as a LaunchPoint Service - Marketo Docs - Product Documentation
title: Add Facebook Custom Audiences as a LaunchPoint Service
exl-id: 5c5b5c80-fd0f-482a-8163-6eef3dbcb236
feature: Integrations
---
# Add Facebook Custom Audiences as a LaunchPoint Service {#add-facebook-custom-audiences-as-a-launchpoint-service}

>[!NOTE]
>
>**Admin Permissions Required**

With this integration you can send audience data from Marketo static and smart lists to Facebook to be used as Custom Audiences in Facebook Ad Campaigns. Here's how to set it up.

1. Go to Marketo **Admin**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. Go to **LaunchPoint**, click on **New** and select **New Service**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. Enter a **Display Name** for your service and select the **Facebook Custom Audiences** service from the **Service** drop-down.

   ![](assets/image2016-11-29-12-3a51-3a8.png)

1. Open a new tab in the same browser and go to [facebook.com](https://www.facebook.com/). Log in to Facebook using the account you want to use for the integration.

   >[!CAUTION]
   >
   >In order for Marketo to send audiences across multiple Ad Manager Accounts, the Facebook user you authorize in the following steps needs to have access to *all* of these accounts.

   ![](assets/image2016-11-29-10-3a52-3a29.png)

1. After you're logged into Facebook, return to Marketo. Click **Authorize**.

   ![](assets/fb-custom-authorize-hand.png)

   >[!NOTE]
   >
   >You _must_ use a Facebook Business Manager account in order for your Custom Audiences integration to work. To learn how to set up a Business Manager account, refer to [Facebook Help](https://www.facebook.com/business/help/1710077379203657).

1. If prompted, click **OK** to accept the Marketo app installation into Facebook.

   ![](assets/image2016-11-29-10-3a56-3a3.png)

1. You're now authorized! Select a matching mode and click **Create**.

   >[!NOTE]
   >
   >**Basic Matching** uses only email addresses. **Advanced Matching** uses seven additional fields, which increases the match rate, for more conversion. However, if your company's privacy policy doesn't permit sharing additional fields, or if your data doesn't include them, select Basic Matching.

   ![](assets/fb-custom-adv-matching-hands.png)

   Great job! You can now go over to any static or smart list in Marketo and send audience data over to Facebook.

   >[!CAUTION]
   >
   >Oh, before you go, be sure to [Accept Facebook's Custom Audiences Terms](https://www.facebook.com/ads/manage/customaudiences/tos.php) within your Facebook account! Without doing this, the audience updates will fail.

>[!MORELIKETHIS]
>
>* [Create a Custom Audience in Facebook](/help/marketo/product-docs/demand-generation/facebook/create-a-custom-audience-in-facebook.md)
>
>* [Set Up Facebook Lead Ads](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-lead-ads.md)
