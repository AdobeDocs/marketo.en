---
description: Set up the Analytics section for your new Marketo Engage instance.
title: New Instance Best Practices - Analytics Checklist
hide: yes
hidefromtoc: yes
feature: Getting Started
---
# New Instance Best Practices: Analytics Checklist {#new-instance-best-practices-analytics-checklist}

The Analytics section offers global reports that analyze the performance of your marketing efforts. Learn about the necessary steps to navigate them.  

Remember to [download the checklists](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) and track your progress.

## Tree {#tree}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Organization: Naming, folders, and archiving</td>
    <td><li>Use a report naming convention to differentiate reports in the Global reports tab.</li>
    <ul><li>An example of good naming convention practice is [Report Type] [Global vs. BU-Specific Tag] [Report Description] such as [Email Performance]-[Global]-[180 Days Email Engagement].</li></ul> <li>Identify reports that should be shared with different user groups within your organization (e.g., sales team, marketing leadership) and organize the reports by folder inside the Group Reports folder in Analytics for Global Reports.</li> 
    <li>Archiving should be limited to the Global Reports folder, as these are always-on reports.   <ul><li>Limit archiving to organizational changes such as reducing or adding relevant business units if you are reporting based on a business unit structure.</li></ul></td>
  </tr>
  <tr>
    <td>Workspaces (if applicable)</td>
    <td><li>Replicate the Global Reports and folder structure across workspaces, if you use workspace, to maintain consistent reporting for your teams. These reports would be contained in the Group Reports folder.</li></td>
  </tr>
  <tr>
    <td>My Reports</td>
    <td><li>Identify and create the reports needed for your use in the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/creating-reports/understanding-my-reports-and-group-reports">My Reports</a> section. Use this private report section as your sandbox for Global Reports. These are only available to the user creating the report.</li>
    <li>Use your organization's naming convention to identify the report and the usage so that you can reconcile your reports in My Reports with reports in Group Reports.</li></td>
  </tr>
  <tr>
    <td>Group Reports</td>
    <td><li>Group Reports are your organization's Global Reports and should report on overall activity for your Marketo Engage organization.</li>
    <li>Consider creating <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/clone-a-report-to-group-reports" target="_blank">cloneable core reports</a> you expect each business unit to use the most to reduce the time needed to pull the report and ensure data correctness. See the details in the 'Basic Reporting - Global Reports' table [INSERT LINK TO BOOKMARKED SECTION].
    <ul><li>People Performance Report (all-time and time-based)- by source, month</li>
    <li>Program Performance Report (by cost month, time-based)</li>
    <li>Email Performance Report (time-based)</li></ul>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-activity/report-email-campaign-performance-across-workspaces" target="_blank">Turn on the "Global Reporting"</a> in the report's Setup tab to include the data from all your Workspaces in the Email Performance and Email Link Performance reports. If you have more than one workspace, you only need to enable this in the default workspace.</li>
    <br>TIP: Create the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists" target="_blank">Smart List</a> with the filters that you want to include in most of your reports in the 'Database' section. When you need to update the Smart List criteria, you could update it in one place instead of updating it in all the Global Reports.</td>
  </tr>
</tbody>
</table>

## Subscriptions {#subscriptions}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Subscriptions</td>
    <td><li>Align with your marketing leader regarding people who should review report results and their cadence during implementation.</li> <li>Use subscriptions to distribute data to need-to-know people in your organization without exhausting a named user license.</li>
    <br>TIP: The subscription emails are usually sent during the nighttime. If you want people to access the real-time report data, you will need to add people as users, so they can directly check the report.
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/subscribe-to-a-basic-report">Set up subscriptions</a> according to the desirable cadence(daily/weekly/monthly) for each team's ongoing monitoring. You can also <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-subscriptions/manage-report-subscriptions">view all your subscriptions</a> in one place under the Subscriptions tab in Analytics.</li></td>
  </tr>
</tbody>
</table>

## Global Reports {#global-reports}

Identify reports that should be shared with different user groups within your organization (e.g., sales team, marketing leadership). Create proper folder structure for each team/user group/business unit to organize the reports within Group Reports when cloning the reports. Consider setting up global reports such as: 

