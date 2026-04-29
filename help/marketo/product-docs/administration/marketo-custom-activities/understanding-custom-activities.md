---
unique-page-id: 10100266
description: "Overview of custom activities for tracking business-specific person actions, how they differ from custom objects, and the two-step setup of creating the activity and API implementation."
title: Understanding Custom Activities
exl-id: 0bb74d9d-3a9d-4ef7-8c8c-2de36cd6190b
feature: Custom Activities
---
# Understanding Custom Activities {#understanding-custom-activities}

Track an action a person has taken specific to your business with custom activities.

## What Are Activities {#what-are-activities}

There are several ways a person can interact with your organization. They may visit your company's website, attend one of your trade shows, or click a link in an email sent to them. These actions are activities, and whatever action they take, Marketo captures it so your Marketing Team can better understand how to send them timely and relevant communication.

## Custom Activities {#custom-activities}

Custom activities help you track an activity that is not related to a Marketo form, email, or landing page. To track when someone deposits a check, use a custom activity. To track when someone attends a webinar, use a custom activity.

>[!NOTE]
>
>Custom activities differ from custom objects. Use custom objects when the value can change (i.e. "car color" changes from blue to red). Use custom activities when tracking moments that occurred, and their details cannot change (i.e. "purchased car").

## Fields {#fields}

You may add [additional fields](/help/marketo/product-docs/administration/marketo-custom-activities/add-edit-delete-marketo-custom-activity-fields.md) that you wish to associate with your activity. Like the primary field, they can be used as filtering criteria in a smart list.

## Getting Started {#getting-started}

Custom activities function just like standard activities. Setting them up, however, is a two-step process.

Step 1: [Create a custom activity](/help/marketo/product-docs/administration/marketo-custom-activities/create-a-custom-activity.md) in your Marketo account

Step 2: The employee in your organization who works with the Marketo API can then begin the implementation. More information can be found here: [Custom Activity API](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Activities/operation/addCustomActivityUsingPOST)
