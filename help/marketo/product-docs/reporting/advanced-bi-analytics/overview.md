---
description: Advanced BI Analytics Overview - Marketo Docs - Product Documentation
title: Advanced BI Analytics Overview
hide: yes
hidefromtoc: yes
feature: Reporting
exl-id: 120663ef-abcd-4cfe-aac1-64b57ff47258
---
# Advanced BI Analytics Overview {#advanced-bi-analytics-overview}

Advanced BI Analytics (formerly known as Revenue Explorer and Advanced Report Builder) offers a flexible reporting and visualization interface on Marketo Engage data, providing granular details about progression, performance, and more. It features richer interactivity and visualization, faster performance, and more seamless and intuitive user experience.

These enhancements help you save time, discover more valuable insights, drive optimization, and share more compelling data stories with colleagues and stakeholders.

>[!PREREQUISITES]
>
>To access this feature you must have purchased the Advanced BI Analytics add-on. Please contact the Adobe Account Team (your Account Manager) for details.

## Key features and benefits {#key-features-and-benefits}

* **High-performance Query Engine**: Delivers 5x faster performance on large datasets, enabling quicker data processing, faster report loading, and a smoother analysis experience.

* **Rich and Engaging Visualization**: Vast, expanded collection of built-in visualization options, including charts, maps, and KPI indicators that make dashboards more insightful and impactful and dramatically enhance data storytelling.

* **Advanced Interactivity and Dynamic Filtering**: Apply dynamic slicers, cross-filtering, and interdependent filters across visuals. Multi-page reports support advanced drill-down, drill-up, and drill-through, ensuring effortless data exploration.

* **Intuitive Report Authoring Interface**: A point-and-click experience simplifies report creation, including multi-page drill-through reports. The interface allows business users to design complex, interactive reports without requiring deep technical expertise.

* **Easy Sharing, Including PowerPoint Export**: Built-in sharing functionality makes sharing insights effortless. Among other destinations, users can easily generate presentation-ready PowerPoint slides.

## Create a report {#create-a-report}

1. In your My Marketo page, click the **Advanced BI Analytics (Beta)** tile.

   SCREENSHOT

1. In the **Reports** tab, click **Create Report**.

   SCREENSHOT

1. Select the desired measures.

   SCREENSHOT

1. Select the desired dimensions.

   SCREENSHOT

1. Choose your preferred visualization.

   SCREENSHOT

1. Add filters by drag-and-droping a dimension attribute.

   SCREENSHOT

## Video demo {#video}

Watch the following video to see an example of a multi-page, drill-through report experience.

