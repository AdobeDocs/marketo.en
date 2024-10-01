---
description: Salesforce Sync Observability Metrics Dashboard - Marketo Docs - Product Documentation
title: Salesforce Sync Observability Metrics Dashboard
hide: yes
hidefromtoc: yes
feature: Reporting
---
# Salesforce Sync Backlog Metrics  {#salesforce-sync-backlog-metrics}

Review your sync performance throughputs and sync backlogs with this dashboard.

## Sync Throughput and Backlog {#sync-throughput-and-backlog}

1. In Marketo Engage, go to the Admin area.

   SCREENSHOT

1. Select Salesforce.

   SCREENSHOT

The statistics reflect the throughput and backlog status for every object type under sync for the last 24 hours. The object types include all objects under sync, including: Lead, Contact, Account, Opportunity, Campaign, User and Custom Objects. The throughput statistics is auto refreshed every 15 minutes, but you can refresh manually using the refresh icon. The backlog is fetched every hour.

   >[!NOTE]
   >
   >Statistics are updated on a rolling basis, not by calendar day.

   SCREENSHOT

<table><thead>
  <tr>
    <th>Field</th>
    <th>Description</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Max records synced / hr</td>
    <td>The maximum number of records synced per hour (maximum throughput) observed in the last 24 hours for the object type. The 24-hour period rolls with time, not the calendar day.</td>
  </tr>
  <tr>
    <td>Min records synced / hr</td>
    <td>The minimum number of records synced per hour (minimum throughput) observed in the last 24 hours for the object type. The 24-hour period rolls with time, not the calendar day.</td>
  </tr>
  <tr>
    <td>Average records synced / hr</td>
    <td>The average number of records synced per hour (minimum throughput) observed in the last 24 hours for the object type. The 24-hour period rolls with time, not the calendar day. This is calculated as total number of records synced in the last 24 hours.</td>
  </tr>
  <tr>
    <td>Sync Backlog</td>
    <td>The backlog of records pending sync for the object type. It is the sum total of backlog pending sync in both directions (from Salesforce to Marketo Engage, and vice versa). The backlog from Salesforce is obtained using an API call to Salesforce, and the backlog from Marketo Engage is calculated using the statistics obtained from the change data log. This is calculated every hour. The next two fields in this table inform when the backlog was last calculated and the next schedule for calculation, respectively.</td>
  </tr>
  <tr>
    <td>Estimated Backlog (time)</td>
    <td>Estimate of the time required to sync the backlog per object type. Calculated as Sync Backlog/Average records synced per hour.</td>
  </tr>
  <tr>
    <td>Backlog last fetched</td>
    <td>The time of the last backlog calculation.</td>
  </tr>
  <tr>
    <td>Backlog next fetch</td>
    <td>The time of the next backlog calculation.</td>
  </tr>
  <tr>
    <td>Backlog Status</td>
    <td>This shows whether the backlog has grown in the last 6 hours. It is inferred as 'Growing' if the current backlog is greater than the backlog recorded 6 hours ago. Otherwise, it is shown as 'Normal.' This is aimed at showing if the sync throughput is catching up with the backlog.</td>
  </tr>
</tbody></table>

## Backlog Trend {#backlog-trend}

The backlog trend reflects changes in the backlogs recorded over the last 5 days. The backlog is shown in a 4-hour time interval spread over 5 days. Therefore, the graph will show 6 intervals per day times 5 days, which equals 30 intervals.

Backlog is observed at a particular 4-hour time interval on the x-axis. This value is for all the objects under sync. This is the total of the backlog in Salesforce and Marketo Engage waiting to sync over.

   SCREENSHOT
