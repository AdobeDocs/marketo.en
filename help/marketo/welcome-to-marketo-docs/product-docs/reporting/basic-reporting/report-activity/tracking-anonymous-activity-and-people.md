---
unique-page-id: 2360181
description: Tracking Anonymous Activity and People - Marketo Docs - Product Documentation
title: Tracking Anonymous Activity and People
---

# Tracking Anonymous Activity and People {#tracking-anonymous-activity-and-people}

Tracking Anonymous Activity and People - Marketo Docs - Product Documentation

The first time someone visits a Marketo [landing page](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) (or a page on your website that has the [Munchkin tracking code](../../../../../welcome-to-marketo-docs/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md)), Marketo creates an *anonymous* *activity* and uses a browser cookie to track it. Once the visitor is identified, it becomes a person and the history associated with the browser cookie is merged in.

1. An anonymous activity is created when someone:

    * Visits your Marketo [landing page](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/landing-pages/free-form-landing-pages/create-a-free-form-landing-page.md) the first time.
    * Visits a page on your site that has [Munchkin tracking](../../../../../welcome-to-marketo-docs/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md).
    * Clicks the [View as Web Page](../../../../../welcome-to-marketo-docs/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md) link in a Marketo email.

   >[!NOTE]
   >
   >`Unlike other links in Marketo emails,` [View as Web Page](#) `is not tracked as an email click.`

   An anonymous activity is merged into a new or existing person when someone:

    * Clicks a [link in a Marketo email](../../../../../welcome-to-marketo-docs/product-docs/email-marketing/general/using-tokens/add-tokens-to-an-email-link.md).
    * Fills out a Marketo [form](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/forms.md).
    * Uses Marketo's [SOAP](http://developers.marketo.com/documentation/soap/synclead/) or [Munchkin](http://developers.marketo.com/documentation/websites/lead-tracking-munchkin-js/) API (for developers) to associate an anonymous activity with a known record.

   One name in the database might be tied to many cookies because people often use different devices and browsers to visit your site.

   >[!NOTE]
   >
   >When anonymous records are merged into a new or existing person record, custom field values will **not** transfer over.

   >[!NOTE]
   >
   >**Related Articles**
   >
   >    
   >    
   >    * [Display People or Anonymous Visitors in Web Reports](display-people-or-anonymous-visitors-in-web-reports.md)
   >    
   >

   >[!NOTE]
   >
   >**Deep Dive**
   >
   >
   >`Learn more about` [Basic Reporting](../../../../../welcome-to-marketo-docs/product-docs/reporting/basic-reporting.md) `.`