>[!VIDEO](https://video.tv.adobe.com/v/3451681/?quality=12&learn=on){transcript=true}

## Standard Reports in Advanced BI Analytics {#standard-reports}

The following standard reports are included as examples for your custom reports.

<table>
  <thead>
    <tr>
      <th>Reporting Area</th>
      <th>Report Name</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="8">Email Analysis</td>
      <td>Email - Sent Activity (in CST)</td>
    </tr>
    <tr>
      <td>Email - Click Activity (in CST)</td>
    </tr>
    <tr>
      <td>Email - Open Activity (in CST)</td>
    </tr>
    <tr>
      <td>Email - Clicked Time Distribution (in CST)</td>
    </tr>
    <tr>
      <td>Email - Open Rate Decay</td>
    </tr>
    <tr>
      <td>Email - Opened Time Distribution (in CST)</td>
    </tr>
    <tr>
      <td>Email - Performance Details</td>
    </tr>
    <tr>
      <td>Email - Click Rate Decay</td>
    </tr>
    <tr>
      <td rowspan="8">Lead Analysis</td>
      <td>Top 10 Lead Sources By Converted Leads</td>
    </tr>
    <tr>
      <td>Top 10 Lead Sources</td>
    </tr>
    <tr>
      <td>SLA Infractions Report</td>
    </tr>
    <tr>
      <td>Lead Aging Report</td>
    </tr>
    <tr>
      <td>Lead Balance Report</td>
    </tr>
    <tr>
      <td>Lead Conversion Report</td>
    </tr>
    <tr>
      <td>Lead Flow Report</td>
    </tr>
    <tr>
      <td>Lead Transition Time Report</td>
    </tr>
    <tr>
      <td rowspan="5">Program Analysis</td>
      <td>Top 10 Programs By Success</td>
    </tr>
    <tr>
      <td>Top 10 Programs By Total Pipeline</td>
    </tr>
    <tr>
      <td>Program Revenue Stage Report</td>
    </tr>
    <tr>
      <td>Top 10 Acquisition Programs</td>
    </tr>
    <tr>
      <td>Marketing Channel Investment Trend</td>
    </tr>
    <tr>
      <td rowspan="7">Opportunity Analysis</td>
      <td>Marketing Impact on Closed Opportunities</td>
    </tr>
    <tr>
      <td>Marketing Influence on Opportunities Closed Won</td>
    </tr>
    <tr>
      <td>Marketing Influence on Opportunities Created</td>
    </tr>
    <tr>
      <td>(FT) Marketing Influence on Opportunities Created</td>
    </tr>
    <tr>
      <td>(MT) Marketing Influence on Opportunities Closed Won</td>
    </tr>
    <tr>
      <td>(MT) Marketing Influence on Opportunities Created</td>
    </tr>
    <tr>
      <td>(FT) Marketing Influence on Opportunities Closed Won</td>
    </tr>
    <tr>
      <td>Opportunity Lead Analysis</td>
      <td>Top 10 Lead Owners By Opportunities Won</td>
    </tr>
  </tbody>
</table>

## Things to note {#note}

The public beta will last until June 1, 2025, upon which time the classic experience through "Revenue Explorer" will be permanently deprecated.

_During the public beta:_

* You can access, create, update, and delete reports in both experiences.
* Your custom reports will be replicated from the classic experience to the new experience with the notable behavior changes mentioned in the [Learning the New Experience](#learning-the-new-experience) section below.

   >[!IMPORTANT]
   >
   >Important - Replication of custom reports will be carried out in cohorts. Once your custom reports are replicated to the new experience, to ensure consistency between the two experiences, any changes made in the classic experiences will also need to be manually applied to the corresponding reports in the new experience. An information note on the above will light up in the classic experience upon the replication of your customer reports.

   * Dashboards in the classic experience are not transferable and will require recreation within the new experience. They should be recreated as reports in the new experience and the filters in the new experience automatically pulls possible values rather than require you to manually enter all possible values individually in the classic experience.
      
      >[!NOTE]
      >
      >The dashboard in the new experience is nothing other than a collection of reports on a single page. The primary value of dashboard in the new experience is to allow you to present analytical insights across different reporting areas.

* Your email subscriptions in the classic experience will be replicated to the new experience. The email subscriptions in the classic experience will continue functioning until the deprecation of the classic experience.
* Your current Revenue Explorer users will automatically have access to the new Advanced BI Analytics (Beta) experience.

## Learning the new experience {#learning-the-new-experience} 

The new visualization experience is delivered via embedded Power BI service.

For a quick tutorial on the visualization experience, visit Microsoft's [Use visuals in Power BI](https://learn.microsoft.com/en-us/training/modules/visuals-in-power-bi/){target="_blank"}.

### Notable experience changes {#notable-experience-changes}

The following are changes in the new experience (Advanced BI Analytics) from the old experience (Revenrue Explorer/Advanced Report Builder).

* The date-type filter functions equivalently; however, the syntax for specifying values changed. In your existing custom reports, all date-type filter values&mdash;except for "Day of the Week"&mdash;are automatically converted to their corresponding equivalents in the new experience. Support for "Day of the Week" values has been discontinued.

* The string-type filters are now case sensitive.

* Runtime formula field in the classic experience is no longer supported.

* Email subscription includes the PDF export rather than the HTML of the report. The new email subscription will not include the report definition.

* Deep link of report is not supported at this time.

* Report folder experience is not available at this time and was temporarily replaced by a flat list with type-ahead search. The name of the replicated report will carry the folder path, e.g. /folder1/folder2/report.

* PDF export is synchronous in the new experience, compared to being asynchronous in the classic experience.
Notable issues

>[!NOTE]
>
>You cannot include more than one Custom Field Group field in a visual for Model Performance Analysis (Leads) reporting area.

>[!MORELIKETHIS]
>
>[Metrics and Dimensions](/help/marketo/product-docs/reporting/advanced-bi-analytics/metrics-and-dimensions.md)
