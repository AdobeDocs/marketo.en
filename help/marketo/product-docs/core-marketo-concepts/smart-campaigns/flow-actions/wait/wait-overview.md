---
unique-page-id: 1146950
description: Wait - Marketo Docs - Product Documentation
title: Wait
---

# Wait {#wait}

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](/help/marketo/getting-started/updates-to-marketo-terminology.md).

## Overview {#overview}

Pause a person in a smart campaign flow with the handy **wait step**.

![](assets/wait-overview.png)

Notice how you can type in natural language like "4 hours." Do **not**, however, abbreviate the words (i.e., 4 hrs). The smart campaign would still run, but the wait step would be ignored.

>[!CAUTION]
>
>Changing the duration of a wait step will not affect people that have already entered it. For example: you have a wait step for 5 days, a person enters it, you then change the wait step to 7 days - that person will still only wait the original 5 days before advancing to the next flow step.

>[!TIP]
>
>If you have someone already in a wait step and you don't want them to advance after the wait period ends, insert [remove from flow](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/remove-from-flow.md) right after the wait step. Specify who you want removed by using the [add choice](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-add-choice-in-a-flow-step.md) option.

## Usage {#usage}

There are three main ways to use a wait flow step:

1. [Use a Duration in a Wait Flow Step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-duration-in-a-wait-flow-step.md)
1. [Use a Specific Date in a Wait Flow Step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md)
1. [Use a Date Token in a Wait Flow Step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-date-token-in-a-wait-flow-step.md)
