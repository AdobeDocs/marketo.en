---
unique-page-id: 14352540
description: Preventing Self Views - Marketo Docs - Product Documentation
title: Preventing Self Views
exl-id: c18715fc-4ca2-4a6b-8f63-a9406f30c0d8
---
# Preventing Self Views {#preventing-self-views}

## Overview {#overview}

Getting false positives on your view tracking can lead to reporting inconsistencies. This often occurs when users of MSC accidentally invoke the tracking pixel from their email client (we call this a self-view). Below are a few tips on significantly reducing and even eliminating self-views.

## Web ([!DNL Outlook Web App] and Gmail) {#web-outlook-web-app-and-gmail}

[!DNL Sales Connect] will store a cookie in your browser to prevent views from being tracked when opening your emails from Outlook Web App and Gmail. If you are still receiving self-views, we recommend doing the following:

* Ensure that you have cookies enabled on your computer.

* If you're using a new computer or mobile device, make sure you've logged in to the web application. This will allow us to recognize your computer/device going forward.

## Desktop (Windows) {#desktop-windows}

Views are tracked by downloading a small invisible image pixel in your email client. You can significantly lower the amount of self-views in [!DNL Outlook] by disabling images to be automatically downloaded. Below are the steps how.

1. In [!DNL Outlook], click **[!UICONTROL File]** in the menu bar.

   ![](assets/win-1.png)

1. Click **[!UICONTROL Options]**.

   ![](assets/win-2.png)

1. In the [!DNL Outlook] Options dialog box, click **[!UICONTROL Trust Center]**.

   ![](assets/win-3.png)

1. Under [!UICONTROL Microsoft Outlook Trust Center], click **[!UICONTROL Trust Center Settings]**.

   ![](assets/win-4.png)

1. Click [!UICONTROL Automatic Download] in the menu on the left, and select the **[!UICONTROL Don't download pictures automatically in HTML email or RSS items]** check box.

   ![](assets/win-5.png)

1. Click **[!UICONTROL OK]** in the [!UICONTROL Trust Center] dialog box.

   ![](assets/win-6.png)

1. Click **[!UICONTROL OK]** in the [!DNL Outlook] Options dialog box.

   ![](assets/win-6.png)

## Desktop (Mac) {#desktop-mac}

Views are tracked by downloading a small invisible image pixel in your email client. You can significantly lower the amount of self-views in [!DNL Outlook] by disabling images to be automatically downloaded. Below are the steps how.

1. In [!DNL Outlook], click **[!UICONTROL Outlook]** in the menu bar and select **[!UICONTROL Preferences]**.

   ![](assets/mac-1.png)

1. Under [!UICONTROL Email], choose **[!UICONTROL Reading]**.

   ![](assets/mac-2.png)

1. Under [!UICONTROL Security], click the **[!UICONTROL Never]** radio button.

   ![](assets/mac-3.png)
