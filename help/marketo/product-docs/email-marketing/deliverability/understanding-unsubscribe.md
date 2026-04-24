---
unique-page-id: 7514918
description: "Learn about unsubscribe types in Marketo (Unsubscribed, Marketing Suspended, Blocklisted). Use the right field for each scenario in your campaigns."
title: Understanding Unsubscribe
exl-id: 30866dc0-cdac-4e73-8dbf-d4b509012269
feature: Deliverability
---
# Understanding Unsubscribe {#understanding-unsubscribe}

There are actually several different types of built-in unsubscribes in Marketo. They're all represented by fields on the person object, just like First Name.

All of these fields are built-in to your Marketo subscription. They are all boolean (checkbox) type. They can be used in Forms or [Change Data Value](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) flow steps.

## Unsubscribed {#unsubscribed}

This is used on the standard unsubscribe page. If a person checks this box, or clicks the unsubscribe link in an email, they will no longer receive marketing emails. They will, however, receive [operational emails](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

## Marketing Suspended {#marketing-suspended}

This field is set by the user for placing people on a temporary unsubscribe. People can only attain this status if they are manually changed or a change data value flow step is utilized.

## Email Suspended {#email-suspended}

This status blocks a person from mailings for 24 hours after a hard bounce occurs. After 24 hours, the person will become mailable again.

>[!NOTE]
>
>Email Suspended will remain checked even after the 24 hour period is over, so you can refer to people who have historically been marked as such. To see if the person is mailable, simply calculate 24 hours after the moment of email suspension.

## Blocklisted {#blocklisted}

[Use this for people like competitors](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.md). Anyone you want receiving **no** emails—operational, marketing, etc. They get nothing!

## One-Click Unsubscribe (List-Unsubscribe) {#one-click-unsubscribe}

>[!IMPORTANT]
>
>As of February 2024, Gmail and Yahoo require bulk senders (5,000+ messages/day) to support one-click unsubscribe via the `List-Unsubscribe-Post` header (RFC 8058). This allows recipients to unsubscribe directly from the email client without visiting a landing page.

Marketo Engage automatically includes the `List-Unsubscribe` header in outgoing emails. The `List-Unsubscribe-Post` header enables one-click unsubscribe directly in the inbox (the "Unsubscribe" button in Gmail, Yahoo, etc.). When a recipient uses this button, Marketo sets the person's **Unsubscribed** field to true.

>[!NOTE]
>
>One-click unsubscribe is separate from the unsubscribe link in your email body. Even if your email template includes an unsubscribe link, the List-Unsubscribe header provides an additional unsubscribe mechanism at the mail-client level that recipients may use instead.

>[!TIP]
>
>To verify that your emails include the proper headers, send a test email to a Gmail address and view the original message headers (three-dot menu > Show Original). Look for both `List-Unsubscribe` and `List-Unsubscribe-Post` headers.

![](assets/image2015-5-18-12-3a6-3a40.png)
