---
unique-page-id: 12983291
description: Understanding Recipient Time Zone - Marketo Docs - Product Documentation
title: Understanding Recipient Time Zone
exl-id: 8895241e-94c9-43a2-9158-11c1994df09b
feature: Email Programs
---
# Understanding Recipient Time Zone {#understanding-recipient-time-zone}

Email and engagement programs can be configured to be delivered according to recipients' time zones, eliminating the need to create multiple programs—send once and Marketo automatically holds the email until the correct local time.

>[!NOTE]
>
>Recipient Time Zone currently works **only** with email content. It will not work for default engagement programs.

## Email Programs {#email-programs}

There are two primary scenarios when [scheduling an email program](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md):

1. Scheduling the program to run within the next 25 hours.
1. Scheduling the program to run more than 25 hours in the future (i.e., next week).

In order to accommodate every time zone, email programs scheduled with Recipient Time Zone start running at midnight in the **first/earliest** time zone in the world (UTC +14:00).

## Engagement Programs {#engagement-programs}

When you [schedule an engagement program stream](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md) and Recipient Time Zone is active, the program cast will start running at midnight in UTC +14:00. We require you to schedule the first cast at least 25 hours in the future (24 hours + some time to get the campaign started) because people may qualify for the cast in every time zone across the globe. Starting processing at this time in UTC +14:00 guarantees that we'll send the email at the scheduled date and time for every person who qualifies for this cast.

## Calculating Time Zone {#calculating-time-zone}

Marketo calculates time zone based on a person's City, State, Country, or Zip Code. If we're unable to calculate someone's time zone from these values, we revert to our Inferred City, Inferred State, Inferred Country and Inferred Zip Code fields.

In cases where we have **only** Country or **only** State available:

* For countries with three or fewer time zones, we select the middle time zone.
* For states with two time zones, we select the earlier of the two.

If we're still unable to determine someone's time zone from any combination of these fields, we will **not** assign a time zone and the email will be sent based on your Marketo subscription time zone. So, if your program is scheduled for 9:00am PDT, people with no assigned time zone will be sent the email at 9:00am PDT.

>[!NOTE]
>
>Marketo automatically re-calculates a person's time zone when any of the above input fields change.

>[!MORELIKETHIS]
>
>* [Schedule Email Programs with Recipient Time Zone](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/scheduling-with-recipient-time-zone/schedule-email-programs-with-recipient-time-zone.md)
>* [Head Start for Email Programs](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/head-start-for-email-programs.md)
>
>* [Schedule Engagement Programs with Recipient Time Zone](/help/marketo/product-docs/email-marketing/drip-nurturing/engagement-program-streams/set-stream-cadence/schedule-engagement-programs-with-recipient-time-zone.md)
