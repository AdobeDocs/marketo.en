---
unique-page-id: 2359416
description: Email Auto-Response - Marketo Docs - Product Documentation
title: Email Auto-Response
---

# Email Auto-Response {#email-auto-response}

### Mission: Send out a thank-you email when a person fills out a form {#mission-send-out-a-thank-you-email-when-a-person-fills-out-a-form}

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

>[!NOTE]
>
>**Prerequisites**
>
>* [Get Set Up and Add a Person](get-set-up-and-add-a-person.md)
>* [Landing Page with a Form](landing-page-with-a-form.md)
>

### What's in this article? {#whats-in-this-article}

[Step 1: Create an Email](#step-create-an-email)  
[Step 2: Create a Smart Campaign](#step-create-a-smart-campaign)

#### Step 1: Create an Email {#step-create-an-email}

##### 1. Go to the Marketing Activities area. {#go-to-the-marketing-activities-area}

![](assets/one-2.png)  

##### 2. Select My Program in the left menu, click the New drop-down, and select New Local Asset. {#select-my-program-in-the-left-menu-click-the-new-drop-down-and-select-new-local-asset}

![](assets/two-3.png)  

##### 3. Click Email. {#click-email}

![](assets/three-2.png)  

##### 4. Name your email "Auto Response Email," choose a template and click Create. {#name-your-email-auto-response-email-choose-a-template-and-click-create}

![](assets/four-1.png)

An email editor will open in a new window or tab. If pop-ups are blocked, click** Edit Draft** on the asset summary page to access the email.

##### 5. Enter a subject line, then double-click the editable area of the email. {#enter-a-subject-line-then-double-click-the-editable-area-of-the-email}

![](assets/five-2.png)

A rich text editor will open on top of the email editor.

##### 6. Highlight the existing email content. {#highlight-the-existing-email-content}

![](assets/six-2.png)  

##### 7. Type your email content and click Save. {#type-your-email-content-and-click-save}

![](assets/seven-2.png)  

##### 8. Your changes are auto-saved. Close the email editor tab/window. {#your-changes-are-auto-saved-close-the-email-editor-tab-window}

![](assets/eight-1.png)  

##### 9. Select your new email. Under Email Actions click Approve. {#select-your-new-email-under-email-actions-click-approve}

![](assets/image2014-9-24-11-3a55-3a16.png) 

#### Step 2: Create a Smart Campaign {#step-create-a-smart-campaign}

1. Right-click **My Program** and click **New Smart Campaign**.

   ![](assets/image2014-9-24-11-3a56-3a13.png)

1. **Name** your the smart campaign "Auto Response Campaign" and click **Create**.

   ![](assets/image2014-9-24-11-3a56-3a25.png)

1. Go to the **Smart List **tab.

   ![](assets/image2014-9-24-11-3a56-3a38.png)

   We're setting up this campaign to run whenever a person fills out the form you created in [**Landing Page with a Form**](landing-page-with-a-form.md).

1. Find and drag the **Fills Out Form** trigger to the left canvas.

   ![](assets/image2014-9-24-11-3a57-3a18.png)

1. Select **My Form** in the drop-down. Click the **Flow **tab.

   ![](assets/image2014-9-24-11-3a57-3a29.png)

1. Drag the **Send Email **flow action to the left canvas.

   ![](assets/image2014-9-24-11-3a57-3a41.png)

1. Select your **Auto Response Email** and go to the **Schedule **tab.

   ![](assets/image2014-9-24-11-3a57-3a53.png)

1. Click **Edit**.

   ![](assets/8.png)

   ##### Select every time and click Save . {#select-every-time-and-click-save}

   ![](assets/9.png)

1. Click **Activate**.

   ![](assets/10.png)

1. Click **Activate **on the confirmation screen.

   ![](assets/11.png)

>[!NOTE]
>
>Once active, this campaign will run every time a person fills out the specified form. The campaign will keep running until it's deactivated.

## Step 3: Fill Out the Form {#step-fill-out-the-form}

1. Select **My Page**. This was created in the [Landing Page with a Form](landing-page-with-a-form.md) quick win.

   ![](assets/image2014-9-24-12-3a0-3a8.png)

1. Click **View Approved Page**.

   ![](assets/image2014-9-24-12-3a0-3a18.png)

   Your "Free Trial" landing page will open in a new tab.

1. Fill out the form with your first name, last name, and email address, then click **Submit**.

   ![](assets/image2014-9-24-12-3a0-3a28.png)

>[!NOTE]
>
>Make sure you use your actual email address so you can get the email.

### Mission Complete {#mission-complete}

Within just a few minutes you should see the auto response email in your inbox. Great job!

---

[◄ Mission 3: Simple Scoring](simple-scoring.md) [Mission 5: Import a List of Leads ►](import-a-list-of-people.md) 