---
unique-page-id: 7514126
description: Attribution Example 1 - Marketo Docs - Product Documentation
title: Attribution Example 1
---

# Attribution Example 1 {#attribution-example}

Read the following scenario and try to determine the numbers that should be in the grid.

* April 11 | Fred is acquired by (Tradeshow)
* April 15 | Margo attends (Webinar) - success
* April 22 | Fred is associated (role) to the opportunity
* April 22 | Opportunity is created for $3,000

| Program Name |(Tradeshow) |(Webinar) |
|---|---|---|
| (FT) Opty Created |`<pre>1</pre>` |`<pre>0</pre>` |
| (FT) Pipeline Created |`<pre>$3,000</pre>` |`<pre>$0</pre>` |
| (FT) Opty Won |`<pre>0</pre>` |`<pre>0</pre>` |
| (FT) Revenue Won |`<pre>0</pre>` |`<pre>0</pre>` |

[Show Answers](#)

>[!NOTE]
>
>**Explanation**
>
>First is to understand that some types are COUNTS and others are CURRENCY. Opty Created is a count, an integer. Pipeline is a currency. In Marketo, the currency will conform to your admin locale settings.
>
>The reason the Tradeshow received all credit is because Margo was not associated with a role in the opportunity. No role, no credit.

>[!NOTE]
>
>**Attribution Rules**
>
>1. Credit is split evenly
>1. You can't give more credit than you earned
>1. You can't give credit for something that happened in the past
>

Try all of the examples and you will be an attribution pro!

>[!NOTE]
>
>**Related Articles**
>
>* [Attribution Example 2](attribution-example-2.md)
>* [Attribution Example 3](attribution-example-3.md)
>* [Attribution Example 4](attribution-example-4.md)
>

