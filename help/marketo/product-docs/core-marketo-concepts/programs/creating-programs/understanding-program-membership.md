---
unique-page-id: 1147091
description: Understanding Program Membership - Marketo Docs - Product Documentation
title: Understanding Program Membership
exl-id: 02480a93-b499-4e0f-8a1c-a22f7d3b7178
feature: Programs
---
# Understanding Program Membership {#understanding-program-membership}

>[!NOTE]
>
>**Definition:** A member is a person that has a status in a program.

## How People Become Members of a Program {#how-people-become-members-of-a-program}

1. A person fills out a [form on a landing page](/help/marketo/getting-started/quick-wins/landing-page-with-a-form.md){target="_blank"} in the program.

   * Person will automatically have the first status in the progression.

1. You [import members into the program](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-members-from-a-spreadsheet-into-a-program.md){target="_blank"} from a CSV file.

   * Person will automatically have the first status in the progression.

1. You use the [change program status](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md){target="_blank"} flow step.
1. A person registers or attends a [webinar synced with an event program](/help/marketo/product-docs/demand-generation/events/understanding-events/event-partners.md){target="_blank"}.
1. A person is [created using the Marketo iPad check-in application](/help/marketo/product-docs/core-marketo-concepts/mobile-apps/event-check-in/check-people-into-your-event-from-your-tablet.md){target="_blank"}.
1. A person is added to an SFDC Campaign, which is [synced to the program](/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md){target="_blank"}.

>[!NOTE]
>
>For an email program, a person is added to membership only when the email is sent.

## Program Statuses {#program-statuses}

Program statuses are the steps people go through in a program (e.g., Invited, RSVP'd, Attended, No Show). These steps are defined by the [channel](/help/marketo/product-docs/administration/tags/create-a-program-channel.md){target="_blank"}.

![](assets/image2015-2-5-15-3a14-3a48.png)

>[!NOTE]
>
>A person cannot move backwards to an earlier program status. Status progression is one way only.

## Success Statuses {#success-statuses}

The purpose of a program is to create a meaningful interaction with the person or prospect. Success is marked when a person reaches the status that achieves that goal.

>[!NOTE]
>
>For a webinar, registering isn't a meaningful interaction if they don't actually watch the webinar. Attending is success in this case.

## Acquisition Program {#acquisition-program}

When a new name enters the system as a program member, Marketo automatically sets that program as "acquisition." This establishes credit for [First-Touch attribution](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/understanding-attribution.md){target="_blank"}.

>[!MORELIKETHIS]
>
>* [Use Tags in a Program](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/use-tags-in-a-program.md){target="_blank"}
>* [Create a Program Performance Report](/help/marketo/product-docs/core-marketo-concepts/programs/program-performance-report/create-a-program-performance-report.md){target="_blank"}
