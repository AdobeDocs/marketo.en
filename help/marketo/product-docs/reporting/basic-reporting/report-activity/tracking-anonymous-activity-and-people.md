---
unique-page-id: 2360181
description: Tracking Anonymous Activity and People - Marketo Docs - Product Documentation
title: Tracking Anonymous Activity and People
exl-id: 95a39e57-4636-4bae-8ca8-00cb43cb566c
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
    * Uses Marketo's [REST API](https://developers.marketo.com/rest-api/lead-database/leads/) or [Munchkin](https://developers.marketo.com/documentation/websites/lead-tracking-munchkin-js/) API (for developers) to associate an anonymous activity with a known record.

   One name in the database might be tied to many cookies because people often use different devices and browsers to visit your site.

   >[!NOTE]
   >
   >When anonymous records are merged into a new or existing person record, custom field values will **not** transfer over.

   >[!MORELIKETHIS]
   >
   >[Display People or Anonymous Visitors in Web Reports](/help/marketo/product-docs/reporting/basic-reporting/report-activity/display-people-or-anonymous-visitors-in-web-reports.md)
