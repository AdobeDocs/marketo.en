---
unique-page-id: 10092925
description: Preview and Test a Web Campaign - Marketo Docs - Product Documentation
title: Preview and Test a Web Campaign
exl-id: 6cc4ebd8-0d39-4a7d-bc3d-e8cd18157470
---
# Preview and Test a Web Campaign {#preview-and-test-a-web-campaign}

This article shows you different ways to preview a web campaign, and also how to test it using a sandbox segment live on your website.

## Preview a Web Campaign on the Creation Page {#preview-a-web-campaign-on-the-creation-page}

1. Go to **Web Campaigns**.

   ![](assets/image2016-8-18-15-3a59-3a35.png)

1. Click **Create New Web Campaign** or the icon to edit an existing campaign.

   ![](assets/create-new-or-edit-web-campaign.png)

1. In Preview on site, add the page URL and click **Preview**. A new window/tab opens showing the campaign preview.

   ![](assets/three-1.png)

   >[!TIP]
   >
   >Click **Share** to open an email with a fixed URL of the campaign preview.

   >[!NOTE]
   >
   >You also have the option of installing a browser plug-in (either [Chrome](https://chrome.google.com/webstore/detail/marketo-web-personalizati/ldiddonjplchallbngbccbfdfeldohkj) or [Firefox](https://rtp-static.marketo.com/rtp/libs/mwp-0.0.0.8.xpi)) for the best experience previewing your campaign. See the section below.

## Preview a Web Campaign on the Creation Page Using the Browser Plug-In {#preview-a-web-campaign-on-the-creation-page-using-the-browser-plug-in}

1. Follow steps 1 & 2 from the section above.

1. Click the link to the browser plug-in (in this case we're using Chrome).

   ![](assets/4-1.png)

1. A new window/tab opens. Click **Add to Chrome**.

   ![](assets/five.png)

1. Click **Add Extension**.

   ![](assets/six.png)

1. Go back to Marketo. Add the page URL and click **Preview**.

   ![](assets/seven.png)

1. A new window/tab opens which allows you to preview how your campaign looks on a desktop, phone, or tablet.

   ![](assets/campaign-preview.png)

## Preview a Web Campaign on the Web Campaigns Page {#preview-a-web-campaign-on-the-web-campaigns-page}

1. While looking at the listing of your web campaigns, simply choose a campaign and click the **Preview** icon.

   ![](assets/web-campaigns-1-preview-hand.png)

   Easy!

## Preview a Web Campaign on your Website {#preview-a-web-campaign-on-your-website}

Create a sandbox segment and campaign.

1. Go to **Segments**.

   ![](assets/new-dropdown-segments-hand.jpg)

1. Click **Create New**.

   ![](assets/image2015-9-10-10-3a42-3a39.png)

1. Name the segment.

1. Under Behavioral, drag Include Pages onto the canvas. Add the value &#42;sandbox=1&#42;. Click **Save & Define Campaign**.

   ![](assets/segment.png)

1. On the Set Web Campaign page, change the Target Segment to the sandbox segment by selecting it from the list.

   ![](assets/set-web-campaign-target-segment.jpg)

1. Complete the campaign creative and Click **Launch**.

   ![](assets/click-launch.jpg)

1. Go to your website, add the URL parameter "?sandbox=1" at the end of the URL. Example: `www.marketo.com?sandbox=1`.

1. See the campaign react on your website.

>[!NOTE]
>
>Campaigns react only once during a visitor session. To see the campaign again, clear your browser cookies.

>[!NOTE]
>
>Redirect campaigns cannot be previewed. The only way to test them is by using a sandbox segment (that targets by specific pages - &#42;sandbox=redirect&#42;)
