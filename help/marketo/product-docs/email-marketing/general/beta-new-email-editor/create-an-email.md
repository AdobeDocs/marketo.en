---
description: Create an Email - Marketo Docs - Product Documentation
title: Create an Email
hide: yes
hidefromtoc: yes
feature: Email Editor
---
# Create an Email {#create-an-email}

Intro text here.

>[!IMPORTANT]
>
>This article is for members of the New Marketo Engage Email Editor closed beta only. Please do not disseminate.

1. Log in to Marketo Engage via the [Adobe Experience Cloud](https://experiencecloud.adobe.com/){target="_blank"}.

1. In My Marketo, select **Design Studio**.

   ![](assets/create-an-email-1.png)

1. In the tree, select **Emails (New Editor)**.

   ![](assets/create-an-email-2.png)

1. Click the **Create email** button.

   ![](assets/create-an-email-3.png)

1. Enter an email name and a subject line. Click **Create**.

   ![](assets/create-an-email-4.png)

That's it. Now it's time to design your email.

## Choose your content type {#choose-your-content-type}

1. In the email you just created, click **+ Add email content**.

   SCREENSHOT

1. The 'Create your email' page loads. You can choose from a few options:

* [Design from scratch](#design-from-scratch) using the Email Editor

* [Import your own HTML](#import-html) via an HTML or zip file

* [Select an existing template](#choose-a-template) (one of our samples or one you already saved)

### Design from scratch {#design-from-scratch}

When starting from scratch in the email editor, use the options below to define your content.

1. In the Design your template homepage, select **Design from scratch**.

Add structure and content to your email.

Add images.

Personalize your content.

Review and update links.

### Import HTML {#import-html}

You can import existing HTML content to design your email templates. The content can be:

* An HTML file with an incorporated style sheet

* A .zip file that includes an HTML file, the style sheet (.css) and images

>[!NOTE]
>
>There are no constraints on the .zip file structure. However, references must be relative and fit with the tree structure of the .zip folder.

1. In the Design your template page, select **Import HTML**.

   SCREENSHOT

1. Drag and drop the desired HTML or .zip file and click **Import**.

   SCREENSHOT

>[!NOTE]
>
>When the HTML content is uploaded, your content will be in Compatibility mode. In this mode, you can only personalize your text, add links, or include assets to your content.

You can make desired changes to the imported content using the [email editor tools](#add-structure-and-content).

### Choose a template {#choose-a-template}

There are two types of templates to choose from.

* Sample templates: Marketo Engage offers four out-of-the-box email templates.

* Saved templates: These are templates you created from scratch using the Templates menu, or an email you created and chose to save as a template.

>[!BEGINTABS]

>[!TAB Sample templates]

Choose one of our out-of-the-box templates for a head start on your email design.

1. In the Create your email page, select **Sample templates**.

   SCREENSHOT

1. Select the desired template.

   SCREENSHOT

1. A preview appears. To confirm your selection, click **Use this template**.

   SCREENSHOT

>[!TAB Saved templates]

Choose one of your previously created templates.

1. In the Create your email page, select Saved templates.

   SCREENSHOT

1. Select the desired template.

   SCREENSHOT

1. A preview appears. To confirm your selection, click **Use this template**.

   SCREENSHOT

>[!ENDTABS]

## Add structure and content {#add-structure-and-content}

1. To start creating or modifying content, drag and drop an item from Structures onto the canvas. Edit its settings in the pane on the right.

   >[!TIP]
   >
   >Select the n:n column component to define the number of columns of your choice (between three and 10). You can also define the width of each column by moving the arrows below the column.

   SCREENSHOT

   >[!NOTE]
   >
   >Each column size cannot be less than 10% of the total width of the structure component. Only empty columns can be removed.

1. From the Contents section, drag over desired items and drop them into one or more structure components.

   SCREENSHOT

1. Each component can be customized via the Settings or Style tabs. Change the font, text style, margin, and more.

SCREENSHOT

### Add Assets {#add-assets}

From the Asset picker, you can directly select assets stored in the Assets library. Double-click the folder which contains your assets. Drag and drop them into a structure component.

Insert personalization fields to customize your content from profiles attributes, audience memberships, Contextual attributes, and more. 

Click Enable condition content to add dynamic content and adapt the content to the targeted profiles based on conditional rules.

Click the Links tab from the left pane to display all the URLs of your content that will be tracked. You can modify their Tracking Type or Label and add Tags if needed. 

If needed, you can further personalize your email by clicking Switch to code editor from the advanced menu. This allows you to edit the email source code, for example to add tracking or custom HTML tags.

CAUTION
You cannot revert back to the visual designer for this email after switching to the code editor.

Once your content is ready, click the Simulate content button to check rendering. You can choose the desktop or mobile view.

When ready, click Save





## Check Alerts {#check-alerts}

As you design your content, alerts are displayed in the interface (top-right of the screen) when key settings are missing.

There are two types of alerts:

**Warnings**

Warnings refer to recommendations and best practices, such as:

* **The opt-out link is not present in the email body**: While unsubscribe links are a requirement, adding them to the body of your email is a best practice.

>[!NOTE]
>
>Adding an unsubscribe option is not required for [Operational Emails](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md) (non-marketing).

* **Text version of HTML is empty**: You must define a text version of your email body for when HTML content cannot be displayed.

* **Empty link is present in email body**: Verify all links in your email are correct.

* **Email size has exceeded the limit of 100KB**: For optimal delivery, make sure the size of your email does not exceed 100KB.

**Errors**

Errors prevent you from sending or testing the email until they are resolved:

* **Subject line is missing**: An email subject line is required.

* **Email version of the message is empty**: This error occurs when the email content has not been configured.

## Test your email

When your message content is defined, you can use test profiles to preview it, send proofs, and control how it renders in popular desktop, mobile, and web-based clients. If you inserted personalized content, you can check how it's displayed in the message using test profile data.

To preview your email content, click **Simulate content**, then add a test profile to check your message using the test profile data.

SCREENSHOT

## Reference an email {#reference-an-email}

After you've created an email in the new editor, you can reference it in Smart Campaigns or Smart Lists like you would with any other email.

* Reference it in a Smart List by [following the usual steps](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md).

* Reference it in a Smart Campaign by [following the usual steps](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/create-a-new-smart-campaign.md).

>[!NOTE]
>
>Only saved emails can be referenced. There is no "approved" status in the new email editor.
