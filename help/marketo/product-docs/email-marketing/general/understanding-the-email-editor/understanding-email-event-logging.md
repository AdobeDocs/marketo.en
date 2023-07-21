---
unique-page-id: 1147356
description: Understanding Email Event Logging - Marketo Docs - Product Documentation
title: Understanding Email Event Logging
exl-id: 107d7f4a-ad38-44e4-95d8-760539aacede
feature: Email Editor
---
# Understanding Email Event Logging {#understanding-email-event-logging}

When sending emails, Marketo logs different data points to the person's activity logs. Here are the basic ones.

| Event |Description |
|---|---|
| Sent |Is logged every time an email is sent from the Marketo servers regardless of if it is actually delivered. Bounced emails are still logged as "Sent." |
| Delivered |Is logged every time an email is accepted by the recipient mail server. This does not mean it avoided spam filters. There can only be 1 delivery for each sent email. |
| Hard Bounced |Some hard bounces are a result of spam blocks, so we won't try to email that person for 24 hours in any campaign. Other hard bounces like non-existent inboxes are permanent, and we will never email the person again from any campaign. |
| Soft Bounced |Is logged when a server response is unclear, mailbox full or general server issues. We do put these people through a retry logic for 24-36 hours for potential future delivery. This does not disqualify the person from other mailings. |
| Opened |Is logged when a recipient views an email with images NOT blocked. Only one open event per email, per person, per smart campaign is logged. If they open the same email from their inbox twice, it will not be logged more than once. |
| Clicked |Is logged every time a decorated URL from the email is loaded in the browser (the result of clicking the link). Usually this is the recipient clicking, but can also be a cut/paste. |
| Unsubscribed |Is logged when a person clicks on the unsubscribe link of an email and submits the unsubscribe form. |

>[!CAUTION]
>
>If the same email is sent to the same person twice from the same campaign, the **Opened** event will be logged a maximum of 1 time.
