---
unique-page-id: 14352464
description: Reporting Dashboards in Salesforce - Marketo Docs - Product Documentation
title: Reporting Dashboards in Salesforce
exl-id: f27ba3e1-210b-46df-81b5-e794826d36c7
---
# Reporting Dashboards in Salesforce {#reporting-dashboards-in-salesforce}

Learn how to set up dashboards below.

## Open and Click Report {#open-and-click-report}

1. Select the **[!UICONTROL Tasks and Events]** record type.
1. Define the report parameters based on your desired time frame and hierarchy structure.
1. Add a filter to remove internal emails logged to [!DNL Salesforce] (e.g. Company/Account not equal to Marketo).
1. Select the **[!UICONTROL Summary]** report format.
1. Add the Subject, Assigned, and Marketo Sales Clicked/Marketo Sales Viewed fields to the report.
1. Double-click on **[!UICONTROL Add Formula]** within the Fields pane.
1. Add a name to the formula, select **[!UICONTROL Percent]** in the format, and select **[!UICONTROL Grouping 1]**.
1. Select **[!UICONTROL Marketo Sales Clicked/Marketo Sales Viewed]**, then **[!UICONTROL Sum]** in the Summary Fields.
1. Add a divide sign to the formula, and then select **[!UICONTROL Record Count]** in the Summary fields – _Save As_.

## Template Performance Report {#template-performance-report}

1. Customize the Open and Click report to include the following fields – _Save As_.

## Template Volume Report {#template-volume-report}

1. Modify the Template Performance Report and include the filter, "Marketo Sales Template not equal to blank."
1. Remove the Marketo Sales Clicked field – _Save As_.

## Trending Accounts Report {#trending-accounts-report}

1. Select Activities with Accounts record type.
1. Setup the report parameters and fields as indicated below – _Save As_.
