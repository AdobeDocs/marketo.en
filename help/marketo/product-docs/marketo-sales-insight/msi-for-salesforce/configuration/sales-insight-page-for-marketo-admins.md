---
unique-page-id: 42762409
description: Learn about the Sales Insight page for Marketo admins. Access Actions Config and MSI settings.
title: Sales Insight Page for Marketo Admins
exl-id: d98bc9d8-1a72-405f-b1d7-b71ad88c8493
feature: Marketo Sales Insights
TQID: https://experienceleague.adobe.com/FTOgWRDvY14tovIUclyWrED5DBXcHXH8APcprG-DlK4
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
    internal-label: Configuration
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
topic_v2:
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# [!DNL Sales Insight] Page for Marketo Admins {#sales-insight-page-for-marketo-admins}

Marketo Admins have certain privileges in [!DNL Sales Insight]. Learn what they are below.

## Soap API Configuration {#soap-api-configuration}

These credentials are used to connect your [!DNL Salesforce] account to your Marketo instance, in order to use MSI in [!DNL Salesforce].

![](assets/one-1.png)

## Rest API Configuration {#rest-api-configuration}

These credentials are used to connect your [!DNL Salesforce] account to your Marketo instance, in order to use MSI Insights Dashboard in [!DNL Salesforce].

![](assets/two-1.png)

## Person Score Settings {#person-score-settings}

* **[!UICONTROL Stars]**: Stars represent total lead score compared to other leads.
* **[!UICONTROL Flames]**: Flames represent urgency - how much a lead's score has changed recently.

By default, [!DNL Marketo Sales Insight] uses the Lead Score field to calculate stars and flames. But if you want to pick a different field, here's how:

1. In the **[!UICONTROL Admin]** area of Marketo, click **[!UICONTROL Sales Insight]**.

   ![](assets/four.png)

1. Under [!UICONTROL Lead Scoring Settings], click **[!UICONTROL Edit]**.

   ![](assets/five.png)

1. Select the field you want to use for stars.

   ![](assets/six.png)

1. Select the field you want to use for flames.

   ![](assets/seven.png)

1. Click **[!UICONTROL Save]**. Sales insight will take some time to re-calculate. You can check your CRM later to see the stars and flames.

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

You can choose the from following unsubscribe settings for [!UICONTROL No Template], [!UICONTROL Standard Emails] & [!UICONTROL Operational emails]

* [!UICONTROL Respect Unsubscribe Setting]
* [!UICONTROL Respect Unsubscribe Settings when more than 1 recipient]
* [!UICONTROL Respect Unsubscribe Settings when more than 5 recipients]
* [!UICONTROL Ignore Unsubscribe Settings]

**Enable ability to lock templates:**

When enabled, MSI users will not be able to edit templates while sending emails from [!DNL Salesforce]

**Enable RSS Feed:**

When enabled, MSI users can view their Lead Feed in an RSS feed (in addition to the Lead Feed in [!DNL Salesforce]). RSS feed can only function if the “[!UICONTROL Token Expiration]” feature is disabled.

**Token Expiration:**

Token Expiration is controlled in the Feature Manager. To have it enabled/disabled, reach out to [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support). When enabled, all Marketo tokens expire within 10 minutes. When disabled, Marketo tokens will not expire.

Tokens generated before enabling Token Expiration will not have an expiration time to validate against, so they won't expire even if the feature is currently enabled.

Tokens generated after enabling Token Expiration will have an expiration time of 10 minutes, so they'll still expire in 10 minutes even after the feature is disabled.

Token behavior will be based on when it was generated (when the Token Expiration feature was enabled/disabled, rather than its current feature status).
