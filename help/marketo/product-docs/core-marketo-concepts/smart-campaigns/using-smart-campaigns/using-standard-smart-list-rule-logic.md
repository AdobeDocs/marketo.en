---
unique-page-id: 1147001
description: Learn how to use standard Smart List rule logic in a Smart Campaign. Combine filters with AND logic for qualification.
title: Using Standard Smart List Rule Logic
exl-id: 9befaa81-e50c-47d3-9edf-220cfadd00f6
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/hRPdzjEUOeC2PZK2YlO1IPZOPoPOfo7CHJu2yUtU0qc
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
---
# Using Standard Smart List Rule Logic {#using-standard-smart-list-rule-logic}

You may have noticed the "Use filters" option when building campaign Smart Lists. This setting allows you to decide if the filters need to be evaluated with an AND or an OR operator.

![](assets/using-standard-smart-list-rule-logic-1.png)

>[!NOTE]
>
>Changing smart list rule logic only applies to filters, _not_ triggers.

Triggers are always evaluated as OR even if the above setting is set to ALL. For example:

![](assets/using-standard-smart-list-rule-logic-2.png)

The above Smart List in words:

```box
IF person fills out Great Form
OR
IF person visits Keith's Landing Page
AND
Industry is Energy
AND
Country is US
THEN follow the campaign's flow step(s)
```

So, if a person fills out the form _or_ visits the page, the campaign will then evaluate that person based on _all_ or _any_ of the subsequent filters, depending on the setting used.

>[!MORELIKETHIS]
>
>[Using Advanced Smart List Rule Logic](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/using-advanced-smart-list-rule-logic.md){target="_blank"}
