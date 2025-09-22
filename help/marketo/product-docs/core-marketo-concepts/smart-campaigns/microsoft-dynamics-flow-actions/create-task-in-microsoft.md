---
unique-page-id: 37356429
description: "Create Task in Microsoft - Marketo Docs - Product Documentation"
title: Create Task in Microsoft
exl-id: b9ae425b-edf1-4aae-92f4-e7c6cf647cdc
feature: Smart Campaigns, Microsoft Dynamics
---
# Create Task in Microsoft {#create-task-in-microsoft}

As a marketer, you have information that can assist sales in closing deals. You can create tasks to let them know what they should do and when they should do it.

Create Task in Microsoft creates a task under Activities related with the Person (Lead or Contact) in [!DNL Microsoft].

>[!NOTE]
>
>This flow step will _only work when used with triggers_, not filters, in your smart campaign.

By default, the flow step will look like this:

![](assets/create-task-in-microsoft-1.png)

>[!NOTE]
>
>When the Marketo Sync User is creating tasks, **[!UICONTROL Due In]** is a required field for the task to be created in [!DNL Microsoft]. Marketo will input five days by default if no value is entered.

Customize all fields to create the task the way you want it.

![](assets/create-task-in-microsoft-2.png)

>[!NOTE]
>
>The field "Status" specified for the task in the Flow Action updates the field: "Status Reason" in [!DNL Microsoft].

>[!TIP]
>
>You can use `{{lead.tokens}}`, `{{company.tokens}}`, `{{campaign.tokens}}` and `{{system.tokens}}` in the **[!UICONTROL Subject]** and **[!UICONTROL Description]**. See [Tokens for Flow Steps](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md){target="_blank"} for more details.
