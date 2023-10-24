---
unique-page-id: 557316
description: Define Smart List Filters - Marketo Docs - Product Documentation
title: Define Smart List Filters
exl-id: ab08c5be-0afa-46d5-9f29-99e1f6b99dea
feature: Smart Lists
---
# Define Smart List Filters {#define-smart-list-filters}

>[!PREREQUISITES]
>
>* [Create a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"}
>* [Find and Add Filters to Smart Lists](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"}

Now that you've [created a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md){target="_blank"} and [added filters](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"} to it, let's define the filters. Here's how.

Continuing our example, let's define these filters to find all people in California with a score over 50.

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/login-marketing-activities-1.png)

1. Select the Smart List and click on the **[!UICONTROL Smart List]** tab.

   ![](assets/smarlist-choosefilters.png)

1. Find and select "CA" for the **[!UICONTROL State]** filter.

   ![](assets/smartlistdefinefilters.png)

   >[!NOTE]
   >
   >You may be storing both "California" and "CA." In order to filter for both values and include _all_ people from California, learn how to  [add multiple values to a Smart List filter](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/using-smart-lists/add-multiple-values-to-a-smart-list-filter.md){target="_blank"}.

1. Pick the **[!UICONTROL greater than]** operator and enter "50."

   ![](assets/smartlistfilter-personscore.png)

>[!TIP]
>
>If you think you may have some records in your database that contain incomplete email addresses (e.g., just "@adobe.com"), use two Email Address filters when you're using the "contains" operator. One filter with "contains @adobe.com," and a separate filter with "contains adobe.com" (leaving out the @ symbol).

You now know how to create a Smart List and add/define filters.
