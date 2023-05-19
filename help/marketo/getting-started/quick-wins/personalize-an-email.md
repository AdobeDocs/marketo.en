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
>* [Get Set Up and Add a Person](/help/marketo/getting-started/quick-wins/get-set-up-and-add-a-person.md){target="_blank"}
>* [Send an Email Blast](/help/marketo/getting-started/quick-wins/send-an-email.md){target="_blank"}
>* [Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md){target="_blank"}

## Step 1: Select an Email to Personalize {#step-select-an-email-to-personalize}

1. Select one of the nurture emails created in the [previous quick win](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md){target="_blank"} and click **[!UICONTROL Create draft]**.

   ![](assets/personalize-an-email-1.png)

   >[!NOTE]
   >
   >This creates a copy of the email as a draft. Remember to approve the draft for the changes to go live.

If you haven't enabled a pop-up blocker, the email editor will open in a new tab/window. Otherwise, click **[!UICONTROL Create Draft]** twice.

## Step 2: Make the Salesperson the Sender {#step-make-the-salesperson-the-sender}

1. Select the **[!UICONTROL From]** field, highlight and **delete** the current name.

   ![](assets/personalize-an-email-2.png)

1. Click the **Token** icon to the right of the **[!UICONTROL From]** field.

   ![](assets/personalize-an-email-3.png)

1. Find and select the **`{{lead.Lead Owner First Name}}`** token.

   ![](assets/personalize-an-email-4.png)

1. Type your company name and a dash for the **Default Value** to ensure something is displayed in case the sale rep's first name is unavailable. Click **Insert**.

   ![](assets/personalize-an-email-5.png)

1. Hit the space bar in the **[!UICONTROL From]** field, making sure the cursor is flashing one space after the token you just inserted. Then click the **Token** icon again.

   ![](assets/personalize-an-email-6.png)

1. Find and select the **`{{lead.Lead Owner Last Name}}`** token.

   ![](assets/personalize-an-email-7.png)

1. Type "Sales" for the **Default Value** and click **Insert**.

   ![](assets/personalize-an-email-8.png)

## Step 3: Add the Lead's Name to the Email {#step-add-the-leads-name-to-the-email}

1. Select the top editable section, click the gear icon and select **[!UICONTROL Edit]**.

   ![](assets/personalize-an-email-9.png)

1. Add a space after "Hello" and place your cursor in front of the comma, then click the **Insert Token** icon.

   ![](assets/personalize-an-email-10.png)

1. Find and select the **`{{lead.First Name}}`** token.

   ![](assets/personalize-an-email-11.png)

1. Enter "Friend" (or any label you'd like) in the **[!UICONTROL Default Value]** field and click **[!UICONTROL Insert]**.

   ![](assets/personalize-an-email-12.png)

   >[!TIP]
   >
   >Always include a default value for tokens; this ensures the default value will be displayed in the email if some part of the personal information is missing.

1. Click **[!UICONTROL Save]**.

   ![](assets/personalize-an-email-13.png)

1. Under **[!UICONTROL Email Actions]** and select **[!UICONTROL Approve and Close]**.

   ![](assets/personalize-an-email-14.png)

>[!TIP]
>
>Need a quick refresher on how to send yourself the email? See [Send an Email Blast](/help/marketo/getting-started/quick-wins/send-an-email.md){target="_blank"}.

### Mission Complete {#mission-complete}

Congratulations, you've personalized your email!

<br>&nbsp;

[◄ Mission 6: Drip, Drip, Nurture](/help/marketo/getting-started/quick-wins/drip-drip-nurture.md)

[Mission 8: Alert the Sales Rep ►](/help/marketo/getting-started/quick-wins/alert-the-sales-rep.md)
