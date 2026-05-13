---
unique-page-id: 1147017
description: Learn how to create a Salesforce task in a flow step. Create a task for the lead owner when someone enters the flow.
title: Create Task
exl-id: c484d913-1fd8-4716-8caa-0bf318218ca1
feature: Smart Campaigns, Salesforce Integration
TQID: https://experienceleague.adobe.com/RJ5nZrVvURtgXEWWZwL2xXzlYOhWjKGSbX-MFTWCwzg
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
---
# Create Task {#create-task}

As a marketer, you have information that can assist sales in closing deals. You can create tasks to let them know what they should do and when they should do it.

![](assets/create-task-1.png)

>[!NOTE]
>
>When the Marketo Sync User is creating tasks, **[!UICONTROL Due In]** is a required field for the task to be created in Salesforce. Marketo will input five days by default if there is no value.

By default, the flow step will look like this:

![](assets/create-task-2.png)

Customize all fields to create the task the way you want it.

![](assets/create-task-3.png)

>[!TIP]
>
>You can use `{{lead.tokens}}`, `{{company.tokens}}`, `{{campaign.tokens}}` and `{{system.tokens}}` in the **[!UICONTROL Subject]** and **[!UICONTROL Description]**. See [Tokens for Flow Steps](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md){target="_blank"} for more details.
