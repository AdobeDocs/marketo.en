---
unique-page-id: 1146997
description: "Use a Date Token in a Wait Flow Step - Marketo Docs - Product Documentation"
title: Use a Date Token in a Wait Flow Step
exl-id: d161922b-ce90-4e65-9282-d3bb866c1d94
feature: Smart Campaigns
---
# Use a Date Token in a Wait Flow Step {#use-a-date-token-in-a-wait-flow-step}

You can use the Wait flow step to pause a person's journey through a Smart Campaign until a particular date that uses a date token. You can also modify the end date by some number of days.

>[!NOTE]
>
>This only applies to Trigger Campaigns. You cannot use this feature in Batch Campaigns.

1. In your Smart Campaign **[!UICONTROL Flow]** tab, drag over the **[!UICONTROL Wait]** flow step.

   ![](assets/use-a-date-token-in-a-wait-flow-step-1.png)

1. Click the gear icon.

   ![](assets/use-a-date-token-in-a-wait-flow-step-2.png)

1. From the **[!UICONTROL Type]** drop-down, select **[!UICONTROL Date Token]**.

   ![](assets/use-a-date-token-in-a-wait-flow-step-3.png)

1. Choose a [!UICONTROL Date token] to specify when the Wait step should end:

    * `{{my._____}}`
    * `{{lead.______}}`
    * `{{company.______}}`
    * `{{system._______}}`

   ![](assets/use-a-date-token-in-a-wait-flow-step-4.png)

1. To wait until the next anniversary of the date occurring in the current or next calendar year, check the box.

   ![](assets/use-a-date-token-in-a-wait-flow-step-5.png)

   >[!TIP]
   >
   >Use this option on date tokens that refer to dates in the past, such as a birthday or contract start date.

1. Optionally, you can modify the end date by a specified number of days.

   ![](assets/use-a-date-token-in-a-wait-flow-step-6.png)

   >[!NOTE]
   >
   >You can also specify the number of days using a `{{lead.` or `{{company.` token that represents an integer field,  or a `{{my.` token of number type.

1. Click **[!UICONTROL Save]**.

   ![](assets/use-a-date-token-in-a-wait-flow-step-7.png)

   >[!MORELIKETHIS]
   >
   >* [Use a Duration in a Wait Flow Step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-duration-in-a-wait-flow-step.md){target="_blank"}
   >* [Use a Specific Date in a Wait Flow Step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md){target="_blank"}
