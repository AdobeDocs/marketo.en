---
unique-page-id: 2359424
description: Alert the Sales Rep - Marketo Docs - Product Documentation
title: Alert the Sales Rep
---

# Alert the Sales Rep {#alert-the-sales-rep}

## Mission: Alert the sales rep when a person fills out a form on your web site {#mission-alert-the-sales-rep-when-a-person-fills-out-a-form-on-your-web-site}

To automatically send alert emails to sales reps, all you need is an alert email and an email campaign. Here's how to do it.

>[!PREREQUISITES]
>
>[Landing Page with a Form](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md)

## Step 1: Create an Alert Email {#step-create-an-alert-email}

1. Go to the **Marketing Activities** area.

   ![](assets/one-5.png)

1. Select **My Program** which you created in the [Landing Page with a Form](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md) quick win, then under **New** click **New Local Asset**.

   ![](assets/two-6.png)

1. Click **Email**.

   ![](assets/three-5.png)

1. **Name** the email "My Email Alert", select a template and click **Create**.

   ![](assets/four-4.png)

1. Enter the **From Name**, **From Email**, **Reply-to**, and **Subject** that you want your sales team to see.

   ![](assets/five-5.png)

1. Double-click to edit the email text.

   ![](assets/six-5.png)

1. Type the email content.

   ![](assets/seven-6.png)

1. Place your cursor where you want to insert the person's contact info and click the **Insert Token** icon.

   ![](assets/eight-4.png)

1. Find and select the `{{SP_Send_Alert_Info}}` **Token** and click **Insert**.

   ![](assets/image2014-9-24-13-3a10-3a0.png)

   >[!NOTE]
   >
   >{{SP_Send_Alert_Info}} is a special token for alert emails. See [Use the Send Alert Info Token](/help/marketo/product-docs/email-marketing/general/using-tokens/use-the-send-alert-info-token.md) to learn more.

1. Click **Save**.

   ![](assets/ten-5.png)

1. Close the email editor tab/window.

   ![](assets/eleven-5.png)

1. Under **Email Actions** click **Approve**.

   ![](assets/twelve-4.png)

## Step 2: Create an Alert Trigger Campaign {#step-create-an-alert-trigger-campaign}

1. Select **My Program** created previously, then under **New** click **New Smart Campaign**.

   ![](assets/image2014-9-24-13-3a14-3a17.png)

1. **Name** the campaign "My Alert Campaign" and click **Create**.

   ![](assets/image2014-9-24-13-3a14-3a28.png)

1. Under the **Smart List** tab, find and drag the **Fills Out Form** trigger to the canvas.

   ![](assets/image2014-9-24-13-3a14-3a43.png)

1. Select the form we created earlier.

   ![](assets/image2014-9-24-13-3a14-3a58.png)

1. Under the **Flow** tab, find and drag the **Send Alert** flow action to the canvas.

   ![](assets/image2014-9-24-13-3a15-3a10.png)

1. Select **My Alert Email** created earlier and leave **Send To** as **Sales Owner**.

   ![](assets/eighteen-1.png)

1. Type your email address in the **To Other Emails** field.  

   ![](assets/nineteen-2.png)

1. Go to the **Schedule** tab and click the **Activate** button.

   ![](assets/twenty-2.png)

   >[!TIP]
   >
   >Set the **Qualification Rules** to **every time** (by editing the Smart Campaign)  to allow the same person to trigger alerts multiple times.

1. Click **Activate** on the confirmation screen.

   ![](assets/twenty-one-1.png)

## Step 3: Test It Out! {#step-test-it-out}

1. Select your landing page and click **View Approved Page**.  

   ![](assets/image2014-9-24-13-3a17-3a8.png)

   >[!NOTE]
   >
   >Don't forget to approve landing pages; they don't go live until approved.

1. Fill out the form and click **Submit**.

   ![](assets/image2014-9-24-13-3a17-3a41.png)

1. You should receive your email shortly. Once you've verified that everything works as it should, remove your email address from the Send Alert flow (see step 2.7 above).

   >[!NOTE]
   >
   >Click the **Person Info** tab in Marketo to see the contact info.

## Mission Complete! {#mission-complete}

<br>&nbsp;

[◄ Mission 7: Personalize an Email](personalize-an-email.md)

[Mission 9: Update Lead Data ►](update-person-data.md)
