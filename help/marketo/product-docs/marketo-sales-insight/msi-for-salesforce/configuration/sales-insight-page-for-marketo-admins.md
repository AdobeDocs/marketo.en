---
unique-page-id: 42762409
description: Sales Insight Page for Marketo Admins - Marketo Docs - Product Documentation
title: Sales Insight Page for Marketo Admins
exl-id: d98bc9d8-1a72-405f-b1d7-b71ad88c8493
feature: Marketo Sales Insights
---
# Sales Insight Page for Marketo Admins {#sales-insight-page-for-marketo-admins}

Marketo Admins have certain privileges in Sales Insight. Learn what they are below.

## Soap API Configuration {#soap-api-configuration}

These credentials are used to connect your Salesforce account to your Marketo instance, in order to use MSI in Salesforce.

![](assets/one-1.png)

## Rest API Configuration {#rest-api-configuration}

These credentials are used to connect your Salesforce account to your Marketo instance, in order to use MSI Insights Dashboard in Salesforce.

![](assets/two-1.png)

## Person Score Settings {#person-score-settings}

* **Stars**: Stars represent total lead score compared to other leads.
* **Flames**: Flames represent urgency - how much a lead's score has changed recently.

By default, Marketo Sales Insight uses the Lead Score field to calculate stars and flames. But if you want to pick a different field, here's how:

1. In the **Admin** area of Marketo, click **Sales Insight**.

   ![](assets/four.png)

1. Under Lead Scoring Settings, click **Edit**.

   ![](assets/five.png)

1. Select the field you want to use for stars.

   ![](assets/six.png)

1. Select the field you want to use for flames.

   ![](assets/seven.png)

1. Click **Save**. Sales insight will take some time to re-calculate. You can check your CRM later to see the stars and flames.

   ![](assets/eight.png)

   >[!TIP]
   >
   >If you don't already have your custom score fields, here's how to [create them](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md).

   >[!MORELIKETHIS]
   >
   >[Stars and Flames](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/customize-stars-and-flames.md)

## Settings {#settings}

![](assets/nine.png)

**Unsubscribe Settings:**

You can choose the from following unsubscribe settings for No Template, Standard Emails & Operational emails

* Respect Unsubscribe Setting
* Respect Unsubscribe Settings when more than 1 recipient
* Respect Unsubscribe Settings when more than 5 recipients
* Ignore Unsubscribe Settings

**Enable ability to lock templates:**

When enabled, MSI users will not be able to edit templates while sending emails from Salesforce

**Enable RSS Feed:**

When enabled, MSI users can view their Lead Feed in an RSS feed (in addition to the Lead Feed in Salesforce). RSS feed can only function if the “Token Expiration” feature is disabled.

**Token Expiration:**

Token Expiration is controlled in the Feature Manager. To have it enabled/disabled, reach out to [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support). When enabled, all Marketo tokens expire within 10 minutes. When disabled, Marketo tokens will not expire.

Tokens generated before enabling Token Expiration will not have an expiration time to validate against, so they won't expire even if the feature is currently enabled.

Tokens generated after enabling Token Expiration will have an expiration time of 10 minutes, so they'll still expire in 10 minutes even after the feature is disabled.

Token behavior will be based on when it was generated (when the Token Expiration feature was enabled/disabled, rather than its current feature status).
