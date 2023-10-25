---
description: Push an Adobe Experience Platform Segment to a Marketo Static List - Marketo Docs - Product Documentation
title: Push an Adobe Experience Platform Segment to a Marketo Static List
exl-id: 8df11bf4-06f4-4927-8dfb-954414fce6dc
feature: Static Lists
---
# Push an Adobe Experience Platform Segment to a Marketo Static List {#push-an-adobe-experience-platform-segment-to-a-marketo-static-list}

This feature allows you to push segments located in your Adobe Experience Platform over to Marketo Engage in the form of a static list.

>[!PREREQUISITES]
>
>* [Edit the API Role](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md#edit-an-existing-role){target="_blank"} to make sure it has the **Read-Write Person** permission (found under the Access API drop-down).
>* [Create an API User](/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md){target="_blank"} in Marketo.
>* Go to **[!UICONTROL Admin]** > **[!UICONTROL Launchpoint]**. Find the name of the role you just created and click **[!UICONTROL View Details]**. Copy and save the info in **[!UICONTROL Client ID]** and **[!UICONTROL Client Secret]**, as you could need it for Step 7.
>* In Marketo, create a static list, or find and select one you've already created. You'll need its ID.

1. Log in to [Adobe Experience Platform](https://experience.adobe.com/){target="_blank"}.

   ![](assets/push-an-adobe-experience-platform-segment-1.png)

1. Click the grid icon and select **[!UICONTROL Experience Platform]**.

   ![](assets/push-an-adobe-experience-platform-segment-2.png)

1. In the left nav, click **[!UICONTROL Destinations]**.

   ![](assets/push-an-adobe-experience-platform-segment-3.png)

1. Click **[!UICONTROL Catalog]**.

   ![](assets/push-an-adobe-experience-platform-segment-4.png)

1. Find the Marketo Engage tile and click **[!UICONTROL Activate]**.

   ![](assets/push-an-adobe-experience-platform-segment-5.png)

1. Click **[!UICONTROL Configure New Destination]**.

   ![](assets/push-an-adobe-experience-platform-segment-6.png)


1. Under Account Type, select the Existing or New Account radio button (in this example, we're choosing **[!UICONTROL Existing Account]**). Click the Select Account icon.

   ![](assets/push-an-adobe-experience-platform-segment-7.png)

   >[!NOTE]
   >
   >If you are choosing New Account, you can find your Munchkin ID by going to **[!UICONTROL Admin]** > **[!UICONTROL Munchkin]** (it's also part of your Marketo URL once logged in). Client ID/Secret you should have from following the prerequisites at the top of this article.

1. Choose the destination account and click **[!UICONTROL Select]**.

   ![](assets/push-an-adobe-experience-platform-segment-8.png)

1. Enter a Destination **[!UICONTROL Name]** and an optional Description. Click the Person Creation drop-down and choose "Match Existing Marketo People and Create Missing People in Marketo" _or_ "Match Existing Marketo People Only" (in this example we're choosing the former). You must also choose a **[!UICONTROL Workspace]**.

   ![](assets/push-an-adobe-experience-platform-segment-9.png)

   >[!NOTE]
   >
   >If you choose "Match Existing Marketo People Only" you'll only need to map the Email and/or ECID, so you can skip Steps 13-16.

1. This section is optional. Click **[!UICONTROL Create]** to skip.

   ![](assets/push-an-adobe-experience-platform-segment-10.png)

1. Select the destination you created and click **[!UICONTROL Next]**.

   ![](assets/push-an-adobe-experience-platform-segment-11.png)

1. Choose the segment you want to send to Marketo and click **[!UICONTROL Next]**.

   ![](assets/push-an-adobe-experience-platform-segment-12.png)

   >[!NOTE]
   >
   >If you choose multiple segments, you'll have to map each segment to a specified static list in the Segment Schedule tab.

   >[!IMPORTANT]
   >
   >After a segment has been activated to the Marketo destination for the first time, backfilling profiles that already existed in the segment prior to Marketo destination activation can take _up to 24 hours_. Going forward, any time profiles are added to the segment, they'll be added to Marketo immediately.

1. Click **[!UICONTROL Add New Mapping]**.

   ![](assets/push-an-adobe-experience-platform-segment-13.png)

1. Click the mapping icon.

   ![](assets/push-an-adobe-experience-platform-segment-14.png)

1. Choose your desired attribute(s) and click **[!UICONTROL Select]**. In this example, we're choosing first name, last name, and email address.

   ![](assets/push-an-adobe-experience-platform-segment-15.png)

   >[!NOTE]
   >
   >You can map attributes from Experience Platform to any of the attributes that your organization has access to in Marketo Engage. Use the [Describe API request](https://developers.marketo.com/rest-api/lead-database/leads/#describe){target="_blank"} to retrieve attribute fields that your organization has access to.

1. Map the Last Name and Company Name by clicking **[!UICONTROL Add New Mapping]** again and repeating Step 15 twice, choosing **[!UICONTROL lastName]** and then **[!UICONTROL companyName]**.

   ![](assets/push-an-adobe-experience-platform-segment-16.png)

1. Now it's time to map the email address. Click **[!UICONTROL Add New Mapping]** again.

   ![](assets/push-an-adobe-experience-platform-segment-17.png)

1. Click the mapping icon.

   ![](assets/push-an-adobe-experience-platform-segment-18.png)

1. Click the Select Identity Namespace radio button, choose **[!UICONTROL Email]**, then click **[!UICONTROL Select]**.

   ![](assets/push-an-adobe-experience-platform-segment-19.png)

   >[!IMPORTANT]
   >
   >Mapping Email and/or ECID from the **[!UICONTROL Identity Namespace]** tab is the most important thing to do to ensure the person is matched in Marketo. Mapping Email will ensure the highest match rate.

1. Now it's time to choose the source fields. For email, click the cursor icon.

   ![](assets/push-an-adobe-experience-platform-segment-20.png)

1. Click the Select Identity Namespace radio button, find and select **[!UICONTROL Email]**, then click **[!UICONTROL Select]**.

   ![](assets/push-an-adobe-experience-platform-segment-21.png)

1. To choose the Company Name source field, click the cursor icon in its row.

   ![](assets/push-an-adobe-experience-platform-segment-22.png)

1. Leave the Select Attributes radio button checked. Search for "company" and select **[!UICONTROL companyName]**, then click **[!UICONTROL Select]**.

   ![](assets/push-an-adobe-experience-platform-segment-23.png)

1. Map the source fields for Last Name and First Name by clicking the cursor icon for each and repeating Step 23 twice, choosing **[!UICONTROL lastName]** and then **[!UICONTROL firstName]**.

   ![](assets/push-an-adobe-experience-platform-segment-24.png)

1. Click **[!UICONTROL Next]**.

   ![](assets/push-an-adobe-experience-platform-segment-25.png)

1. Review your changes and click **[!UICONTROL Finish]**.

   ![](assets/push-an-adobe-experience-platform-segment-26.png)
