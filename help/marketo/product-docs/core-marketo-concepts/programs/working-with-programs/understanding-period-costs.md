---
unique-page-id: 7504676
description: Learn about period costs in programs for tracking spend. Assign costs to program periods for reporting and ROI.
title: Understanding Period Costs
exl-id: 99f50eaf-28cf-4a8b-8ebd-89a4beef986a
feature: Programs
TQID: https://experienceleague.adobe.com/1b6-8sKXlxtEi61tpFuFsfQjRu7-IXT6dOBGBd7Fwlw
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
---
# Understanding Period Costs {#understanding-period-costs}

## Overview {#overview}

Period costs refer to the money you spend in a specific month on a program.

>[!NOTE]
>
>**Example**
>
>If you spend $1000 to hire an illustrator for an [!DNL eBook] that launches in July - the [!DNL eBook] program would have a period cost of $1000 in July.
>
>If you spend $200 per month on [!DNL Google Adwords] - the [!DNL Google Adwords] program would have a period cost of $200 _every month_.

>[!NOTE]
>
>[Understanding Programs](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
>
>[Understanding Program Membership](/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md)

## How Period Costs are Calculated {#how-period-costs-are-calculated}

Imagine an event, like a webinar, that occurs in March. New people are acquired beforehand from advertising in January and February. New contacts are also acquired after the event, when people download the webinar in the months of April and May.

1. With a single period cost attributed to March...

   ![](assets/graph1.png)

   ...contacts added in the months before and after will _only_ count towards March.

   ![](assets/graph2.png)

1. With period costs attributed to January, February, and March...

   ![](assets/graph3.png)

   ...contacts added only in the months after March will count towards March.

   ![](assets/graph4.png)

1. With period costs attributed to January and April...

   ![](assets/graph5.png)

   ...contacts added in the months January through March will count towards January. Contacts added in the months April and May will count towards April.

   ![](assets/graph6.png)

   >[!NOTE]
   >
   >In summary - months with no defined period costs will roll "backwards" to the last one that was defined. If there is no prior period cost, the months will be rolled "forward" to the next one that has been defined. If a period cost has not been defined for _any_ months, reporting in RCE will not be available for the program.

>[!MORELIKETHIS]
>
>* [Using Period Costs in a Program](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program.md)
>* [Filter a Program Report by Period Cost](/help/marketo/product-docs/core-marketo-concepts/programs/program-performance-report/filter-a-program-report-by-period-cost.md)
