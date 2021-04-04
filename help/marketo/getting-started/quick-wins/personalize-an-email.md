---
unique-page-id: 2359422
description: Personalize an Email - Marketo Docs - Product Documentation
title: Personalize an Email
exl-id: 1562796e-da47-4305-b950-3bed1d36d339
---
# Personalize an Email {#personalize-an-email}

## Mission: Make your emails personal by adding data tokens {#mission-make-your-emails-personal-by-adding-data-tokens}

>[!PREREQUISITES]
>
>* [Get Set Up and Add a Person](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md)
>* [Send an Email Blast](/help/marketo/getting-started/quick-wins/send-an-email.md)
>* [Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

## Step 1: Select an Email to Personalize {#step-select-an-email-to-personalize}

1. Select one of the nurture emails created in the [previous quick win](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md) and click **Edit Draft**.

   ![](assets/one-4.png)

   >[!NOTE]
   >
   >This creates a copy of the email as a draft. You must approve the draft for the changes to go live.

If you haven't enabled a pop-up blocker, the email editor will open in a new tab/window. Otherwise, click **Edit Draft** twice.

## Step 2: Make the Salesperson the Sender {#step-make-the-salesperson-the-sender}

1. Select the **From** field, highlight and **delete** the current name.

   ![](assets/two-5.png)

1. Click the **Token** icon to the right of the **From** field.

   ![](assets/three-4.png)

1. Find and select the **`{{lead.Lead Owner First Name}}`** token.

   ![](assets/four-3.png)

1. Type your company name and a dash for the **Default Value** to ensure something is displayed in case the sale rep's first name is unavailable. Click **Insert**.

   ![](assets/five-4.png)

1. Hit the space bar in the **From** field, making sure the cursor is flashing one space after the token you just inserted. Then click the **Token** icon again.

   ![](assets/six-4.png)

1. Find and select the **`{{lead.Lead Owner Last Name}}`** token.

   ![](assets/seven-5.png)

1. Type "Sales" for the **Default Value** and click **Insert**.

   ![](assets/eight-3.png)

## Step 3: Add the Lead's Name to the Email {#step-add-the-leads-name-to-the-email}

1. Select the top editable section, click the gear icon and select **Edit**.

   ![](assets/nine-2.png)

1. Add a space after "Hello" and place your cursor in front of the comma, then click the **Insert Token** icon.

   ![](assets/ten-4.png)

1. Find and select the **`{{lead.First Name}}`** token.

   ![](assets/eleven-4.png)

1. Enter "Friend" (or any label you'd like) in the **Default Value** field and click **Insert**.

   ![](assets/twelve-3.png)

   >[!TIP]
   >
   >Always include a default value for tokens; this ensures the default value will be displayed in the email if some part of the personal information is missing.

1. Click **Save**.

   ![](assets/thirteen-3.png)

1. Close the email editor tab/window.

   ![](assets/fourteen-3.png)

1. Under **Email Actions**, select **Approve Draft**.

   ![](assets/fifteen-3.png)

>[!TIP]
>
>Need a quick refresher on how to send yourself the email? See [Send an Email Blast](/help/marketo/getting-started/quick-wins/send-an-email.md).

### Mission Complete {#mission-complete}

Congratulations, you've personalized your email!

<br>&nbsp;

[◄ Mission 6: Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

[Mission 8: Alert the Sales Rep ►](/help/marketo/getting-started/quick-wins/alert-the-sales-rep.md)
