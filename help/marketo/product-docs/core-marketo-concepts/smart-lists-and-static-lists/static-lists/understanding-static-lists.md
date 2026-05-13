---
unique-page-id: 2949891
description: Learn about static lists in Marketo for fixed sets of people. Use static lists when membership is manually managed.
title: Understanding Static Lists
exl-id: c37c1496-cf19-4e44-aaec-77b10669b9bf
feature: Static Lists
TQID: https://experienceleague.adobe.com/rRi3-6ZggKswYYLTZjUr5EBDNoMRirDc1KJgHbbDqP4
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
---
# Understanding Static Lists {#understanding-static-lists}

Static lists are one of the most simple and useful features of Marketo. They are a list of names from your Database. You will find plenty of reasons to use them.

>[!NOTE]
>
>A single person in the database can be in many different static lists.

The difference between a Static and Smart List is crucial to understand.

| Type |Logic |
|---|---|
| Smart List |Based on **defined rules** |
| Static List |Based on **adding/removing each person** |

>[!CAUTION]
>
>One of the most common mistakes is thinking you can remove a person from a list by "deleting the person." **This is wrong**. Deleting the person will delete them from **the entire database**, not just the list.

## Ways to Add or Remove People from a List {#ways-to-add-remove-people-from-a-list}

1. Smart Campaign flow step ([Add to List](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-to-list.md){target="_blank"}, [Remove from List](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/remove-from-list.md){target="_blank"})

1. [Single action flow step](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/run-a-single-flow-step-from-a-smart-list.md){target="_blank"}
1. Dragging people into a list in the tree
1. [List import](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md){target="_blank"}

## Some Uses of a Static List {#some-uses-of-a-static-list}

* A list that has been pre-selected to receive a marketing message.
* A "competitors" list that you use to send mischievous counter-intelligence messages.
* A temporary list of people in a particular state, who are then removed by Smart Campaigns when they exit that state.

>[!MORELIKETHIS]
>
>[Create a Static List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/create-a-static-list.md){target="_blank"}
