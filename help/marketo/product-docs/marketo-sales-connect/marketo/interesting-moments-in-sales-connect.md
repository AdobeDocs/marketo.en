---
unique-page-id: 30082174
description: Interesting Moments in Sales Connect - Marketo Docs - Product Documentation
title: Interesting Moments in Sales Connect
exl-id: 210f31d1-606a-479d-8a2b-351b2b1a7678
feature: Marketo Sales Connect
---
# Interesting Moments in Sales Connect {#interesting-moments-in-sales-connect}

Interesting moments are the key to communicating with your sales team through Marketo Sales Connect.

>[!AVAILABILITY]
>
>These are available to [Marketo Sales Insight](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/interesting-moments/using-interesting-moments.md) and Marketo Sales Connect customers only.

>[!PREREQUISITES]
>
>* You must have a [connection to the Salesforce CRM](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-integration/connect-your-sales-connect-account-to-salesforce.md){target="_blank"}
>* You must be the lead or contact owner in Salesforce
>* You must have access to [grant access to the Marketo Engage connection](/help/marketo/product-docs/marketo-sales-connect/marketo/granting-access-to-users.md){target="_blank"}

## What is an interesting moment? {#what-is-an-interesting-moment}

That's up to you! You decide what information is relevant to your sales team. Your sales team might want to know when a lead:

* Visits the pricing page on your website
* Clicks a link in a new product announcement email
* Requests a product demo

## How do I create an interesting moment? {#how-do-i-create-an-interesting-moment}

1. Choose a [smart campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md), preferably one your sales team would find interesting if triggered.

   ![](assets/image2015-1-8-18-3a8-3a54.png)

1. Drag over the **Interesting Moments** flow step.

   ![](assets/image2015-1-8-18-3a15-3a20.png)

1. Select a **type** (Email, Milestone, or Web).

   ![](assets/image2015-1-8-18-3a17-3a16.png)

1. Write a message to your sales team in the **Description** field that explains why this action matters.

   ![](assets/image2015-1-8-18-3a18-3a23.png)

   >[!NOTE]
   >
   >Marketo will also add the date it occurred and how the interesting moment was added (i.e lead action > flow step, SOAP API).

## What does an interesting moment look like in Marketo?  {#what-does-an-interesting-moment-look-like-in-marketo}

Interesting moments will be displayed in a [lead's activity log](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md).

![](assets/image2015-1-14-18-3a45-3a58.png)

## What does an interesting moment look like in Sales Connect? {#what-does-an-interesting-moment-look-like-in-sales-connect}

Interesting Moments will be displayed in real time in a user's Live Feed. We utilize the lead owner ID in Salesforce to show users' interesting moments of relevant leads that they're the owner of. Users can quickly follow up with leads via email/phone/sales campaign by clicking the drop-down next to the lead's name.

![](assets/engagement.jpg)
