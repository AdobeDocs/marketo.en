---
unique-page-id: 10097202
description: Head Start for Email Programs - Marketo Docs - Product Documentation
title: Head Start for Email Programs
exl-id: f7c8b082-4d83-4e3b-8aa4-7b252e3dacd3
feature: Email Programs
---
# Head Start for Email Programs {#head-start-for-email-programs}

>[!PREREQUISITES]
>
>[Create an Email Program](/help/marketo/product-docs/email-marketing/email-programs/creating-an-email-program/create-an-email-program.md)

When you choose a date/time for an Email Program, it determines when the program will begin processing. If you want your emails to launch at the selected time, Head Start gives you that option by processing the program in advance.

## Standard Head Start {#standard-head-start}

1. Click **Marketing Activities**.

   ![](assets/one-1.png)

1. Find and select your Email Program.

   ![](assets/selectemailprogram-4.jpg)

   >[!NOTE]
   >
   >Head Start cannot be used with A/B testing.

1. In the Schedule tile, schedule your email then select the **Head Start** box.

   ![](assets/three-1.png)

   With Head Start selected, the program will begin processing approximately 12 hours prior to the scheduled time. Once processing starts, the program is locked.

   >[!CAUTION]
   >
   >Anyone from your audience who unsubscribes after program lock will still receive the email. We recommend adjusting your unsubscribe notification to reflect that unsubscribes may take 1-2 business days to process.

1. Click **Approve Program**.

   ![](assets/four-1.png)

   After program approval, there are four different statuses you may see on the Approval tile.

    * **Waiting to run:** After the program is approved.
    * **Processing started, waiting to run:** Processing is in progress.
    * **Processing finished, waiting to run:** Processing completed, email now waiting for scheduled time to launch.
    * **Finished:** Program completed.

   >[!TIP]
   >
   >Want to cancel after the program locks but before the email sends? No problem! Simply click **Abort Program** in the lower-right side of the Approval tile.

   >[!NOTE]
   >
   >If you unapprove your email program with less than 12 hours before its scheduled run time, but then change your mind, you'll need to pick a new date/time that's at least 12 hours ahead of when you approve it.

## Head Start with Recipient Time Zone {#head-start-with-recipient-time-zone}

   Our existing Head Start feature requires the program to be scheduled at least 12 hours in advance. What does that mean for Recipient Time Zone? Recall that when Recipient Time Zone is active, we start running the email program at midnight in the earliest time zone (UTC +14:00). So, to enable **both** Head Start and Recipient Time Zone, programs need to be scheduled **at least 12 hours ahead of the earliest time zone (UTC +14:00**.)

   This means that if you're in America/Los Angeles and want to enable both Head Start and Recipient Time Zone, you need to schedule the program **34 hours** in advance. How did we get to this number?

   ![](assets/image2017-12-5-13-3a11-3a46.png)

   [Learn more](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md) about how to schedule email programs with Recipient Time Zone.

>[!MORELIKETHIS]
>
>* [Schedule Your Email Program](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/schedule-your-email-program.md)
>* [Schedule Email Programs with Recipient Time Zone](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [Understanding Recipient Time Zone](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/understanding-recipient-time-zone.md)