<table>
<thead>
  <tr>
    <th style="width:20%">Report Type</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Email Performance Report</td>
    <td><li>Create Global, Workspace/Business Unit-wide reports with the correct emails selected.</li>
    <li>Create a local email performance report in all your cloneable program templates.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/editing-reports/change-a-report-time-frame">Use a relevant timeframe</a> (e.g., YTD, last 90 days, etc.) for the report to provide you with an accurate view of standard email engagement and deliverability metrics.</li>
    <br>TIP: <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/email-setup/filtering-email-bot-activity">Turn on 'Bot Activity' filtering in 'Admin&gt;Email'</a> to avoid logging or identify if logging is enabled for the bot activities. <a href="https://nation.marketo.com/t5/product-documents/filtering-email-bot-activity-feature-latest-release/ta-p/324860">Include the filter to allow only Opened/Clicked activities with the "Is Bot Activity" constrained set to "False"</a> in the Smart List of your cloneable Global Reports.</td>
  </tr>
  <tr>
    <td>People Performance Report</td>
    <td>NOTE: It's recommended to have a proper <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags">channel and tag strategy</a> for every Marketo Engage implementation before you can track the people acquired through each, and the ROI of your marketing investments by channel.
    <br>
    <li>Determine the criteria you will use to measure the performance of your lead acquisition programs and create your time-based (current year, last rolling 12 months view, or 180 days) standard reports based on these metrics:</li> <ul><li>Acquisition Program: Marketo Engage program that is credited for acquiring the lead.</li>
    <li>Person Source: The source category for how the record came to be known to your database (based on the Source list of values in your CRM)</li></ul>
    <li>Measure people created by week or month. This report will provide you with a measure of your Database growth rate and whether you are approaching or will soon exceed your Database size limit.</li>
    <li>Filter the metrics in People Performance Reports by <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/editing-reports/add-custom-columns-to-a-person-report">using your Smart Lists as custom columns.</a></li>
    <br>TIP: Create the Smart Lists for the custom columns you want to add to the People Performance Report in 'Database' instead of 'Marketing Activities', so you can see the Smart List name properly and clearly when it is selected in the report.</td>
  </tr>
  <tr>
    <td>Program Performance Report</td>
    <td>NOTE: This report requires that you have your channels, progression statuses, and success steps defined in the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/tags/create-a-program-channel">Admin > Tags area</a>. <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/program-performance-report/create-a-program-performance-report">Measure the effectiveness of your marketing tactics</a> within selective programs.</li>
    <li>Manage program membership (using Smart Campaigns to update acquisition program, status, success statuses) according to best practices within Marketing Activities.</li>
    <li>Measure based on costs for current year and rolling 12 months.
    <ul><li>Remember that maintaining <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/programs/working-with-programs/using-period-costs-in-a-program">Period Costs</a> is critical to leveraging the Program Performance Report.</li></ul>
    <br>TIP: To aggregate and view any <a href="https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/quick-wins/import-a-list-of-people">imported lists</a> in the Program Performance Reports, ensure your teams select appropriate Acquisition Program for tagging. Consider <a href="https://experienceleague.adobe.com/en/docs/marketo-learn/tutorials/programs-and-campaigns/default-programs/create-and-measure-default-programs">creating a default program</a> to be selected as the Acquisition program when the lists imported don't apply to any channel. This ensures any person imported has a valid acquisition program related to its source, business unit, channel, etc. instead of a blank value.</td>
  </tr>
  <tr>
    <td>Landing Page Performance Report</td>
    <td><li>Create the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-performance-report">Landing Page Performance Report</a> as a global report so you can <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/landing-page-actions/filter-a-landing-page-performance-report">filter and review the numbers</a> of all your Design Studio Landing Pages or Marketing Activities Landing Pages in one place.</li>
    <li>For the programs with landing page(s), consider <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-performance-report">creating a dedicated local report within the program template</a> so you can review the performance at the program level.</li></td>
  </tr>
  <tr>
    <td>Web Page Activity Report</td>
    <td>NOTE: Only web pages (external and Marketo landing pages) that have <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website">the Munchkin JavaScript</a> enabled will be tracked in this report. Consider placing the JavaScript code in the Tag Management Platform, such as <a href="https://developers.marketo.com/blog/integrating-munchkin-with-google-tag-manager/">Google Tag Manager</a>, to avoid hardcoding the code on every webpage.
    <br>
    <li>Create the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/web-page-activity-report">Web Page Activity Report</a> as a global report so you can review the numbers of all your web pages in one place. Note that your external web page activities are only reflected in the Web Page Activity reports.</li></td>
  </tr>
</tbody>
</table>

## Local Reports {#local-reports}

Some Marketo Engage reports are best deployed as local assets within specific programs in 'Marketing Activities', as their best use is in a more limited set of programs and assets. Consider setting up basic reports such as:  

<table>
<thead>
  <tr>
    <th style="width:20%">Report Type</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Email Link Performance Report</td>
    <td><li>Create <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/email-programs/email-program-data/email-link-performance-report" target="_blank">Email Link Performance Report</a> within programs sending emails and your drip campaigns to provide you with insights into the links people click on within your email sends.</li></td>
  </tr>
  <tr>
    <td>Campaign Activity Report</td>
    <td><li>Create the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/campaign-activity-report" target="_blank">Campaign Activity Report</a> and choose a period within your operational folder in 'Marketing Activities'.</li>
    <li>Set up reports to monitor the triggers for each use case and <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/reporting/basic-reporting/report-types/campaign-activity-report" target="_blank">apply campaign filters</a>, for example, Behavior Scoring triggers, Lifecycle qualification triggers, Interesting Moments triggers.</li></td>
  </tr>
  <tr>
    <td>Engagement Stream Performance Report (if applicable)</td>
    <td><li>Create <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/drip-nurturing/reports-and-notifications/engagement-stream-performance-report" target="_blank">Engagement Stream Performance Report</a> to measure the effectiveness of content and stream deployed within your Engagement Program.</li>
    <li>Consider <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/group-email-reports-by-segmentations" target="_blank">using the "Segmentation" filter in the report's Setup tab</a> and grouping the reporting data by the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation" target="_blank">segment</a> (e.g., person source, industry) used in your Engagement Program. This will help get deeper insights into each segment's engagement patterns, guiding you to make strategic changes to improve your Engagement program (content, stream, stream cadence, etc.).</li></td>
  </tr>
</tbody>
</table>
