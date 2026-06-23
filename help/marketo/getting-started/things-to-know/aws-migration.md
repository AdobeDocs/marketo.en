---
description: AWS Migration - Marketo Engage Docs - Product Documentation
title: AWS Migration
feature: Getting Started
hide: true
exl-id: a4bb6c23-ec63-43ec-9fbe-b1cb3928f233
---
# AWS Migration {#aws-migration}

Over the next several months, all Marketo Engage subscriptions are being migrated from a private data center to the AWS public cloud to improve reliability, scalability, and speed.

You will receive an email as well as an in-app notification approximately 30 days prior to migration. Use this guide to prepare.

## Recommended actions

During your migration window, all Marketo Engage services will be unavailable. We recommend taking the following steps to mitigate any impact on your business.

* **Avoid creating or updating leads/people** or running processes that modify Person records.

* **Do not trigger follow-on processes**, as scheduled campaigns will be paused.

* **Temporarily disable any integrations** that send or receive data to or from Marketo Engage.

* **Avoid running** data imports or exports or any major lead/person-generation campaigns.

* **Review and update IP allowlists** for login, API access, email sending, web tracking, and integrations.

* **Add new IP addresses** and keep your current IPs as-is. See the IP addresses to add via the [table below](#ip-addresses).

## Expected service impacts

The impacts below require no action on your part.

* **CRM integrations and LaunchPoint services** will be disabled but should resume automatically afterward.
* **Landing pages, forms, and data collection** will be unavailable, and a maintenance message will be displayed instead.

## Identify your data center/pod {#identify}

Before reviewing the tables below, [learn how to identify](/help/marketo/getting-started/things-to-know/system-status-notifications.md#identify) what data center and pod/server your subscription is located in.

## Schedule {#schedule}

New dates and data center/pod information is periodically added, so be sure to check back here for details.

<table>
 <tbody>
  <tr>
   <th style="width:50%">Date</th>
   <th style="width:20%">Data Center/Pod</th>
   <th style="width:30%">Time</th>
  </tr>
  <tr>
   <td>July 8, 2026</td>
   <td>AB69<br>
   AB64</td>
   <td>5 p.m. PDT<br>
   6 p.m. PDT</td>
  </tr>
  <tr>
   <td>July 9, 2026</td>
   <td>AB70<br>
   AB43</td>
   <td>5 p.m. PDT<br>
   6 p.m. PDT</td>
  </tr>
  <tr>
   <td>July 11, 2026</td>
   <td>AB46</td>
   <td>10 a.m. PDT</td>
  </tr>
  <tr>
   <td>July 13, 2026</td>
   <td>NLD101</td>
   <td>10 a.m. PDT</td>
  </tr>
  <tr>
   <td>July 15, 2026</td>
   <td>NLD102<br>
   NLD104</td>
   <td>10 a.m. PDT<br>
   11 a.m. PDT</td>
  </tr>
  <tr>
   <td>July 17, 2026</td>
   <td>NLD103<br>
   NLD105</td>
   <td>10 a.m. PDT<br>
   11 a.m. PDT</td>
  </tr>
  </body>
</table>

## IP addresses to add {#ip-addresses}

Based on your data center, work with your IT department to get the respective IP addresses added.

<table>
<tbody>
<tr>
  <th style="width:25%">Data Center</th>
  <th style="width:75%">IP Addresses</th>
</tr>
<tr>
  <td>AB</td>
  <td>54.160.246.246<br>
  54.237.141.197<br>
  52.20.211.99</td>
</tr>
<tr>
  <td>NLD</td>
  <td>34.247.24.245<br>
18.200.201.81<br>
54.220.138.65</td>
</tr>
</body>
</table>

## Updates and support

For the latest updates, bookmark this page. If you have any questions, contact Adobe Support via the Support portal in the Admin Console or [Experience League](https://experienceleague.adobe.com/en/support){target="_blank"}.
