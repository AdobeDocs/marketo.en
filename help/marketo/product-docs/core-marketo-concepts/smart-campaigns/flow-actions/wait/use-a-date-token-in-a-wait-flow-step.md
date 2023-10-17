---
unique-page-id: 1146997
description: Use a Date Token in a Wait Flow Step - Marketo Docs - Product Documentation
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

   ![](assets/image2014-9-22-14-3a8-3a22.png)

1. Click the gear icon.

   ![](assets/image2014-9-22-14-3a8-3a37.png)

1. From the **[!UICONTROL Type]** drop-down, select **[!UICONTROL Date Token]**.

   ![](assets/image2014-9-22-14-3a8-3a41.png)

1. Choose a Date token to specify when the Wait step should end:

    * `{{my._____}}`
    * `{{lead.______}}`
    * `{{company.______}}`
    * `{{system._______}}`

   ![](assets/image2014-9-22-14-3a9-3a33.png)

1. To wait until the next anniversary of the date occurring in the current or next calendar year, check the box.

   ![](assets/image2014-9-22-14-3a9-3a37.png)

   >[!TIP]
   >
   >Use this option on date tokens that refer to dates in the past, such as a birthday or contract start date.

1. Optionally, you can modify the end date by a specified number of days.

   ![](assets/image2014-9-22-14-3a9-3a57.png)

   >[!NOTE]
   >
   >You can also specify the number of days using a `{{lead.` or `{{company.` token that represents an integer field,  or a `{{my.` token of number type.

1. Click **[!UICONTROL Save]**.

   ![](assets/image2014-9-22-14-3a11-3a3.png)

   >[!MORELIKETHIS]
   >
   >* [Use a Duration in a Wait Flow Step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-duration-in-a-wait-flow-step.md){target="_blank"}
   >* [Use a Specific Date in a Wait Flow Step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/wait/use-a-specific-date-in-a-wait-flow-step.md){target="_blank"}
