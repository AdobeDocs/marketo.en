---
description: Expected Behavior - Marketo Docs - Product Documentation
title: Expected Behavior
hide: yes
hidefromtoc: yes
exl-id: d19130cf-186e-4aad-be32-6aad18c9d08b
---
# Expected Behavior {#expected-behavior}

In this article, you'll find information on expected behavior associated with [!UICONTROL Predictive Audiences] (PA).

## Data and Privacy Considerations

* All required data processing for the AI/ML models takes place in North America.
* AI/ML models do not use specific lead information such as first or last names, gender, emails, contact numbers, etc. Models only utilize general attributes derived from firmographics and activity logs.

**For [!UICONTROL Predictive Audiences], you can expect the following behavior**

* PA is accessible in both [!DNL Marketo Sky] and the [!DNL Marketo Classic] experience. The availability of specific features is as follows:
  * Predictive filters - [!DNL Sky/Classic]
  * Projected registrations - [!DNL Sky/Classic]
  * Lead-level likelihood predictions - [!DNL Sky/Classic]
  * Goals and tracking - [!DNL Sky] only
  * Insights and recommendations - [!DNL Sky] only
* [Initial activation](/help/marketo/product-docs/marketo-sky/getting-started-with-predictive-audiences.md) takes **24-48 hours** for all processes to complete after PA has been enabled. You will see all [!UICONTROL Predictive Audiences] and [!UICONTROL Predictive Filters] capabilities in the interface, but it can take up to 24 hours for these features to begin working.
* **Predictions will only be generated for new campaigns that are created after the feature is activated.**

**There are some additional considerations specific to predictive filters**:

* Registration and Attendance Likelihood filters can only be used with event or webinar programs. Lookalike and Unsubscribe filters can be used in email, event, and webinar programs.
* You can apply predictive filters to a smart campaign even if the parent program is created before predictive filters are enabled.
* Predictive filters are not available for trigger campaigns.
* To run a smart campaign, likelihood filters need to be used in conjunction with other regular filters.
* The Saved Rules feature is not available for use in campaigns that contain predictive filters.
* You can use **up to 5** predictive filters in a smart list.
* Predictive filters can process a **maximum of 1 million qualified leads**.
* You can have **up to 50 active programs** with predictive filters. An active program is any program that uses predictive filters and has been scheduled at least once.

## When are projected registrations not available?

Projected registrations will not be available in the following use cases:

* if the program was created before Predictive Audiences was added
* when program statuses are not mapped to system statuses
* when there are no members in the program
* when there are no past similar programs within the last 6 months that match the required criteria
