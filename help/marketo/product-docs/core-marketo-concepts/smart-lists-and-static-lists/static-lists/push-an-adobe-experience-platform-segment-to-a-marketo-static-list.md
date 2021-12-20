---
description: Push an Adobe Experience Platform Segment to a Marketo Static List - Marketo Docs - Product Documentation
title: Push an Adobe Experience Platform Segment to a Marketo Static List
exl-id: 8df11bf4-06f4-4927-8dfb-954414fce6dc
---
# Push an Adobe Experience Platform Segment to a Marketo Static List {#push-an-adobe-experience-platform-segment-to-a-marketo-static-list}

This feature allows you to push segments located in your Adobe Experience Platform over to Marketo in the form of a static list.

>[!PREREQUISITES]
>
>* [Create an API User](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md) in Marketo.
>* Then, go to **Admin** > **Launchpoint**. Find the name of the role you just created and click **View Details**. Copy and save the info in **Client ID** and **Client Secret**, as you'll need it for this feature.

1. Log in to [Adobe Experience Platform](https://experience.adobe.com/).

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-1.png)

1. Click the grid icon and select **Experience Platform**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-2.png)

1. In the left nav, click **Destinations**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-3.png)

1. Click **Catalog**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-4.png)

1. Find the Marketo Engage tile and click **Activate Segments**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-5.png)

1. Click **Configure New Destination**.


1. Under Account Type, click the **New Account** radio button. Enter your Marketo credentials and click **Connect to Destination**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-6.png)

   >[!NOTE]
   >
   >You can find your Munchkin ID by going to **Admin** > **Munchkin** (it's also part of your Marketo URL once logged in). Client ID/Secret you should have from following the prerequisites at the top of this article.

1. "Connected" should appear below your credentials. Click **Next** in the upper right-hand corner.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-7.png)

1. Enter a **Name** and an _optional_ Description. Click **Create Destination**.

   >[!NOTE]
   >
   >Choosing something from Marketing Actions is also optional. Marketo doesn't leverage that information at this time, but likely will soon.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-8.png)

1. Click **Next**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-9.png)

1. Choose your desired segment and click **Next**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-10.png)

   >[!NOTE]
   >
   >If you choose multiple segments here, you'll have to map each segment to a specified static list in the Segment Schedule tab.

1. Click **Add New Mapping**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-11.png)

1. Click the cursor icon.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-12.png)

1. Choose either the **Select Attributes** or **Select Identity Namespace** radio button (in this example, we're choosing Attributes).

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-13.png)

   >[!NOTE]
   >
   >If you chose **Select Identity Namespace**, after making your selection, skip to Step 15.

1. Choose the relevant field that contains the email address that identifies the user. Click **Select** when done.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-14.png)

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-15.png)

   >[!NOTE]
   >
   >The example we've chosen may look much different than your selection.

1. Click the mapping icon.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-16.png)

1. Choose **Select Identity Namespace**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-17.png)

   >[!IMPORTANT]
   >
   >Mapping attributes is optional. Mapping Email and/or ECID from the **Identity Namespace** tab is the most important thing to do to ensure the person is matched in Marketo. Mapping Email will ensure the highest match rate.

1. Choose between ECID or Email. In this example we're choosing **Email**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-18.png)

1. Click **Next**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-19.png)

   >[!NOTE]
   >
   >Identities are used to look for matches in Marketo. If a match is found, the person is added to the static List. If a match is not found, those people are dropped (i.e., not created in Marketo).

1. _In Marketo_, create a static list, or find and select one you've already created. Copy the mapping ID from the end of the URL.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-20.png)

   >[!NOTE]
   >
   >For best results, make sure the list you reference in Marketo is empty.

1. Back in Adobe Experience Platform, enter the ID you just copied. Choose your Start Date. People will continuously sync until the chosen end date. For an indefinite sync, leave the end date blank. Click **Next** when done.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-21.png)

1. Confirm your changes and click **Finish**.

   ![](assets/push-an-adobe-experience-platform-segment-to-a-marketo-static-list-22.png)
