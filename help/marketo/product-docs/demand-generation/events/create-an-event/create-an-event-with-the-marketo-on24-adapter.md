---
unique-page-id: 10096656
description: Create an Event with the Marketo ON24 Adapter - Marketo Docs - Product Documentation
title: Create an Event with the Marketo ON24 Adapter
exl-id: a240ff72-b12f-4e3a-8e14-94fddb02f944
---
# Create an Event with the Marketo ON24 Adapter {#create-an-event-with-the-marketo-on-adapter}

>[!IMPORTANT]
>
>As of August 2022, ON24 no longer supports new Marketo integrations. The information in this article only applies to existing users.

You should be familiar with the building blocks and the recommended sequence for creating Events in Marketo. You should also have working knowledge of the following Marketo concepts:

* [Marketo Programs](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md) as well as Events, and the differences between them
* [Channels](/help/marketo/product-docs/administration/tags/create-a-program-channel.md)
* [Local Assets](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-local-assets-in-a-program.md)
* [Child Campaigns](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md) and [Program Statuses](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md)

>[!NOTE]
>
>Please refer to the [Marketo API documentation](https://developers.marketo.com/documentation/rest/) for more information on Marketo APIs.

## Prerequisites {#prerequisites}

The following are required to use the Marketo ON24 integration:

* **Subscription to ON24 webcasts** - If you do not have a current subscription, contact ON24 directly. **NOTE**: ON24 Hosted Edition is required. ON24 Event Management is not required.

* **Administrator rights to ON24** - You'll need this to use this connector and create guests in the ON24 system.
* **ON24 connection credentials** - You'll need to enter this information into Marketo to enable the integration: Username, Password, Client ID, and Client Key. Contact your ON24 Account Manager or ON24 Support if you need help with your credentials.
* **Registration form** - Use a Marketo form or a non-Marketo form along with the proper API to ensure registration data and registrant info is passed to Marketo.
* **Registration child campaign** - A registration child campaign in your Marketo Event must be created and configured properly for your Event Partner integration to work.

## Process Flow {#process-flow}

Follow these steps to create an Event with the Marketo On24 Adapter:

1. [Create Your Webinar Event in ON24](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-your-webinar-event-in-on24.md)
1. [Configure Event Settings and Sync Marketo with Your Webinar](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/configure-event-settings-and-sync-marketo-with-your-webinar.md)
1. [Create Child Campaigns and Local Assets](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/create-child-campaigns-and-local-assets.md)
1. [Test Your ON24 Event Integration](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/test-your-on24-event-integration.md)
1. [Example ON24 Event Integration](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md)
1. [Understanding Webinar Program Statuses](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-webinar-program-statuses.md)
1. [ON24 Event Registration Updates](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/on24-event-registration-updates.md)
