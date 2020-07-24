---
title: understanding-batch-and-trigger-smart-campaigns
description: Understanding Batch and Trigger Smart Campaigns
---

# Understanding Batch and Trigger Smart Campaigns

<br>&nbsp;

There are two types of smart campaigns: Batch and Trigger.

## Batch Smart Campaign

A batch campaign launches at a specific time and affects a specific set of people all at once. An example would be sending an email to everyone in your database who lives in California.

Batch smart campaigns will only have filters within the smart list section (i.e., no triggers).

   ![Image One](/help/sky/assets/smart-campaigns/understanding-batch-and-trigger-smart-campaigns/understanding-batch-and-trigger-smart-campaigns-1.png)

Clicking the **Schedule** tab will confirm that the smart campaign is set to "Batch."

   ![Image Two](/help/sky/assets/smart-campaigns/understanding-batch-and-trigger-smart-campaigns/understanding-batch-and-trigger-smart-campaigns-2.png)

**Batch Smart Campaigns**

* Can be scheduled for recurrences, such as daily, weekly, and monthly. You can also have them run just once.
* Are visible on the [program schedule view](https://docs.marketo.com/display/DOCS/Navigating+the+Program+Schedule+View).
* Anything after a "Wait" step within the smart campaign will not be included on the view.

## Trigger Smart Campaign

A trigger smart campaign affects one person at a time based on a triggered event. An example of a trigger would be clicking a link in an email.

If a smart campaign uses at least one trigger within the smart list section, the mode will automatically be set to triggered.

   ![Image Three](/help/sky/assets/smart-campaigns/understanding-batch-and-trigger-smart-campaigns/understanding-batch-and-trigger-smart-campaigns-3.png)

Clicking the **Schedule** tab will confirm that the smart campaign is set to "Trigger."

   ![Image Four](/help/sky/assets/smart-campaigns/understanding-batch-and-trigger-smart-campaigns/understanding-batch-and-trigger-smart-campaigns-4.png)

**Trigger Smart Campaigns**

* Cannot be scheduled for recurrences. They can only be set to active or inactive.
* You can set more than one trigger. However if _any_ trigger is fired, the campaign actions will run.

>[!TIP]
>
>Use the [activity log](https://docs.marketo.com/display/DOCS/Locate+the+Activity+Log+for+a+Person) to see what occurred step-by-step within your smart campaigns. You can find the activity log in the last tab of a person's detail page.
