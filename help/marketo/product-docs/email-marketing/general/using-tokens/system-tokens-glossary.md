---
unique-page-id: 1147344
description: System Tokens Glossary - Marketo Docs - Product Documentation
title: System Tokens Glossary
exl-id: 8a7694af-4edb-4b32-b408-19d2e7bd596e
---
# System Tokens Glossary {#system-tokens-glossary}

In addition to person tokens, you can use some really cool system tokens. Here they are.

>[!NOTE]
>
>Your account time zone settings affect when date and time tokens run.

## system.date {#system-date}

The `{{system.date}}` token will render current date at runtime like so: **Aug 08, 2013**

**Works in:**

* [Change Data Value](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) flow step
* [Interesting Moment](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md) flow step
* [Create Task](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) flow step
* The body of an email or template

## system.time {#system-time}

The `{{system.time}}` token will render the current time at runtime like so: **04:34 PM (GMT -0700)**

**Works in:**

* [Change Data Value](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) flow step
* [Interesting Moment](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md) flow step
* [Create Task](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) flow step
* The body of an email or template

## system.dateTime {#system-datetime}

The `{{system.dateTime}}` token will render the current date and time at runtime like so: **2013-08-08 16:36:13**

**Works in:**

* [Change Data Value](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) flow step
* [Interesting Moment](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md) flow step
* [Create Task](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/salesforce-flow-actions/create-task.md) flow step
* The body of an email or template

## system.forwardToFriendLink {#system-forwardtofriendlink}

The `{{system.forwardToFriendLink}}` token allows you to control the placement of the ['Forward to a Friend Link' in Emails](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/forward-to-a-friend-link-in-emails.md).

**Works in:**

* [Add a System Token as a Link in an Email](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md) or template

## system.unsubscribeLink {#system-unsubscribelink}

The `{{system.unsubscribeLink}}` token allows you to control the placement of the unsubscribe link in an email.

**Works in:**

* [Add a System Token as a Link in an Email](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md) or template

## system.viewAsWebpageLink {#system-viewaswebpagelink}

The `{{system.viewAsWebpageLink}}` token allows you to control the placement of the View as Web Page link in an email.

**Works with:**

* [Add a System Token as a Link in an Email](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md) or template
