---
unique-page-id: 1146901
description: Using Advanced Smart List Rule Logic - Marketo Docs - Product Documentation
title: Using Advanced Smart List Rule Logic
exl-id: fc41b6fd-c65e-4c44-b0ee-7bb5c77c51fb
feature: Smart Lists
---
# Using Advanced Smart List Rule Logic {#using-advanced-smart-list-rule-logic}

You can find the exact people you need by applying Smart List rule logic to multiple filters within a Smart List. Here's how.

>[!PREREQUISITES]
>
>* [Find and Add Filters to a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"}
>* [Define Smart List Filters](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/define-smart-list-filters.md){target="_blank"}

>[!NOTE]
>
>Advanced filter logic is only available if there are three or more filters in your Smart List.

## Add Logic to a Smart List {#add-logic-to-a-smart-list}

By default, your Smart List will find the people that match **[!UICONTROL ALL]** filters (filters 1 _and_ 2 _and_ 3). You can change the rule logic to find people that match **[!UICONTROL ANY]** of the defined filters (filters 1 _or_ 2 _or_ 3), or use advanced filters (filters 1 _and_ 2 _or_ 3).

In this example, let's say you want to find people in California _and_ with a score of at least 50 points _or_ with a status of "Sales Qualified."

1. Select **[!UICONTROL Use Advanced filters]** from the drop-down.

   ![](assets/one.png)

   >[!NOTE]
   >
   >Using **[!UICONTROL Advanced]** filters reduces the need to create Smart Lists with the Member of Smart List filter. This helps optimize performance.

1. The **[!UICONTROL Advanced filters]** text box will display "and" as the default value between all your filters.

   ![](assets/two-2.png)

1. Type a pair of parentheses around "2 and 3."

   ![](assets/three-2.png)

   >[!CAUTION]
   >
   >You must use "and" before "or" when entering rule logic.

1. Change the "and" between "2 and 3" to "or."

   ![](assets/four-1.png)

## Use Parentheses When Mixing "And" and "Or {#use-parentheses-when-mixing-and-and-or}

Mixing "and" and "or" logic requires parentheses to make your intention clear.

![](assets/advancedfilters-parent.png)

## Use Nested Parentheses for Four or More Filters if Needed {#use-nested-parentheses-for-four-or-more-filters-if-needed}

Depending on your intention, you may need to add nested parentheses when using four or more filters.

![](assets/advancedfilters-nested.png)

>[!TIP]
>
>If you enter an invalid rule, you'll see a red line displayed under the rule. Scroll over the text to see the related error message.
