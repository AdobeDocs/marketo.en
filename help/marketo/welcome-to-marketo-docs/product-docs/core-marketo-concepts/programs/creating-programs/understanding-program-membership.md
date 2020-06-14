---
unique-page-id: 1147091
description: Understanding Program Membership - Marketo Docs - Product Documentation
title: Understanding Program Membership
---

# Understanding Program Membership {#understanding-program-membership}

Understanding Program Membership - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

>[!NOTE]
>
>**Definition**
>
>A member is a person that has a status in a program.

#### How People Become Members of a Program {#understandingprogrammembership-howpeoplebecomemembersofaprogram}

1. A person fills out a [form on a landing page](../../../../../welcome-to-marketo-docs/getting-started/quick-wins/landing-page-with-a-form.md) in the program.

    1. Person will automatically have the first status in the progression.

1. You [import members into the program](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/programs/working-with-programs/import-members-from-a-spreadsheet-into-a-program.md) from a CSV file.

    1. `Person will automatically have the first status in the progression.`

1. You use the [change program status](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/program-flow-actions/change-program-status.md) flow step.
1. A person registers or attends a [webinar synced with an event program](../../../../../welcome-to-marketo-docs/product-docs/demand-generation/events/understanding-events/launchpoint-event-partners.md).
1. A person is [created using the Marketo iPad check-in application](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/mobile-apps/event-check-in/check-people-into-your-event-from-your-tablet.md). 
1. A person is added to an SFDC Campaign, which is [synced to the program](../../../../../welcome-to-marketo-docs/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-campaign-sync.md).

>[!NOTE]
>
>For an email program, a person is added to membership only when the email is sent.

#### Program Statuses {#understandingprogrammembership-programstatuses}

Program statuses are the steps people go through in a program (e.g., Invited, RSVP'd, Attended, No Show). These steps are defined by the [channel](../../../../../welcome-to-marketo-docs/product-docs/administration/tags/create-a-program-channel.md).

![](assets/image2015-2-5-15-3a14-3a48.png)

>[!NOTE]
>
>A person cannot move backwards to an earlier program status. Status progression is one way only.

#### Success Statuses {#understandingprogrammembership-successstatuses}

The purpose of a program is to create a meaningful interaction with the person or prospect. Success is marked when a person reaches the status that achieves that goal.

>[!NOTE]
>
>**Example**
>
>For a webinar, registering isn't a meaningful interaction if they don't actually watch the webinar. Attending is success in this case.

#### Acquisition Program  {#understandingprogrammembership-acquisitionprogram}

When a new name enters the system as a program member, Marketo automatically sets that program as "acquisition." This establishes credit for [First-Touch attribution](../../../../../welcome-to-marketo-docs/product-docs/reporting/revenue-cycle-analytics/revenue-tools/understanding-attribution.md).

>[!NOTE]
>
>**Related Articles**
>
>* [Use Tags in a Program](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags/use-tags-in-a-program.md)
>* [Create a Program Performance Report](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/programs/program-performance-report/create-a-program-performance-report.md)
>

