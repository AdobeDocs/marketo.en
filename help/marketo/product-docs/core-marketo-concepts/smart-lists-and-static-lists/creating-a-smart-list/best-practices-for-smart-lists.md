---
unique-page-id: 7512524
description: Best Practices for Smart Lists - Marketo Docs - Product Documentation
title: Best Practices for Smart Lists
exl-id: 466de198-1012-4ac3-906c-d41943fe5bc0
feature: Smart Lists
---
# Best Practices for Smart Lists {#best-practices-for-smart-lists}

Smart lists are the most powerful query tool in the marketing universe. They find the people you are looking for with magical speed and ease.

To make them easy to work with and optimize performance, we've created a list of good practices. Enjoy!

>[!NOTE]
>
>**Each customer is different.** The bigger the database, the more processing happens. The more activities you have stored, the longer it takes to search through them.
>
>If you are experiencing slowness, try the tips below. If the issue persists, contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}.

1. **Limit history -** History filters (a.k.a. Activity filters) are among the most resource intensive, time-consuming operations. If you must use them, try to limit the date range to as short as possible, which would reduce the searchable data set. Additionally, date ranges won't supersede retention periods. Ex: If the activity you're querying has a 90-day retention period and you choose "past 100 days," only results from the past 90 days will be returned. Activity retention periods [can be found here](https://nation.marketo.com/t5/knowledgebase/marketo-activities-data-retention-policy/ta-p/251480){target="_blank"}.
1. **Limit nested smart lists -** When creating a new smart list, limit the amount of "Member of Smart List" filters used. This is called nesting smart lists, and each smart list referenced will increase processing time. Instead, either reference static lists or utilize [segmentation](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md){target="_blank"}.
1. **Use positive over negative operators -** While "not" filters are available, they have to search the entire data set in your instance, which can be extremely time-consuming. Positive "is" filters are able to leverage more effective search algorithms.
1. **Avoid "contains" -** If you only have partial data, "starts with" qualifiers will yield much faster results than "contains." "Is" will run even faster. Avoid using "contains" with multi-values; the two together can slow down a campaign even further.
1. **Use Random Sample by itself -** Random Sample is a special filter. Use it by itself to put your people into pre-made lists. Then just use "Member of List" to make your smart list super fast. Random Sample will **NOT** work with nested Smart Lists. The Random Sample filter will not work if it is the Smart List being referenced for the "Member of Smart List" filter.
1. **Be thrifty with inactivity filters -** Filters like "Not Filled Out Form" can be really useful, but require much more processing power.
1. **Be thrifty with pasting in multiple values -** Multi-select is designed for pasting in dozens or possibly hundreds of values. Put in too many, however, and it will slow way down.
1. **Be thrifty when adding constraints -** These are the tiny details of a rule and related values. The more constraints you add, the slower the processing time.
1. **Simplify your campaigns -** 100+ independent rules (we have seen it!) are obviously going to take some time to process. Keep it simple and you will notice the speed gains - plus it will be easier for you to understand.
1. **Include the @ symbol before the domain name when using the Email Address filter** **-** This makes it use a faster query. Example: Instead of using _email contains 'somedomain.com'_, use _email contains '@somedomain.com_.' If you're using multiple email address with "contains," ALL of them must start with "@."

>[!TIP]
>
>Marketo can be used in many ways and certain techniques are better for you and your business. Consider [Marketo professional services](https://pages2.marketo.com/72-hour-survival-guide.html){target="_blank"} to make your investment shine.
