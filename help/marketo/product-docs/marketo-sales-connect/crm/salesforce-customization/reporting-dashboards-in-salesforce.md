---
unique-page-id: 14352464
description: Reporting Dashboards in Salesforce - Marketo Docs - Product Documentation
title: Reporting Dashboards in Salesforce
---

# Reporting Dashboards in Salesforce {#reporting-dashboards-in-salesforce}

Reporting Dashboards in Salesforce - Marketo Docs - Product Documentation

Learn how to set up dashboards below.

### What's in this article? {#whats-in-this-article}

[Open and Click Report](#open-and-click-report)  
[Template Performance Report](#template-performance-report)  
[Template Volume Report](#template-volume-report)  
[Trending Accounts Report](#trending-accounts-report)

#### Open and Click Report {#open-and-click-report}

1. Select the **Tasks and Events** record type.
1. Define the report parameters based on your desired time frame and hierarchy structure.
1. Add a filter to remove internal emails logged to Salesforce (e.g. Company/Account not equal to Marketo).
1. Select the **Summary** report format.
1. Add the Subject, Assigned, and Marketo Sales Clicked/Marketo Sales Viewed fields to the report.
1. Double-click on **Add Formula** within the Fields pane.
1. Add a name to the formula, select **Percent **in the format, and select **Grouping 1*.***
1. Select **Marketo Sales Clicked/Marketo Sales Viewed, **then** Sum** in the Summary Fields.
1. Add a divide sign to the formula, and then select **Record Count** in the Summary fields – *Save As*.

#### Template Performance Report {#template-performance-report}

1. Customize the Open and Click report to include the following fields – *Save As.*

#### Template Volume Report {#template-volume-report}

##### 1. Modify the Template Performance Report and include the filter, "Marketo Sales Template not equal to blank." {#modify-the-template-performance-report-and-include-the-filter-marketo-sales-template-not-equal-to-blank}

##### 2. Remove the Marketo Sales Clicked field – *Save As*. {#remove-the-marketo-sales-clicked-field-save-as}

#### Trending Accounts Report {#trending-accounts-report}

##### 1. Select Activities with Accounts record type. {#select-activities-with-accounts-record-type}

##### 2. Setup the report parameters and fields as indicated below – *Save As.* {#setup-the-report-parameters-and-fields-as-indicated-below-save-as}

