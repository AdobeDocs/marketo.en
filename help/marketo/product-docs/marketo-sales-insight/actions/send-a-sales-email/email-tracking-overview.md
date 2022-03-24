---
description: Email Tracking Overview - Marketo Docs - Product Documentation
title: Email Tracking Overview
exl-id: 89437d22-d739-45ea-8a2e-046a7de80379
---
# Email Tracking Overview {#email-tracking-overview}

## How Reply Tracking Works {#how-reply-tracking-works}

Reply Tracking is done by looking at a message ID that’s in every email you send. Every email contains a unique message ID that allows us to have some of the best reply tracking around.

>[!PREREQUISITES]
>
>Connection with Email Server: Sales Connect must be connected with your inbox so we know when a new reply has arrived. You’ll need to have your Sales Connect account connected to Gmail. If you’re using Outlook, we’ll need to integrate with your exchange server.

If Sales Connect can’t track your prospect’s reply to your email, it won’t be able to stop a campaign based on reply detection or log that reply to Salesforce. What do we mean any email address can reply?

This means that if you email flynn@flynnsarcade.com and he responds with kevinf@flynnsarcade.com, we’re able to track the reply. Additionally, if you email flynn@flynnsarcade.com and CC alan@encom.com, and Alan writes you back, it will also detect the reply and end the campaign.

## How to Track Your Email Attachments {#how-to-track-your-email-attachments}

Sales Connect offers tracking on your attachments (.doc, .ppt, .pdf) so you can see when they’ve been opened/downloaded, and see what pages your recipient is looking through. We’ll allow you to use our trackable attachments feature from both the [web application](https://toutapp.com/login) and Gmail (or Google Apps).

>[!NOTE]
>
>Attachment tracking is only available for our team plans (starting with our g3startup plan).

**How to Send Your First Trackable Attachment**

1. Compose an email or edit a template, then click the **Content** button.

1. Upload your attachment and send it out. We support PDFs, Word docs, and Powerpoint presentations.

1. Select **Add to Email**.

1. Click **Send** and fire up your Live Feed. You’ll see your recipients as they open and page through your attachments.

>[!TIP]
>
>If you would not like to track an attachment, simply click Attach Files and this attachment will not be tracked.

## How View Tracking Works {#how-view-tracking-works}

We track email opens by placing an invisible image inside the emails you send.

If someone responds to your email but Sales Connect is saying it wasn’t viewed, odds are the recipient did not enable images within their email client (i.e., click on the “click here to download images” message in the email).

Some tips for getting better tracking stats on your emails:

* Include an image in your emails (like a logo) so the recipient is encouraged to enable images to see your message.
* Include a link as a call to action in the email.

## Test Email Not Showed as Viewed {#test-email-not-showed-as-viewed}

Even if you sent your message to another email address, we won’t log you viewing any emails you’ve sent to yourself in the Live Feed. Our tracking is device-based; as long as you’re using a computer you’ve logged into Sales Connect with, we’ll filter out that activity.

The reason? Sales Connect is smart, and our active users would never forgive us if their own info popped up in the Live Feed Activity every time they looked at an email they sent.
