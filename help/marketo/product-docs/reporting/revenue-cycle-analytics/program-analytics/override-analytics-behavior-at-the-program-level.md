---
unique-page-id: 2360421
description: Override Analytics Behavior at the Program Level - Marketo Docs - Product Documentation
title: Override Analytics Behavior at the Program Level
exl-id: 2fd86279-99ae-494d-a6f8-2572b7dcd892
feature: Reporting, Revenue Cycle Analytics
---
# Override Analytics Behavior at the Program Level {#override-analytics-behavior-at-the-program-level}

You can set the [analytics behavior at the admin level on channels](/help/marketo/product-docs/reporting/revenue-cycle-analytics/program-analytics/make-a-program-without-a-period-cost-available-in-revenue-explorer-and-analyzers.md) but you can also override it at the program level. Here is how:

1. Go to the **[!UICONTROL Marketing Activities]** area.

   ![](assets/image2014-9-24-11-3a40-3a46.png)

1. Find and select your program.

   ![](assets/image2014-9-24-11-3a40-3a57.png)

1. Under the **[!UICONTROL Setup]** tab, drag [!UICONTROL Analytics Behavior] into the canvas.

   ![](assets/image2014-9-24-11-3a41-3a2.png)

1. Select the [!UICONTROL Analytics Behavior] you want.

   >[!NOTE]
   >
   >**Definition**
   >
   >* **Inclusive** - This option will ensure that the program is available for reporting in revenue explorer and analyzers regardless of if you have included a period cost or not.
   >* **Operational** - This option results in the program not showing up in either revenue explorer or analyzers.

   >[!NOTE]
   >
   >The default behavior (if this setting is not applied) is the program would be included in Analytics **ONLY if there is at least one period cost**, even one with zero dollars assigned.

   ![](assets/image2014-9-24-11-3a42-3a0.png)

1. Click **[!UICONTROL Save]**.

   ![](assets/image2014-9-24-11-3a42-3a6.png)

Nicely done! Now you know how to override the analytics behavior at the program level.

>[!NOTE]
>
>The changes will take affect the next day and either be made available or pulled out of revenue explorer and analyzers.
