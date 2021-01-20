---
unique-page-id: 557312
description: Smart List Filter Operators Glossary - Marketo Docs - Product Documentation
title: Smart List Filter Operators Glossary
---

# Smart List Filter Operators Glossary {#smart-list-filter-operators-glossary}

An operator is a part of the smart list that helps you get specific. It lets you describe your filter or trigger in straightforward language. The available operators are different for each type of field.

Here's a glossary describing each set of operators.

## Date Fields {#date-fields}

![](assets/image2014-9-10-17-3a15-3a47.png)

When you choose an operator, the right side will change dynamically.

| Operator |Right Side |Description |
|---|---|---|
| is |Single Date |Exact date match |
| is not |Single Date |Any date EXCEPT the one specified |
| between |Two Date Fields |Any date including and between two specified dates |
| in past |Natural Language Input&#42; |See diagram below |
| in past before |Natural Language Input&#42; |See diagram below |
| in future |Natural Language Input&#42; |See diagram below |
| in future after |Natural Language Input&#42; |See diagram below |
| in time frame |Presets (last quarter, yesterday etc) |Defined in picklist |
| after |Single Date |All records after the specified date |
| before |Single Date |All records before the specified one |
| on or after |Single Date |Same as "after" but inclusive |
| on or before |Single Date |Same as "before" but inclusive |
| is empty |None |All records without a date |
| is not empty |None |All records with any date |

&#42; Natural language input is cool. Here are some of the patterns you can enter:

* 1 hour
* 82 days
* 3 weeks
* 14 months
* 1 year

Just type the number and unit together and it'll work!

>[!NOTE]
>
>"In past" **does** include the day (up until the time, not after) you create your smart list.

>[!CAUTION]
>
>When you create a smart list using a date field filter (e.g., Date of Birth, SFDC Created Date) and use the **before** or **on or before** constraints, the smart list will also include people who have no value in said date field.

Use the following diagram to understand the difference between the date operators.

![](assets/image2014-9-10-17-3a15-3a58.png)

>[!NOTE]
>
>**Example**
>
>Date fields can get tricky when you're working with past and future events. Here are a couple of examples.
>
>**In past before**
>
>For your new promotion, use this operator to send emails only to people who have not subscribed to or renewed your service within one year or have never been subscribers.
>
>**In future after**
>
>Say you want to see customers who are up for renewal in 90 days. You would use two separate filters. First use "In Future After 90 days," and second, "In Future 91 Days." That would capture whomever has a date 90 days from now.

## String Fields {#string-fields}

![](assets/image2014-9-10-17-3a16-3a6.png)

| Operator |Description |
|---|---|
| is |Exact match (not case sensitive) |
| is not |Anything EXCEPT exact match |
| starts with |First letters of string match |
| not starts with |First letters of string DO NOT match |
| contains |Any letters together in the string match (example: california, fortune, therefor) |
| not contains |No letters together in the string match. (reverse of "contains") |
| is empty |Records that have no value (NULL) |
| is not empty |Records with ANY value |

>[!TIP]
>
>Use positive over negative operators. "Is not" filters have to search the entire data set in your instance, which can be extremely time-consuming. Positive "is" filters can leverage more effective search algorithms.

## Integer Fields {#integer-fields}

![](assets/image2014-9-10-17-3a16-3a14.png)

<table> 
 <thead> 
  <tr> 
   <th colspan="1" rowspan="1">Operator</th> 
   <th colspan="1" rowspan="1">Description</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td colspan="1" rowspan="1">is</td> 
   <td colspan="1" rowspan="1">Exact number match ( = 0 will return both leads with 0 <em>and</em> NULL)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">is not</td> 
   <td colspan="1" rowspan="1">Anything EXCEPT exact number match</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">between</td> 
   <td colspan="1" rowspan="1">Define two value to find everyone in between (inclusive)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">greater than</td> 
   <td colspan="1" rowspan="1">Above the specified</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">less than</td> 
   <td colspan="1" rowspan="1">Less than the specified</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">at least</td> 
   <td colspan="1" rowspan="1">Above the specified (inclusive)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">at most</td> 
   <td colspan="1" rowspan="1">Less than the specified (inclusive)</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">is empty</td> 
   <td colspan="1" rowspan="1">Records that have no value (NULL) - zero is a number, it is <em>not</em> NULL</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1">is not empty</td> 
   <td colspan="1" rowspan="1">Records with ANY value (including zero)</td> 
  </tr> 
 </tbody> 
</table>

As you can see, these operators make it easy to speak Marketo-ese with fluency!
