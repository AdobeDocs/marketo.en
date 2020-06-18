---
unique-page-id: 10096677
description: Test Your ON24 Event Integration - Marketo Docs - Product Documentation
title: Test Your ON24 Event Integration
---

# Test Your ON24 Event Integration {#test-your-on-event-integration}

Test Your ON24 Event Integration - Marketo Docs - Product Documentation

Make sure to test your event integration thoroughly.

### What's in this article? {#what-s-in-this-article}

[Recommended Test Sequence Before Running Your First Campaign](#testyouron24eventintegration-recommendedtestsequencebeforerunningyourfirstcampaign)  
[After the Event](#testyouron24eventintegration-aftertheevent)

#### Recommended Test Sequence Before Running Your First Campaign {#testyouron24eventintegration-recommendedtestsequencebeforerunningyourfirstcampaign}

1. Fill out the event's registration form and use a valid email address to test.
1. Confirm the test name shows with a **Registered** status in the Membership grid of your Marketo event.
1. Confirm the test name also shows as **Registered** in ON24.
1. Confirm that the valid email address you used to register the test name received a confirmation email to the Event and that the unique URL is resolved in the email.

   >[!NOTE]
   >
   >You must use the {{member.webinar url}} token in your confirmation email in order for the unique URL to show in each registrant’s email.

#### After the Event {#testyouron24eventintegration-aftertheevent}

Here’s how data is updated after the event takes place:

* Marketo retrieves attendee data from ON24 every night.
* Once the attendee data syncs between Marketo and ON24, Marketo updates the membership status to Attended, Attended On-demand, or No Show. In the event's **Summary** tab, the event status is updated to **Event Complete**.

>[!NOTE]
>
>**Related Articles**
>
>* [Example ON24 Event Integration](example-on24-event-integration.md)
>* [Understanding Marketo ON24 Adapter Events](understanding-marketo-on24-adapter-events.md)
>

&nbsp; 