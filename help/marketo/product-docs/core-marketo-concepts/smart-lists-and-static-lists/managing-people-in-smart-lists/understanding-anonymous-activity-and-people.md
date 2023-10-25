---
unique-page-id: 1147322
description: Understanding Anonymous Activity and People - Marketo Docs - Product Documentation
title: Understanding Anonymous Activity and People
exl-id: 1676e8f3-9138-42ed-8bb4-40e195391fc4
feature: Smart Lists
---
# Understanding Anonymous Activity and People {#understanding-anonymous-activity-and-people}

The first time someone visits a Marketo landing page (or a page on your website that has the [Munchkin Tracking Code](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}), Marketo creates an *anonymous activity* and uses a browser cookie to track it. Once it's identified, it becomes a person and the history associated with their browser cookie is merged in.

>[!IMPORTANT]
>
>Enabling the Beta Feature **Munchkin V2 Anonymous Replay Activity on Known** ensures that campaigns triggered by anonymous lead promotion will always be replayed after the anonymous lead is successfully merged into the known record. As a result, custom fields changed by Change Data Value steps in any replayed campaigns will be retained in the known record.

**An Anonymous** activity is created when someone:

* Visits your Marketo landing page the first time.
* Visits a page on your site that has [Munchkin tracking](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"}.
* Clicks the [View as Web Page](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} link in a Marketo email.

>[!NOTE]
>
>Unlike other links in Marketo emails, [View as Web Page](/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/add-a-view-as-web-page-link-to-an-email.md){target="_blank"} is not tracked as an email click.

An anonymous activity is merged into a new or existing person when someone:

* Clicks a [link in a Marketo email](/help/marketo/product-docs/email-marketing/general/using-tokens/add-a-system-token-as-a-link-in-an-email.md){target="_blank"}.
* Fills out a Marketo [Form](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md){target="_blank"}.
* Uses Marketo's [SOAP](/help/marketo/product-docs/administration/additional-integrations/configuring-your-soap-api-settings.md){target="_blank"} or [Munchkin](/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md){target="_blank"} API (for developers) to associate an anonymous person with a known record.

One name in the database might be tied to many cookies because people often use different devices and browsers to visit your site.

>[!NOTE]
>
>When anonymous records are merged into a new or existing person record, custom field values will *not* transfer over.
