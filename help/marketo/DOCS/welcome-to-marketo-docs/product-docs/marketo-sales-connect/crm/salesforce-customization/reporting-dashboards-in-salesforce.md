---
unique-page-id: 14352464
description: Reporting Dashboards in Salesforce - Marketo Docs - Product Documentation
title: Reporting Dashboards in Salesforce
---

# Reporting Dashboards in Salesforce {#reporting-dashboards-in-salesforce}

Reporting Dashboards in Salesforce - Marketo Docs - Product Documentation

Learn how to set up dashboards below.

### What's in this article? {#what-s-in-this-article}

[Open and Click Report](#reportingdashboardsinsalesforce-openandclickreport)  
[Template Performance Report](#reportingdashboardsinsalesforce-templateperformancereport)  
[Template Volume Report](#reportingdashboardsinsalesforce-templatevolumereport)  
[Trending Accounts Report](#reportingdashboardsinsalesforce-trendingaccountsreport)

#### Open and Click Report {#reportingdashboardsinsalesforce-openandclickreport}

1. Select the **Tasks and Events** record type.
1. Define the report parameters based on your desired time frame and hierarchy structure.
1. Add a filter to remove internal emails logged to Salesforce (e.g. Company/Account not equal to Marketo).
1. Select the **Summary** report format.
1. Add the Subject, Assigned, and Marketo Sales Clicked/Marketo Sales Viewed fields to the report.
1. Double-click on **Add Formula** within the Fields pane.
1. Add a name to the formula, select **Percent **in the format, and select **Grouping 1*.***
1. Select **Marketo Sales Clicked/Marketo Sales Viewed, **then** Sum** in the Summary Fields.
1. Add a divide sign to the formula, and then select **Record Count** in the Summary fields – *Save As*.

#### Template Performance Report {#reportingdashboardsinsalesforce-templateperformancereport}

1. Customize the Open and Click report to include the following fields – *Save As.*

#### Template Volume Report {#reportingdashboardsinsalesforce-templatevolumereport}

##### 1. Modify the Template Performance Report and include the filter, "Marketo Sales Template not equal to blank." {#reportingdashboardsinsalesforce-modifythetemplateperformancereportandincludethefilter-"marketosalestemplatenotequaltoblank-"}

##### 2. Remove the Marketo Sales Clicked field – *Save As*. {#reportingdashboardsinsalesforce-removethemarketosalesclickedfield–saveas}

#### Trending Accounts Report {#reportingdashboardsinsalesforce-trendingaccountsreport}

##### 1. Select Activities with Accounts record type. {#reportingdashboardsinsalesforce-selectactivitieswithaccountsrecordtype}

##### 2. Setup the report parameters and fields as indicated below – *Save As.* {#reportingdashboardsinsalesforce-setupthereportparametersandfieldsasindicatedbelow–saveas}

