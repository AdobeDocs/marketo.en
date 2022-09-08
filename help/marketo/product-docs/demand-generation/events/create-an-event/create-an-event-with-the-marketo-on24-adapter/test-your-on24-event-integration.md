---
unique-page-id: 10096677
description: Test Your ON24 Event Integration - Marketo Docs - Product Documentation
title: Test Your ON24 Event Integration
exl-id: 8326b81e-abf7-4615-9a0b-b0a579be8bb8
---
# Test Your ON24 Event Integration {#test-your-on-event-integration}

>[!IMPORTANT]
>
>As of August 2022, ON24 no longer supports new Marketo integrations. The information in this article only applies to existing users.

Make sure to test your event integration thoroughly.

## Recommended Test Sequence Before Running Your First Campaign {#recommended-test-sequence-before-running-your-first-campaign}

1. Fill out the event's registration form and use a valid email address to test.
1. Confirm the test name shows with a **Registered** status in the Membership grid of your Marketo event.
1. Confirm the test name also shows as **Registered** in ON24.
1. Confirm that the valid email address you used to register the test name received a confirmation email to the Event and that the unique URL is resolved in the email.

   >[!NOTE]
   >
   >You must use the `{{member.webinar url}}` token in your confirmation email in order for the unique URL to show in each registrant’s email.

## After the Event {#after-the-event}

Here’s how data is updated after the event takes place:

* Marketo retrieves attendee data from ON24 every night.
* Once the attendee data syncs between Marketo and ON24, Marketo updates the membership status to Attended, Attended On-demand, or No Show. In the event's **Summary** tab, the event status is updated to **Event Complete**.

>[!MORELIKETHIS]
>
>* [Example ON24 Event Integration](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/example-on24-event-integration.md)
>* [Understanding Marketo ON24 Adapter Events](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md)
