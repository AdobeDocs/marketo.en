---
description: How Do I Prevent Self Views - Marketo Docs - Product Documentation
title: How Do I Prevent Self Views
exl-id: 52de102f-6c6c-4663-9725-aae2f620d5bb
---
# How Do I Prevent Self Views? {#how-do-i-prevent-self-views}

Getting false positives on your view tracking can lead to reporting inconsistencies. This often occurs when users of [!DNL Marketo Sales] accidentally invoke the tracking pixel from their email client (we call this a self-view). Below are a few tips on significantly reducing and even eliminating self-views.

## Web ([!DNL Outlook] Web App and Gmail) {#web-outlook-web-app-and-gmail}

[!DNL Marketo Sales] will store a cookie in your browser to prevent views from being tracked when opening your emails from [!DNL Outlook] Web App and Gmail. If you are still receiving self-views, we recommend doing the following:

* Ensure that you have cookies enabled on your computer.

* If you're using a new computer or mobile device, make sure you've logged in to the web application. This will allow us to recognize your computer/device going forward.

## Desktop (Windows) {#desktop-windows}

Views are tracked by downloading a small invisible image pixel in your email client. You can significantly lower the amount of self-views in [!DNL Outlook] by disabling images to be automatically downloaded. Below are the steps how.

1. In Outlook, click **[!UICONTROL File]** in the menu bar.

   ![](assets/how-do-i-prevent-self-views-1.png)

1. Click **[!UICONTROL Options]**.

   ![](assets/how-do-i-prevent-self-views-2.png)

1. In the [!DNL Outlook] Options dialog box, click **[!UICONTROL Trust Center]**.

   ![](assets/how-do-i-prevent-self-views-3.png)

1. Under Microsoft [!DNL Outlook] Trust Center, click **[!UICONTROL Trust Center Settings]**.

   ![](assets/how-do-i-prevent-self-views-4.png)

1. Click [!UICONTROL Automatic Download] in the menu on the left, and select the **[!UICONTROL Don't download pictures automatically in HTML email or RSS items]** check box.

   ![](assets/how-do-i-prevent-self-views-5.png)

1. Click **[!UICONTROL OK]** in the [!UICONTROL Trust Center] dialog box.

   ![](assets/how-do-i-prevent-self-views-6.png)

1. Click **[!UICONTROL OK]** in the [!DNL Outlook] Options dialog box.

   ![](assets/how-do-i-prevent-self-views-7.png)

## Desktop (Mac) {#desktop-mac}

Views are tracked by downloading a small invisible image pixel in your email client. You can significantly lower the amount of self-views in [!DNL Outlook] by disabling images to be automatically downloaded. Below are the steps how.

1. In [!DNL Outlook], click **[!UICONTROL Outlook]** in the menu bar and select **[!UICONTROL Preferences]**.

   ![](assets/how-do-i-prevent-self-views-8.png)

1. Under [!UICONTROL Email], choose **[!UICONTROL Reading]**.

   ![](assets/how-do-i-prevent-self-views-9.png)

1. Under [!UICONTROL Security], click the **[!UICONTROL Never]** radio button.

   ![](assets/how-do-i-prevent-self-views-10.png)
