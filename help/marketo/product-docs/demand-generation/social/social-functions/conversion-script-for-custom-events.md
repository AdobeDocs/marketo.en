---
unique-page-id: 2950561
description: Conversion Script for Custom Events - Marketo Docs - Product Documentation
title: Conversion Script for Custom Events
exl-id: 202b7e66-af83-42fd-8067-a5808eba7c32
feature: Social
---
# Conversion Script for Custom Events {#conversion-script-for-custom-events}

You define the fulfillment goal when creating a referral offer. If the action that counts towards the goal is a specific event on your own web page, you can use a conversion script to call our JavaScript API.

>[!IMPORTANT]
>
>On July 31, 2024, we began the process of deprecating this feature. You won't be able to create new assets. Existing assets will continue to work through January 31, 2025. [Learn more](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

## Retrieve the Conversion Script {#retrieve-the-conversion-script}

1. Within the referral offer editor, click **Offer Details** and then select **Customer JavaScript Event** from the fulfillment goal drop-down.

   ![](assets/image2015-4-20-17-3a22-3a15.png)

1. Copy the top script in the grey box and place it on your webpage within the `<body>` tags. The bottom script is placed within the `<header>` tags.

   ![](assets/image2015-4-20-17-3a29-3a7.png)

   >[!NOTE]
   >
   >Remember to copy and paste both scripts if they are going on a non-Marketo website.

## Retrieve the Loader Script {#retrieve-the-loader-script}

1. Select the referral offer from the tree, then click **Referral Offer Actions** and **Embed Code**.

   ![](assets/image2015-4-20-17-3a34-3a46.png)

1. Right-click the **Header Code** and insert it into your webpage header. Then do the same for the **Body Code**.

   ![](assets/image2015-4-20-20-3a49-3a19.png)

## Pasting the Scripts Onto Your Webpage {#pasting-the-scripts-onto-your-webpage}

Paste the conversion scripts into the HTML for the body and header. Next, place the loader scripts into the HTML for the body and header.

![](assets/image2015-4-20-21-3a0-3a16.png)

## Connecting the Conversion Script {#connecting-the-conversion-script}

Here's where you will write a JavaScript function that uses the specific HTML id of whatever page element you want to trigger goal completion on. For example:

`<pre><em><!-- Referral offer conversion script --></em> <script> cf_scripts.afterload(function (){ jQuery("#myButtonId").click(function (){ CF.insight.conversion(); }); }); </script></pre>` `<pre>`

In this example there is a button on the webpage with an id of "#myButtonId." When that button is clicked, the person will be registered as having completed the goal.

Awesome! Your website is now capturing custom social promotion goals with Marketo.

>[!MORELIKETHIS]
>
>* [Specify Goal for Referral Offer](/help/marketo/product-docs/demand-generation/social/referral-offers/specify-goal-for-referral-offer.md)
>* [Create a Referral Offer](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md)
>* [Deploy Social on Your Website](/help/marketo/product-docs/demand-generation/social/social-functions/deploy-social-on-your-website.md)
