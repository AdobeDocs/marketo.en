---
unique-page-id: 10094576
description: Durable Unsubscribe - Marketo Docs - Product Documentation
title: Durable Unsubscribe
exl-id: e03a5a01-7395-45b3-8351-7931ec413236
feature: Deliverability
---
# Durable Unsubscribe {#durable-unsubscribe}

Marketo has enhanced the behavior of the unsubscribe functionality to make it “durable." We've added a master email status, which is separate from the unsubscribe flag visible on the person detail record.

If the unsubscribe flag is set from false to true, the master email status is updated, and the change is propagated to other people with the same email address. If a person is removed and recreated, or if a new record is created with the same email address, the unsubscribe flag will **not** be overwritten.

>[!NOTE]
>
>Durable Unsubscribe works across all partitions in your entire Marketo database.

## Update the Unsubscribe Flag from True to False (e.g., Re-subscribe a Person) {#update-the-unsubscribe-flag-from-true-to-false-e-g-re-subscribe-a-person}

There are several ways a person can be re-subscribed.

In Salesforce, **clear** the Email Opt Out field on the lead/contact's record. This will sync to Marketo.

![](assets/one.png)

In Marketo, **clear** the unsubscribed box in the Info tab of the person's record.

![](assets/two.png)

Run a **Change Data Value** flow step as shown below on one or many people.

![](assets/three.png)

Update an existing person via SOAP API.

## Creating a New Person {#creating-a-new-person}

When a new person is created, Marketo checks it against the master email status table. If the person was previously unsubscribed, we'll update the record to be unsubscribed.

## Changing an Email Address {#changing-an-email-address}

If you change the email address of a person to an unsubscribed email address, that person will be unsubscribed. This change can occur in either Marketo or Salesforce.

If you change an unsubscribed email address to one that is subscribed, that person will become subscribed.

## Re-subscribing {#re-subscribing}

Just as an unsubscribe would cause all people with the same email address to become unsubscribed, a resubscribe would in fact resubscribe every person with the same email address.

## Activity Log {#activity-log}

Data Value Change definitions for _updateLeadEmailStatus_ and _resetLeadEmailStatus_ can be found in [this Community article](https://nation.marketo.com/t5/Knowledgebase/Durable-Unsubscribe-Activity-Log/ta-p/252688).

>[!MORELIKETHIS]
>
>[Understanding Unsubscribe](/help/marketo/product-docs/email-marketing/deliverability/understanding-unsubscribe.md)
