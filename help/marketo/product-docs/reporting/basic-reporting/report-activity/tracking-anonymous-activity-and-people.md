---
unique-page-id: 2360181
description: Learn about tracking anonymous activity and people in Marketo Engage, including tracking anonymous activity and. Use this guide to complete your next step.
title: Tracking Anonymous Activity and People
exl-id: 95a39e57-4636-4bae-8ca8-00cb43cb566c
feature: Reporting
TQID: https://experienceleague.adobe.com/BZakQFVtQystRyrlzo81s-p8N65LXHUJ2ZoSAzeTG6Q
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Tracking Anonymous Activity and People {#tracking-anonymous-activity-and-people}

The first time someone visits a Marketo [landing page](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) (or a page on your website that has the [Munchkin tracking code](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)), Marketo creates an _anonymous activity_ and uses a browser cookie to track it. Once the visitor is identified, it becomes a person and the history associated with the browser cookie is merged in.

1. An anonymous activity is created when someone:

    * Visits your Marketo [landing page](/help/marketo/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) the first time.
    * Visits a page on your site that has [Munchkin tracking](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
    * Clicks the [View as Web Page](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) link in a Marketo email.

   >[!NOTE]
   >
   >Unlike other links in Marketo emails, View as Web Page is not tracked as an email click.

   An anonymous activity is merged into a new or existing person when someone:

    * Clicks a [link in a Marketo email](/help/marketo/product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md).
    * Fills out a Marketo [form](/help/marketo/product-docs/demand-generation/forms/creating-a-form/create-a-form.md).
    * Uses Marketo's [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/leads) or [Munchkin](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/javascriptapi/leadtracking/lead-tracking) API (for developers) to associate an anonymous activity with a known record.

   One name in the database might be tied to many cookies because people often use different devices and browsers to visit your site.

   >[!NOTE]
   >
   >When anonymous records are merged into a new or existing person record, custom field values will **not** transfer over.

   >[!MORELIKETHIS]
   >
   >[Display People or Anonymous Visitors in Web Reports](/help/marketo/product-docs/reporting/basic-reporting/report-activity/display-people-or-anonymous-visitors-in-web-reports.md)
