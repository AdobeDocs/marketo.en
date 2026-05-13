---
description: Acquisition API operational program template. Use it to capture leads via API.
title: OP-Acquisition-API
feature: Programs
exl-id: abf7c4a0-c363-4e92-9a1f-197c3953c515
TQID: https://experienceleague.adobe.com/a-4w7mJg44cvotVtX2qwx1e4p8SKIbQU1jPWyQ0BzUA
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
topic_v2:
  - id: df401a2a-327d-468c-a5e4-b7b7ccd071a0
    internal-label: Data integration
  - id: ebde5b41-29c9-4f5e-9ef6-1197e85409e3
    internal-label: Data management
---
# OP-Acquisition-API {#op-acquisition-api}

This example program is for operational processes to track the acquisition of records from API sources utilizing a Marketo Engage Default Program.

## Channel Summary {#channel-summary}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>Channel</th>
   <th>Membership Status</th>
   <th>Analytics Behavior</th>
   <th>Program Type</th>
  </tr>
  <tr>
   <td>Operational</td>
   <td>01-Member</td>
   <td>Operational</td>
   <td>Default</td>
  </tr>
 </tbody>
</table>

## Program Contains the Following Assets {#program-contains-the-following-assets}

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th>Type</th>
   <th>Template Name</th>
   <th>Asset Name</th>
  </tr>
  <tr>
   <td>Smart Campaign</td>
   <td>&nbsp</td>
   <td>Set Acquisition - Batch</td>
  </tr>
  <tr>
   <td>Smart Campaign</td>
   <td>&nbsp</td>
   <td>Set Acquisition - Trigger</td>
  </tr>
  <tr>
   <td>Folder</td>
   <td>&nbsp</td>
   <td>Campaigns (contains all Smart Campaigns)</td>
  </tr>
 </tbody>
</table>

![](assets/op-acquisition-api-1.png)

## Conflict Rules {#conflict-rules}

* **Program Tags**
  * Create tags in this subscription - _Recommended_
  * Ignore

* **Landing Page template with the same name**
  * Copy original template - _Recommended_
  * Use destination template

* **Images with the same name**
  * Keep both files - _Recommended_
  * Replace item in this subscription

* **Email templates with the same name**
  * Keep both templates - _Recommended_
  * Replace existing template

## Best Practices {#best-practices}

* Run the Batch Campaign first if you need to catch up in your data management.

* Consider utilizing similar programs to ensure alignment to best practices across all input sources to include your CRM or Data Integrations.

* Within channel specific channel marketing initiatives, ensure acquisition is captured when needed.
