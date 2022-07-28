---
unique-page-id: 2359545
description: Define the A/B Test Winner Criteria - Marketo Docs - Product Documentation
title: Define the A/B Test Winner Criteria
exl-id: be8a0887-70f4-4667-93a6-d982a16cdfdb
---
# Define the A/B Test Winner Criteria {#define-the-a-b-test-winner-criteria}

When [adding an A/B test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md){target="_blank"} to your email program, you will need to pick a test type, [schedule the A/B test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md){target="_blank"}, then define the winner criteria. Here's how to decide which email wins.

>[!PREREQUISITES]
>
>[Add an A/B Test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md){target="_blank"}

## Winner Criteria {#winner-criteria}

1. The default **Winner Criteria** options are listed first.

   ![](assets/image2014-9-12-15-3a51-3a3.png)

   <table>
   <tr>
   <td><b>Opens</b></td>
   <td>An open registers when images are downloaded into an email. Even if you don't include an image, by default Marketo inserts a single tracking pixel into all HTML emails.</td>
   </tr>
   <tr>
   <td><b>Clicks</b></td>
   <td>By default, links in emails have tracking embedded in them allowing you to see who clicked which link, how many total links were clicked, etc.</td>
   </tr>
   <tr>
   <td><b>Click to Open %</b></td>
   <td>Percentage of emails that were opened and had a link clicked in the email. This measures the relevancy and context of an email by taking the number of unique clicks divided by the number of unique opens, and then multiplying by 100 to show it as a percentage.</td>
   </tr>
   <tr>
   <td><b>Engagement Score</b></td>
   <td>The <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.html" target="_blank">engagement score</a> helps you determine the effectiveness of your content.</td>
   </tr>
   </table>

   >[!TIP]
   >
   >If you pick Engagement Score the test will need to run for at least 24 hours. Learn more about [understanding the engagement score](/help/marketo/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.md){target="_blank"}.

1. You can also customize your criteria by selecting Custom Conversion and clicking Edit.

   ![](assets/image2014-9-12-15-3a51-3a53.png)

   >[!NOTE]
   >
   >Custom Conversion allows you to pick any event as a conversion by using triggers and filters.

1. A window will pop open. Find the trigger of your choice and drag it into the canvas.

   ![](assets/image2014-9-12-15-3a52-3a18.png)

1. Define the trigger.

   ![](assets/image2014-9-12-15-3a53-3a11.png)

   >[!NOTE]
   >
   >Marketo will only allow triggers for people who have been sent the email from this email program. No need to add a "Was Sent Email" filter.

1. Click **Close**.

   ![](assets/image2014-9-12-15-3a53-3a36.png)

   Great! Now it's time to decide how the winner is determined.

## Declare Winner {#declare-winner}

1. Pick one of the two available options.

   ![](assets/image2014-9-12-15-3a53-3a44.png)

   >[!NOTE]
   >
   >If you are doing a **Date/Time** A/B test, you can only choose **Manual**.

   Once the A/B test is over, Marketo can automatically send the winning email at the scheduled time, or you can review the results and decide which email goes out when.  

1. Automatic is awesome and is the default option. Just click **Next**.

   ![](assets/image2014-9-12-15-3a54-3a35.png)

   >[!TIP]
   >
   >Choosing **Manual** will send the test out and wait for you to declare a winner. You will receive a report of the results.

Perfect! Now let's [schedule the A/B test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/schedule-the-a-b-test.md){target="_blank"}.
