---
description: Learn how to create tasks in Veeva from Marketo to inform sales what to do and when. Use the Create Task flow step and customize subject, description, and due date.
title: Create Task in [!DNL Veeva]
exl-id: 342e45dd-2038-432d-a6b6-1740c8f0b58e
feature: Veeva CRM
TQID: https://experienceleague.adobe.com/W4zIWswN64cHyqA7oQ9iku0iMC7Q6NqIpWiAcSgvD04
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
---
# Create Task in [!DNL Veeva] {#create-task-in-veeva}

As a marketer, you have information that can assist sales in closing deals. You can create tasks to let them know what they should do and when they should do it.

   ![](assets/create-task-in-veeva-1.png)

>[!NOTE]
>
>When the Marketo Sync User is creating tasks, **[!UICONTROL Due In]** is a required field for the task to be created in [!DNL Veeva]. Marketo will input five days by default if there is no value.

By default, the flow step will look like this:

   ![](assets/create-task-in-veeva-2.png)

Customize all fields to create the task the way you want it.

   ![](assets/create-task-in-veeva-3.png)

>[!TIP]
>
>You can use `{{lead.tokens}}`, `{{company.tokens}}`, `{{campaign.tokens}}` and `{{system.tokens}}` in the [!UICONTROL Subject] and [!UICONTROL Description]. See [Tokens for Flow Steps](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md){target="_blank"} for more details.
