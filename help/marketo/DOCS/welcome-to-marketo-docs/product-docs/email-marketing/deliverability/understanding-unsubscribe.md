---
unique-page-id: 7514918
description: Understanding Unsubscribe - Marketo Docs - Product Documentation
title: Understanding Unsubscribe
---

# Understanding Unsubscribe {#understanding-unsubscribe}

Understanding Unsubscribe - Marketo Docs - Product Documentation

There are actually several different types of built-in unsubscribes in Marketo. They're all represented by fields on the person object, just like First Name.

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

### What's in this article? {#what-s-in-this-article}

[Unsubscribed](#understandingunsubscribe-unsubscribed)  
[Marketing Suspended](#understandingunsubscribe-marketingsuspended)  
[Email Suspended](#understandingunsubscribe-emailsuspended)  
[Blacklisted](#understandingunsubscribe-blacklisted)

>[!NOTE]
>
>All of these fields are built-in to your Marketo subscription. They are all boolean (checkbox) type. They can be used in Forms or [Change Data Value](../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) flow steps.

#### Unsubscribed {#understandingunsubscribe-unsubscribed}

This is used on the standard unsubscribe page. If a person checks this box, or clicks the unsubscribe link in an email, they will no longer receive marketing emails. They will, however, receive [operational emails](../../../../welcome-to-marketo-docs/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md).

#### Marketing Suspended {#understandingunsubscribe-marketingsuspended}

This field is set by the user for placing people on a temporary unsubscribe. People can only attain this status if they are manually changed or a change data value flow step is utilized.

#### Email Suspended {#understandingunsubscribe-emailsuspended}

This status blocks a person from mailings for 24 hours after a hard bounce occurs. After 24 hours, the person will become mailable again.

>[!NOTE]
>
>Email Suspended will remain checked even after the 24 hour period is over, so you can refer to people who have historically been marked as such. To see if the person is mailable, simply calculate 24 hours after the moment of email suspension.

#### Blacklisted {#understandingunsubscribe-blacklisted}

Use this for competitors. They will receive neither operational nor marketing emails. They get nothing!

![](assets/image2015-5-18-12-3a6-3a40.png)

