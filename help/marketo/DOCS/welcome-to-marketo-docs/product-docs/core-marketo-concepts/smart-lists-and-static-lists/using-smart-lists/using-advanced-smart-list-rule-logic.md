---
unique-page-id: 1146901
description: Using Advanced Smart List Rule Logic - Marketo Docs - Product Documentation
title: Using Advanced Smart List Rule Logic
---

# Using Advanced Smart List Rule Logic {#using-advanced-smart-list-rule-logic}

Using Advanced Smart List Rule Logic - Marketo Docs - Product Documentation

You can find the exact people you need by applying smart list rule logic to multiple filters within a smart list. Here's how.

>[!NOTE]
>
>**Prerequisites**
>
>* [Find and Add Filters to a Smart List](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)
>* [Define Smart List Filters](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/define-smart-list-filters.md)
>

>[!NOTE]
>
>Advanced filter logic is only available if there are three or more filters in your smart list.

### What's in this article? {#what-s-in-this-article}

[Add Logic to a Smart List](#usingadvancedsmartlistrulelogic-addlogictoasmartlist)  
[Use Parentheses When Mixing "And" and "Or](#usingadvancedsmartlistrulelogic-useparentheseswhenmixing"and"and"or)  
[Use Nested Parentheses for Four or More Filters if Needed](#usingadvancedsmartlistrulelogic-usenestedparenthesesforfourormorefiltersifneeded)

#### Add Logic to a Smart List {#usingadvancedsmartlistrulelogic-addlogictoasmartlist}

By default, your smart list will find the people that match **ALL** filters (filters 1 *and* 2 *and* 3). You can change the rule logic to find people that match **ANY** of the defined filters (filters 1 *or* 2 *or* 3), or use advanced filters (filters 1 *and* 2 *or *3).

In this example, let's say you want to find people in California *and* with a score of at least 50 points *or* with a status of "Sales Qualified."

1. Select **Use** **Advanced** **filters** from the drop-down.

   ![](assets/one.png)

   >[!NOTE]
   >
   >Using **Advanced** filters reduces the need to create smart lists with the Member of Smart List filter. This helps optimize performance.

1. The **Advanced** **filters** text box will display "and" as the default value between all your filters.

   ![](assets/two-2.png)

1. Type a pair of parentheses around "2 and 3."

   ![](assets/three-2.png)

   >[!CAUTION]
   >
   >You must use "and" before "or" when entering rule logic.

1. Change the "and" between "2 and 3" to "or."

   ![](assets/four-1.png)

#### Use Parentheses When Mixing "And" and "Or {#usingadvancedsmartlistrulelogic-useparentheseswhenmixing"and"and"or}

Mixing "and" and "or" logic requires parentheses to make your intention clear.

![](assets/advancedfilters-parent.png) 

#### Use Nested Parentheses for Four or More Filters if Needed {#usingadvancedsmartlistrulelogic-usenestedparenthesesforfourormorefiltersifneeded}

Depending on your intention, you may need to add nested parentheses when using four or more filters.

![](assets/advancedfilters-nested.png)

>[!TIP]
>
>If you enter an invalid rule, you'll see a red line displayed under the rule. Scroll over the text to see the related error message.

