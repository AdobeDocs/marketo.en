---
unique-page-id: 7514146
description: Attribution Example 2 - Marketo Docs - Product Documentation
title: Attribution Example 2
---

# Attribution Example 2 {#attribution-example}

Read the following scenario and try to determine the numbers that should be in the grid.

* April 11 | Bill is acquired by (Tradeshow)
* April 15 | Joan is acquired by (Webinar)
* April 22 | (Opportunity 1) created for $6,000
* April 24 | (Opportunity 2) created for $10,000
* April 25 | Bill and Joan are associated with roles to **BOTH **Optys
* April 29 | (Opportunity 1) is Closed-Won

| Program Name |(Tradeshow) |(Webinar) |
|---|---|---|
| (FT) Opty Created |`<pre>1</pre>` |`<pre>1</pre>` |
| (FT) Pipeline Created |`<pre>$8,000</pre>` |`<pre>$8,000</pre>` |
| (FT) Opty Won |`<pre>0.5</pre>` |`<pre>0.5</pre>` |
| (FT) Revenue Won |`<pre>$3,000</pre>` |`<pre>$3,000</pre>` |

[Show Answers](#)

>[!NOTE]
>
>**Explanation**
>
>Because both Bill and Joan were associated with roles to **BOTH **opportunities, the system (according to the rules) split the credit evenly between them.
>
>Pipeline created for each program ($8,000) is half of the total ($16,000) available to give as credit.

>[!NOTE]
>
>**Attribution Rules**
>
>1. Credit is split evenly
>1. You can't give more credit than you earned
>1. You can't give credit for something that happened in the past
>

<br>&nbsp;

Try all of the examples and you will be an attribution pro!

>[!NOTE]
>
>**Related Articles**
>
>* [Attribution Example 1](attribution-example-1.md)
>* [Attribution Example 3](attribution-example-3.md)
>* [Attribution Example 4](attribution-example-4.md)
>

