---
unique-page-id: 2359416
description: Email Auto-Response - Marketo Docs - Product Documentation
title: Email Auto-Response
exl-id: c9c0a154-65ec-4845-97a0-a2100223cb13
---
# Email Auto-Response {#email-auto-response}

## Mission: Send out a thank-you email when a person fills out a form {#mission-send-out-a-thank-you-email-when-a-person-fills-out-a-form}

>[!PREREQUISITES]
>
>* [Get Set Up and Add a Person](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target="_blank"}
>* [Landing Page with a Form](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"}

## Step 1: Create an Email {#step-create-an-email}

1. Go to the **[!UICONTROL Marketing Activities]** area.

   ![](assets/email-auto-response-1.png)

1. Select your program in the left menu, click the **[!UICONTROL New]** drop-down, and select **[!UICONTROL New Local Asset]**.

   ![](assets/email-auto-response-2.png)

1. Select **[!UICONTROL Email]**.

   ![](assets/email-auto-response-3.png)

1. Name your email "Auto Response Email," choose a template, and click **[!UICONTROL Create]**.

   ![](assets/email-auto-response-4.png)

   An email editor will open in a new window or tab. If pop-ups are blocked, click **[!UICONTROL Edit Draft]** on the asset summary page to access the email.

1. Enter a subject line, then double-click the editable area of the email.

   ![](assets/email-auto-response-5.png)

   _A rich text editor will open on top of the email editor._

1. Highlight the existing email content.

   ![](assets/email-auto-response-6.png)

1. Type your email content and click **[!UICONTROL Save]**.

   ![](assets/email-auto-response-7.png)

1. Click the **[!UICONTROL Email Actions]** drop-down and select **[!UICONTROL Approve and Close]**.

   ![](assets/email-auto-response-8.png)

## Step 2: Create a Smart Campaign {#step-create-a-smart-campaign}

1. Select your program, click the **[!UICONTROL New]** drop-down and select **[!UICONTROL New Smart Campaign]**.

   ![](assets/email-auto-response-9.png)

1. **Name** your the smart campaign "Auto Response Campaign" and click **[!UICONTROL Create]**.

   ![](assets/email-auto-response-10.png)

1. Go to the **[!UICONTROL Smart List]** tab.

   ![](assets/email-auto-response-11.png)

   We're setting up this campaign to run whenever a person fills out the form you created in [**Landing Page with a Form**](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"}.

1. Find and drag the **[!UICONTROL Fills Out Form]** trigger to the canvas.

   ![](assets/email-auto-response-12.png)

1. Select **[!UICONTROL My Form]** in the drop-down. Then click the **[!UICONTROL Flow]** tab.

   ![](assets/email-auto-response-13.png)

1. Drag the **[!UICONTROL Send Email]** flow action to the left canvas.

   ![](assets/email-auto-response-14.png)

1. Select your **Auto Response Email**. Then click the **[!UICONTROL Schedule]** tab.

   ![](assets/email-auto-response-15.png)

1. Click **[!UICONTROL Edit]**.

   ![](assets/email-auto-response-16.png)

1. Select **[!UICONTROL every time]** and click **[!UICONTROL Save]**.

   ![](assets/email-auto-response-17.png)

1. Click **[!UICONTROL Activate]**.

   ![](assets/email-auto-response-18.png)

1. Click **[!UICONTROL Activate]** on the confirmation screen.

   ![](assets/email-auto-response-19.png)

>[!NOTE]
>
>Once active, this campaign will run every time a person fills out the specified form. The campaign will keep running until it's deactivated.

## Step 3: Fill Out the Form {#step-fill-out-the-form}

1. Select **My Page** (this was created in the [Landing Page with a Form](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"} quick win) and click **[!UICONTROL Preview]**.

   ![](assets/email-auto-response-20.png)

   _Your "Free Trial" landing page will open in a new tab._

1. Fill out the form with your first name, last name, and email address, then click **[!UICONTROL Submit]**.

   ![](assets/email-auto-response-21.png)

>[!NOTE]
>
>Make sure you use your actual email address so you can get the email.

## Mission Complete {#mission-complete}

Within just a few minutes you should see the auto response email in your inbox. Great job!

<br>&nbsp;

[◄ Mission 3: Simple Scoring](/help/marketo/getting-started/quick-wins/simple-scoring.md)

[Mission 5: Import a List of People ►](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md)
