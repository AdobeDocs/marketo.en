---
unique-page-id: 7514151
description: Attribution Example 4 - Marketo Docs - Product Documentation
title: Attribution Example 4
---

# Attribution Example 4 {#attribution-example}

Attribution Example 4 - Marketo Docs - Product Documentation

Read the following scenario and try to determine the numbers that should be in the grid.

* April 11 | Michelle downloads e-Book (Content) - Success
* April 15 | John attends (Webinar) - Success
* April 22 | (Opportunity 1) created for $3,000
* April 24 | ( `Opportunity`2) created for $5,000
* April 25 | John and Michelle are associated to **both** Optys
* April 29 | [Opty 1] is Closed-Won

| Program Name |(Content) |(Webinar) |
|---|---|---|
| &nbsp; |(Opty 1) |(Opty 2) |(Opty 1) |(Opty 2) |
| (MT) Opty Created |`<pre>0.5</pre>` |`<pre>0.5</pre>` |`<pre>0.5</pre>` |`<pre>0.5</pre>` |
| (MT) Pipeline Created |`<pre>$1,500</pre>` |`<pre>$2,500</pre>` |`<pre>$1,500</pre>` |`<pre>$2,500</pre>` |
| (MT) Opty Won |`<pre>0.5</pre>` |`<pre>0</pre>` |`<pre>0.5</pre>` |`<pre>0</pre>` |
| (MT) Revenue Won |`<pre>$1,500</pre>` |`<pre>$0</pre>` |`<pre>$1,500</pre>` |`<pre>$0</pre>` |

[Show Answers](#)

>[!NOTE]
>
>**Explanation**
>
>When you have multiple opportunities and multiple people with program success, you have to split the credit between the people and programs. However, notice that the credit for opportunity 1 and 2 are not combined. Each is a distinct credit evaluation.
>
>When many people are involved, Marketo will automatically calculate the fractions of an opportunity to give credit for.

>[!NOTE]
>
>**Attribution Rules**
>
>1. Credit is split evenly
>1. You can't give more credit than you earned
>1. You can't give credit for something that happened in the past
>

&nbsp;  

---

Try all of the examples and you will be an attribution pro!

>[!NOTE]
>
>**Related Articles**
>
>* [Attribution Example 1](attribution-example-1.md)
>* [Attribution Example 2](attribution-example-2.md)
>* [Attribution Example 3](attribution-example-3.md)
>

