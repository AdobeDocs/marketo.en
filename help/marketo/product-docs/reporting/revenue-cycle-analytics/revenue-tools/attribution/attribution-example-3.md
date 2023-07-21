---
unique-page-id: 7514149
description: Attribution Example 3 - Marketo Docs - Product Documentation
title: Attribution Example 3
exl-id: d8ca63a2-58de-4cde-b915-ff7f2e6468d9
feature: "Reporting, Revenue Cycle Analytics"
---
# Attribution Example 3 {#attribution-example}

Read the following scenario and try to determine the numbers that should be in the grid.

* April 11 | Steve downloads (Content) - success
* April 22 | Opportunity is created for $3,000 (Both Steve and Jason have roles)
* April 25 | Jason attends (Webinar) - success
* April 30 | Opportunity is Closed-Won

| Attribution Metric |(Content) |(Webinar) |
|---|---|---|
| (MT) Opty Created |`<pre>1</pre>` |`<pre>0</pre>` |
| (MT) Pipeline Created |`<pre>$3,000</pre>` |`<pre>$0</pre>` |
| (MT) Opty Won |`<pre>0.5</pre>` |`<pre>0.5</pre>` |
| (MT) Revenue Won |`<pre>$1,500</pre>` |`<pre>$1,500</pre>` |

**Show Answers**

>[!NOTE]
>
>**Explanation**
>
>Remember attribution rule #3. Jason had program success AFTER the opty was created. Therefore, the webinar can't get credit for the creation of the opportunity. Only credit for the Opty won.
>
>Therefore, (Content) has 100% of credit for the Opty creation and pipeline, but only 50% credit for the opty won.

>[!NOTE]
>
>**Attribution Rules**
>
>1. Credit is split evenly
>1. You can't give more credit than you earned
>1. You can't give credit for something that happened in the past

Try all of the examples and you will be an attribution pro!

>[!MORELIKETHIS]
>
>* [Attribution Example 1](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-1.md)
>* [Attribution Example 2](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-2.md)
>* [Attribution Example 4](/help/marketo/product-docs/reporting/revenue-cycle-analytics/revenue-tools/attribution/attribution-example-4.md)
