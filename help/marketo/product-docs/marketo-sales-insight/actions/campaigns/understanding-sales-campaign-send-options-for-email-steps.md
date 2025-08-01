---
description: Understanding Sales Campaign Send Options for Email Steps - Marketo Docs - Product Documentation
title: Understanding Sales Campaign Send Options for Email Steps
feature: Sales Insight Actions
exl-id: 775c6401-efb2-4940-a81c-be5d2759c7bd
---
# Understanding Sales Campaign Send Options for Email Steps {#understanding-sales-campaign-send-options-for-email-steps}

When you are creating a Sales Campaign, you have several options on how your email steps get created in [!DNL Sales Insight Actions]. And, depending on where your email falls in your Sales Campaign, your options also differ.

## First Step Send Options {#first-step-send-options}

If it's your first step and the first day in your Sales Campaign, you will have the following options:

![](assets/understanding-sales-campaign-send-options-for-email-steps-1.png)

### I will choose when to send this email {#first-step-i-will-choose}

* This option allows you to choose the "send at" time for the first email in your Sales Campaign when you kick off the Sales Campaign by adding people.

### Send this email at the following time {#first-step-following-time}

* When you kick off your Sales Campaign by adding people to it, we will schedule the email for this time.
* You always have the option to choose a new "send at" time when you are kicking off your Sales Campaign.

### Create a task; I will send this email myself {#first-step-create-a-task}

* This option will create an Email Task (and sync to [!DNL Salesforce]) that you can send at your convenience.
* Once you've made this selection, when you kick off your Sales Campaign, we will queue these tasks up for you in Command Center and the Live Feed. You can then personalize and send (or schedule) each email before it goes out.

  * If you open this task in our web application, it will open a compose window with your contact's email address, the subject line of your email, and the template you chose.
  * If you open this task in Gmail or [!DNL Outlook], it will open a native compose window and dynamically populate your contact's email address, the subject line of your email, and the template you chose.

## Subsequent Step Send Options {#subsequent-step-send-options}

For any subsequent days/steps in your Sales Campaign, you will have the following options:

### Send this email at the same time as the previous email in this Sales Campaign {#subsequent-send-at-same-time}

* This option will send the email at the same time as the email directly before it.
* It will still send on the day it is associated with.

>[!IMPORTANT]
>
>Sending an email at the same time as the previous email is not supported for emails sent on the same day. Instead, the email will be sent out at the time of the email sent from the previous day. If this option is selected for an email on the first day of the campaign (not recommended), that email will be sent out immediately at the start of the campaign.

### Send this email at the following time {#subsequent-send-at-following-time}

* When you kick off your Sales Campaign by adding people to it, we will schedule the email for this time.
* You always have the option to choose a new "send at" time when you are kicking off your Sales Campaign.

### Create a task; I will send this email myself {#subsequent-create-a-task}

* This option will create an Email Task (and sync to [!DNL Salesforce]) that you can send at your convenience.
* Once you've made this selection, when you kick off your Sales Campaign, [!DNL Sales Insight Actions] will queue these tasks up for you in Command Center and the Live Feed. You can then personalize and send (or schedule) each email before it goes out.

  * If you open this task in our web application, it will open a compose window with your contact's email address, the subject line of your email, and the template you chose.
  * If you open this task in Gmail or [!DNL Outlook], it will open a native compose window and dynamically populate your contact's email address, the subject line of your email, and the template you chose.

### Create this email as a follow up to the previous email in this campaign {#subsequent-create-this-email}

* Enable this checkbox if you'd like the previous email in your sales campaign to be appended to the next email that your sales campaign sends out.
* For the appended copy of the email, the email template in your sales campaign will always be sent out. Any edits the user may have made before it was sent out will not be included in the send.

>[!NOTE]
>
>This option to create an email as follow-up will only be available on an email step, when the previous step is also an email. If the previous step is Call, InMail, or Custom, the option to create a follow-up will not appear.

>[!MORELIKETHIS]
>
>[Create a Sales Campaign](/help/marketo/product-docs/marketo-sales-insight/actions/campaigns/create-a-sales-campaign.md){target="_blank"}
>[Sales Campaign Step Types and Reminder Tasks](/help/marketo/product-docs/marketo-sales-insight/actions/campaigns/sales-campaign-step-types-and-reminder-tasks.md){target="_blank"}
>[Sales Campaign Settings](/help/marketo/product-docs/marketo-sales-insight/actions/campaigns/sales-campaign-settings.md){target="_blank"}

