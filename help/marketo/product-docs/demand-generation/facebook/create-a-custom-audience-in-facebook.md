---
unique-page-id: 4720275
description: Create a Custom Audience in Facebook - Marketo Docs - Product Documentation
title: Create a Custom Audience in Facebook
exl-id: a2c8d89c-16b3-44f6-a2c6-c52fe78ab39c
---
# Create a Custom Audience in [!DNL Facebook] {#create-a-custom-audience-in-facebook}

>[!PREREQUISITES]
>
>* [Add [!DNL Facebook] Custom Audiences as a LaunchPoint Service](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-facebook-custom-audiences-as-a-launchpoint-service.md){target="_blank"} in the Admin section.
>* [Accept [!DNL Facebook]'s Custom Audiences Terms](https://www.facebook.com/ads/manage/customaudiences/tos.php){target="_blank"} within your [!DNL Facebook] account.

>[!TIP]
>
>Learn more about [custom audiences in [!DNL Facebook]](https://www.facebook.com/help/341425252616329){target="_blank"}.

1. Find and select the smart or static list that contains the leads you want to create the audience from.

   ![](assets/create-a-custom-audience-in-facebook-1.png)

1. Select the **[!UICONTROL Leads]** tab, then click on the **Send Via Ad Bridge** icon at the bottom.

   ![](assets/create-a-custom-audience-in-facebook-2.png)

1. Select **[!UICONTROL Facebook]** and click **[!UICONTROL Next]**.

   ![](assets/create-a-custom-audience-in-facebook-3.png)

1. Click the **[!UICONTROL Audience]** drop-down and select **[!UICONTROL + New Audience]**.

   ![](assets/create-a-custom-audience-in-facebook-4.png)

   >[!IMPORTANT]
   >
   >The Facebook API allows up to 500 custom audiences per Facebook ad account.

1. Type in an **[!UICONTROL Audience Name]**. Click **[!UICONTROL Update]**.

   ![](assets/create-a-custom-audience-in-facebook-5.png)

   >[!NOTE]
   >
   >If you have multiple [!DNL Facebook] Ad Accounts, you will see an additional drop-down, allowing you to choose which Ad Account this audience is created in.

   >[!TIP]
   >
   >Want to swap a new audience with an existing one that's currently associated with an ad set or group? Select the **[!UICONTROL Replace an existing audience]** check box. Doing this will **not** delete the audience being replaced.

1. When done, the status dialog will update.

   ![](assets/create-a-custom-audience-in-facebook-6.png)

   And that's it! In Facebook you'll see the new audience in **Ads Manager** > **Audiences**.

   ![](assets/create-a-custom-audience-in-facebook-7.png)

   >[!NOTE]
   >
   >All lists that you push over to [!DNL Facebook] become static. Smart lists in Marketo will not auto-update the audience list in [!DNL Facebook] to reflect any changes made after the transfer.

   >[!TIP]
   >
   >See the [[!DNL Facebook] learning path for Marketo customers](https://facebook.exceedlms.com/student/enrollments/create_enrollment_from_token/BF9TqSaCvM73PP4ScjhCm4fi){target="_blank"}. It covers everything you need to know, from creating a [!DNL Facebook] page to targeting your [!DNL Facebook] ads using Marketo's ad network integrations.

   >[!MORELIKETHIS]
   >
   >[Add Leads to a Custom Audience in [!DNL Facebook]](/help/marketo/product-docs/demand-generation/facebook/add-leads-to-a-custom-audience-in-facebook.md)
