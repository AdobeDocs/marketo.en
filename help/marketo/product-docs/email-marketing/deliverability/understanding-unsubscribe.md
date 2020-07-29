---
unique-page-id: 7514918
description: Understanding Unsubscribe - Marketo Docs - Product Documentation
title: Understanding Unsubscribe
---

# Understanding Unsubscribe {#understanding-unsubscribe}

There are actually several different types of built-in unsubscribes in Marketo. They're all represented by fields on the person object, just like First Name.

>[!NOTE]
>
>Marketo is in the process of changing terms such as Blacklist and Whitelist to Blocklist and Allowlist in our product. During this update, you may see the old terms in our UI and documentation screenshots, and the new terms in our documentation text. We apologize for any confusion.

### What's in this article? {#whats-in-this-article}

[Unsubscribed](#unsubscribed)  
[Marketing Suspended](#marketing-suspended)  
[Email Suspended](#email-suspended)  
[Blocklisted](#blocklisted)

##### All of these fields are built-in to your Marketo subscription. They are all boolean (checkbox) type. They can be used in Forms or [Change Data Value](../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) flow steps. {#all-of-these-fields-are-built-in-to-your-marketo-subscription-they-are-all-boolean-checkbox-type-they-can-be-used-in-forms-or-change-data-value-flow-steps}

#### Unsubscribed {#unsubscribed}

This is used on the standard unsubscribe page. If a person checks this box, or clicks the unsubscribe link in an email, they will no longer receive marketing emails. They will, however, receive [operational emails](../../../product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

#### Marketing Suspended {#marketing-suspended}

This field is set by the user for placing people on a temporary unsubscribe. People can only attain this status if they are manually changed or a change data value flow step is utilized.

#### Email Suspended {#email-suspended}

This status blocks a person from mailings for 24 hours after a hard bounce occurs. After 24 hours, the person will become mailable again.

>[!NOTE]
>
>Email Suspended will remain checked even after the 24 hour period is over, so you can refer to people who have historically been marked as such. To see if the person is mailable, simply calculate 24 hours after the moment of email suspension.

#### Blocklisted {#blocklisted}

[Use this for people like competitors](http://docs.marketo.com/x/uwOQ). Anyone you want receiving **no** emails—operational, marketing, etc. They get nothing!

![](assets/image2015-5-18-12-3a6-3a40.png)

