---
unique-page-id: 2359416
description: Email Auto-Response - Marketo Docs - Product Documentation
title: Email Auto-Response
---

# Email Auto-Response {#email-auto-response}

## Mission: Send out a thank-you email when a person fills out a form {#mission-send-out-a-thank-you-email-when-a-person-fills-out-a-form}

>[!PREREQUISITES]
>
>* [Get Set Up and Add a Person](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md)
>* [Landing Page with a Form](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md)

## Step 1: Create an Email {#step-create-an-email}

1. Go to the Marketing Activities area.

   ![](assets/one-2.png)

1. Select My Program in the left menu, click the New drop-down, and select New Local Asset.

   ![](assets/two-3.png)

1. Click Email.

   ![](assets/three-2.png)

1. Name your email "Auto Response Email," choose a template and click Create.

   ![](assets/four-1.png)

   An email editor will open in a new window or tab. If pop-ups are blocked, click **Edit Draft** on the asset summary page to access the email.

1. Enter a subject line, then double-click the editable area of the email.

   ![](assets/five-2.png)

   _A rich text editor will open on top of the email editor._

1. Highlight the existing email content.

   ![](assets/six-2.png)

1. Type your email content and click Save.

   ![](assets/seven-2.png)

1. Your changes are auto-saved. Close the email editor tab/window.

   ![](assets/eight-1.png)

1. Select your new email. Under Email Actions click Approve.

   ![](assets/image2014-9-24-11-3a55-3a16.png)

## Step 2: Create a Smart Campaign {#step-create-a-smart-campaign}

1. Right-click **My Program** and click **New Smart Campaign**.

   ![](assets/image2014-9-24-11-3a56-3a13.png)

1. **Name** your the smart campaign "Auto Response Campaign" and click **Create**.

   ![](assets/image2014-9-24-11-3a56-3a25.png)

1. Go to the **Smart List** tab.

   ![](assets/image2014-9-24-11-3a56-3a38.png)

   We're setting up this campaign to run whenever a person fills out the form you created in [**Landing Page with a Form**](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md).

1. Find and drag the **Fills Out Form** trigger to the left canvas.

   ![](assets/image2014-9-24-11-3a57-3a18.png)

1. Select **My Form** in the drop-down. Click the **Flow** tab.

   ![](assets/image2014-9-24-11-3a57-3a29.png)

1. Drag the **Send Email** flow action to the left canvas.

   ![](assets/image2014-9-24-11-3a57-3a41.png)

1. Select your **Auto Response Email** and go to the **Schedule** tab.

   ![](assets/image2014-9-24-11-3a57-3a53.png)

1. Click **Edit**.

   ![](assets/8.png)

1. Select **every time** and click **Save**.

   ![](assets/9.png)

1. Click **Activate**.

   ![](assets/10.png)

1. Click **Activate** on the confirmation screen.

   ![](assets/11.png)

>[!NOTE]
>
>Once active, this campaign will run every time a person fills out the specified form. The campaign will keep running until it's deactivated.

## Step 3: Fill Out the Form {#step-fill-out-the-form}

1. Select **My Page**. This was created in the [Landing Page with a Form](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md) quick win.

   ![](assets/image2014-9-24-12-3a0-3a8.png)

1. Click **View Approved Page**.

   ![](assets/image2014-9-24-12-3a0-3a18.png)

   Your "Free Trial" landing page will open in a new tab.

1. Fill out the form with your first name, last name, and email address, then click **Submit**.

   ![](assets/image2014-9-24-12-3a0-3a28.png)

>[!NOTE]
>
>Make sure you use your actual email address so you can get the email.

## Mission Complete {#mission-complete}

Within just a few minutes you should see the auto response email in your inbox. Great job!

<br>&nbsp;

[◄ Mission 3: Simple Scoring](/help/marketo/getting-started/quick-wins/simple-scoring.md)

[Mission 5: Import a List of Leads ►](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md)
