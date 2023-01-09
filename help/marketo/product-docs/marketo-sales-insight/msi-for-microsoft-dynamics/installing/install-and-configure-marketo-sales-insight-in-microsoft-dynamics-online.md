---
unique-page-id: 37355602
description: Install and Configure Marketo Sales Insight in Microsoft Dynamics Online - Marketo Docs - Product Documentation
title: Install and Configure Marketo Sales Insight in Microsoft Dynamics Online
exl-id: 3b58b109-96f9-427e-be5c-a8db270ffe69
---
# Install and Configure [!DNL Marketo Sales Insight] in [!DNL Microsoft Dynamics Online] {#install-and-configure-marketo-sales-insight-in-microsoft-dynamics-online}

[!DNL Marketo Sales Insight] is a fantastic tool for giving your sales team a "window" into the wealth of data the Marketing team has. Here's how to install and configure it in [!DNL Microsoft Dynamics Online].

>[!PREREQUISITES]
>
>Complete your Marketo-Microsoft integration.
>
>[Download the correct solution](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) for your version of [!DNL Microsoft Dynamics CRM].

## Import Solution {#import-solution}

>[!NOTE]
>
>If you're using the Unified Interface, prior to Step 1 below, click the Settings icon in the top-right corner and select **[!UICONTROL Advanced Settings]**.

1. Under Microsoft Dynamics CRM click **[!UICONTROL Settings]**.

   ![](assets/image2014-12-12-9-3a4-3a56-1.png)

1. Under Settings, click **[!UICONTROL Customizations]**.

   ![](assets/image2015-4-29-14-3a22-3a1-1.png)

1. Click **[!UICONTROL Solutions]**.

   ![](assets/image2014-12-12-9-3a5-3a17-1.png)

   >[!NOTE]
   >
   >You should already have installed and configured the Marketo solution before moving forward.

1. Click **[!UICONTROL Import]**.

   ![](assets/image2014-12-12-9-3a5-3a27-1.png)

1. In the new window, click **[!UICONTROL Browse]**.

   ![](assets/image2014-12-12-9-3a5-3a36-1.png)

1. On your computer, find and install the solution you just downloaded.

1. Click **[!UICONTROL Next]**.

   ![](assets/seven.png)

1. The solution will upload. You can view the package contents if you like. Click **[!UICONTROL Next]**.

   ![](assets/image2014-12-12-9-3a6-3a10-1.png)

1. Make sure to leave the box checked and click **[!UICONTROL Import]**.

   ![](assets/image2014-12-12-9-3a6-3a19-1.png)

1. Feel free to download the log file, then click **[!UICONTROL Close]**.

   ![](assets/image2014-12-12-9-3a6-3a29-1.png)

1. Awesome! You should see the solution now. If it's not there, refresh your screen.

   ![](assets/eleven.png)

1. Click **[!UICONTROL Publish Customization]**.

   >[!NOTE]
   >
   >Make sure to enable the Global [!DNL MS Dynamics] sync.

## Connect Marketo and [!DNL Sales Insight] {#connect-marketo-and-sales-insight}

Let's tie your Marketo instance to [!DNL Sales Insight] in [!DNL Dynamics]. Here's how:

>[!NOTE]
>
>**Admin Permissions Required**

1. Log in Marketo and go to the **[!UICONTROL Admin]** section.

   ![](assets/image2014-12-12-9-3a6-3a50-1.png)

1. Under the [!UICONTROL Sales Insight] section, click **[!UICONTROL Edit API Configuration]**.

   ![](assets/image2014-12-12-9-3a7-3a0-1.png)

1. Copy the **[!UICONTROL Marketo Host]**, **[!UICONTROL API URL]**, and **[!UICONTROL API User Id]** for use in a later step. Enter an API Secret Key of your choice and click **[!UICONTROL Save]**.

   >[!CAUTION]
   >
   >Don't use an ampersand (&) in your API Secret Key.

   ![](assets/image2014-12-12-9-3a7-3a9-1.png)

   >[!NOTE]
   >
   >The following fields must be synced with Marketo for _both Lead and Contact_ for [!DNL Sales Insight] to work:
   >
   >* Priority
   >* Urgency
   >* Relative Score
   >
   >If any of these fields are missing, you will see an error message in Marketo with the name of the missing fields. To fix this, perform [this procedure](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/required-fields-for-syncing-marketo-with-dynamics.md).

1. Back in [!DNL Microsoft Dynamics], go to **[!UICONTROL Settings]**.

   ![](assets/image2014-12-12-9-3a7-3a25-1.png)

1. Under **[!UICONTROL Settings]**, click **[!UICONTROL Marketo API Config]**.

   ![](assets/image2014-12-12-9-3a7-3a34-1.png)

1. Click **[!UICONTROL New]**.

   ![](assets/image2014-12-12-9-3a8-3a8-1.png)

1. Enter the information that you took from Marketo earlier and click **[!UICONTROL Save]**.

   ![](assets/image2014-12-12-9-3a8-3a17-1.png)

## Enable Sync {#enable-sync}

1. In Marketo, click **[!UICONTROL Admin]**.

   ![](assets/enable-one.png)

1. Under Integration, select **[!UICONTROL Microsoft Dynamics]**.

   ![](assets/enable-two.png)

1. Click **[!UICONTROL Enable Sync]**.

   ![](assets/enable-three.png)

1. Click **[!UICONTROL Edit]** next to [!UICONTROL Field Sync Details].

   ![](assets/enable-four.png)

1. This will _automatically_ select MSI fields that were previously disabled ([!UICONTROL Urgency], [!UICONTROL Relative Score], and [!UICONTROL Priority]). Simply click **[!UICONTROL Save]** to to start syncing data.

   ![](assets/enable-five.png)

## Set User Access {#set-user-access}

Finally, you have to give specific users access to use [!DNL Marketo Sales Insight].

1. Go to **[!UICONTROL Settings]**.

   ![](assets/image2014-12-12-9-3a8-3a34-1.png)

1. Go to **[!UICONTROL Security]**.

   ![](assets/image2015-4-29-14-3a56-3a33-1.png)

1. Click **[!UICONTROL Users]**.

   ![](assets/image2015-4-29-14-3a57-3a46-1.png)

1. Select the users you want to give access to [!DNL Sales Insight] to and click **[!UICONTROL Manage Roles]**.

   ![](assets/image2015-4-29-14-3a59-3a31-1.png)

1. Select the [!DNL Marketo Sales Insight] role and click **[!UICONTROL OK]**.

   ![](assets/image2014-12-12-9-3a9-3a22-1.png)

   And you should be all done! Finally, to test, log into [!DNL Dynamics] as a user who has access to [!DNL Marketo Sales Insight] and look at a lead or contact.

   ![](assets/image2015-4-29-15-3a2-3a27-1.png)

>[!MORELIKETHIS]
>
>[Setting up Stars and Flames for Lead/Contact Records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
