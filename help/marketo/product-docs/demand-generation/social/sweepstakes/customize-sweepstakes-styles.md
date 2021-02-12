---
unique-page-id: 2359807
description: Customize Sweepstakes Styles - Marketo Docs - Product Documentation
title: Customize Sweepstakes Styles
---

# Customize Sweepstakes Styles {#customize-sweepstakes-styles}

When you [create a sweepstakes](/help/marketo/product-docs/demand-generation/social/sweepstakes/create-sweepstakes.md), you can customize how it looks on your landing page.

>[!AVAILABILITY]
>
>Not all customers have purchased this functionality. Contact your sales rep for details.

1. Go to **Marketing Activities**.

![](assets/login-marketing-activities-1.png)

1. Select the sweepstakes, and click **Edit Draft**.

   ![](assets/image2014-9-25-17-3a51-3a45.png)

1. In the Sweepstakes editor, go to **App Settings** > **Appearance**.

   ![](assets/image2014-9-25-17-3a51-3a59.png)

1. Edit the text of your sign-up button and the progress link.

   ![](assets/image2014-9-25-17-3a52-3a22.png)

1. For each element that you wish to customize, enter your custom CSS properties.

   ![](assets/image2014-9-25-17-3a52-3a37.png)

   Example CSS for **Enter Button**:
   `<pre>border: 5px solid #7B68EE; background-color: purple; padding: 10px; font: 16px; color: #FFFFFF; text-align: center;</pre>`

   Example Image for **Enter Button**:
   `<pre>background:url(https://app.marketo.com/images/public-site/button_sign-up-now.png) no-repeat center center; width:275px; height:95px; margin:auto; display:block;</pre>` `<pre>`

   >[!NOTE]
   >
   >If you use an image with text on it, remember to remove the text from the **Enter Button** field under Text above.

1. As you make each change, the result is displayed in the View & Edit preview.

   ![](assets/image2014-9-25-17-3a55-3a3.png)

   >[!NOTE]
   >
   >Test your button in several different browsers, including older versions.

   >[!MORELIKETHIS]
   >
   >The next step is to add [sign-up and fulfillment emails to your sweepstakes](/help/marketo/product-docs/demand-generation/social/social-functions/use-emails-in-social-promotions.md).
