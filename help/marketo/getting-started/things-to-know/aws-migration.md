---
description: AWS Migration - Marketo Engage Docs - Product Documentation
title: AWS Migration
feature: Getting Started
exl-id: a4bb6c23-ec63-43ec-9fbe-b1cb3928f233
---
# AWS Migration {#aws-migration}

Over the next several months, all Marketo Engage subscriptions are being migrated from a private data center to the AWS public cloud to improve reliability, scalability, and speed.

You will receive an email as well as an in-app notification approximately 30 days prior to migration. Use this guide to prepare.

## Recommended actions {#actions}

During your migration window, all Marketo Engage services will be unavailable. We recommend taking the following steps to mitigate any impact on your business.

* **Avoid creating or updating leads/people** or running processes that modify Person records.

* **Do not trigger follow-on processes**, as scheduled campaigns will be paused.

* **Temporarily disable any integrations** that send or receive data to or from Marketo Engage.

* **Avoid running** data imports or exports or any major lead/person-generation campaigns.

* **Review and update IP allowlists** for login, API access, email sending, web tracking, and integrations.

* **Add new IP addresses** and keep your current IPs as-is. See the IP addresses to add via the [table below](#ip-addresses).

## Expected service impacts {#impacts}

The impacts below require no action on your part.

* **CRM integrations and LaunchPoint services** will be disabled but should resume automatically afterward.
* **Landing pages, forms, and data collection** will be unavailable, and a maintenance message will be displayed instead.

>[!NOTE]
>
>If you use [external forms](/help/marketo/product-docs/demand-generation/forms/form-actions/embed-a-form-on-your-website.md){target="_blank"} and want to avoid losing form submission data collected while Marketo Engage is unavailable during your migration window, contact [Adobe Support](https://experienceleague.adobe.com/en/support){target="_blank"} **at least two business days** beforehand and provide the Form ID and your subscription's Munchkin ID.

## Identify your data center/pod {#identify}

Before reviewing the tables below, [learn how to identify](/help/marketo/getting-started/things-to-know/system-status-notifications.md#identify) what data center and pod/server your subscription is located in.

## Schedule {#schedule}

New dates and data center/pod information is periodically added or changed, so monitor this schedule for updates.

+++July schedule
<table>
 <tbody>
  <tr>
   <th style="width:25%">Date</th>
   <th style="width:25%">Data Center/Pod</th>
   <th style="width:25%">Time</th>
   <th style="width:25%">Status</th>
  </tr>
  <tr>
   <td>July 8, 2026</td>
   <td>AB69<br>
   AB64</td>
   <td>5 p.m. PDT<br>
   6 p.m. PDT</td>
   <td>Completed<br>
   Completed</td>
  </tr>
  <tr>
   <td>July 9, 2026</td>
   <td>AB70</td>
   <td>5 p.m. PDT</td>
   <td>Completed</td>
  </tr>
  <tr>
   <td>July 11, 2026</td>
   <td>AB46</td>
   <td>10 a.m. PDT</td>
   <td>Completed</td>
  </tr>
  <tr>
   <td>July 13, 2026</td>
   <td>NLD101</td>
   <td>10 a.m. PDT</td>
   <td>Completed</td>
  </tr>
  <tr>
   <td>July 15, 2026</td>
   <td>NLD102<br>
   NLD104</td>
   <td>10 a.m. PDT<br>
   11 a.m. PDT</td>
   <td>Completed<br>
   Completed</td>
  </tr>
  <tr>
   <td>July 17, 2026</td>
   <td>NLD103<br>
   NLD105</td>
   <td>10 a.m. PDT<br>
   11 a.m. PDT</td>
   <td>Completed<br>
   Completed</td>
  </tr>
  <tr>
   <td>July 21, 2026</td>
   <td>AB54</td>
   <td>5 p.m. PDT</td>
   <td>Completed</td>
  </tr>
  <tr>
   <td>July 23, 2026</td>
   <td>AB48</td>
   <td>5 p.m. PDT</td>
   <td>Completed</td>
  </tr>
  <tr>
   <td>July 31, 2026</td>
   <td>AB43</td>
   <td>3 p.m. PDT</td>
   <td>Completed</td>
  </tr>
  </body>
</table>

+++

+++August schedule

<table>
 <tbody>
  <tr>
   <th style="width:25%">Date</th>
   <th style="width:25%">Data Center/Pod</th>
   <th style="width:25%">Time</th>
   <th style="width:25%">Status</th>
  </tr>
  <tr>
   <td>August 12, 2026</td>
   <td>AB61<br>
   AB17</td>
   <td>3 p.m. PDT<br>
   4 p.m. PDT</td>
   <td>Completed<br>
   Completed</td>
  </tr>
  <tr>
  <td>August 13, 2026</td>
   <td>AB68</td>
   <td>4 p.m. PDT</td>
   <td>Completed</td>
  </tr>
  <tr>
   <td>August 20, 2026</td>
   <td>AB42</td>
   <td>5 p.m. PDT</td>
   <td>Completed</td>
  </tr>
  <tr>
   <td>August 26, 2026</td>
   <td><i>AB40</i><br>
   AB50</td>
   <td><i>5 p.m. PDT</i><br>
   6 p.m. PDT</td>
   <td><i>Postponed (date TBD)</i><br>
   Completed</td>
  </tr>
  <tr>
   <td>August 28, 2026</td>
   <td><i>AB53</i><br>
   AB56</td>
   <td><i>3 p.m. PDT</i><br>
   4 p.m. PDT</td>
   <td><i>Postponed (date TBD)</i><br>
   Completed</td>
  </tr>
  </body>
</table>

+++

<table>
 <tbody>
  <tr>
   <th style="width:25%">Date</th>
   <th style="width:25%">Data Center/Pod</th>
   <th style="width:25%">Time</th>
   <th style="width:25%">Status</th>
  </tr>
  <tr>
   <td>September 8, 2026</td>
   <td>AB01<br>
   AB02</td>
   <td>5 p.m. PDT<br>
   6 p.m. PDT</td>
   <td>On schedule<br>
   On schedule</td>
  </tr>
  <tr>
   <td>September 10, 2026</td>
   <td>AB03<br>
   <i>AB04</i></td>
   <td>5 p.m. PDT<br>
   <i>6 p.m. PDT</i></td>
   <td>On schedule<br>
   <i>Postponed (date TBD)</i></td>
  </tr>
  <tr>
   <td>September 15, 2026</td>
   <td>AB05<br>
   AB06</td>
   <td>5 p.m. PDT<br>
   6 p.m. PDT</td>
   <td>On schedule<br>
   On schedule</td>
  </tr>
  <tr>
   <td>September 17, 2026</td>
   <td>AB07<br>
   AB08</td>
   <td>5 p.m. PDT<br>
   6 p.m. PDT</td>
   <td>On schedule<br>
   On schedule</td>
  </tr>
  <tr>
   <td>September 22, 2026</td>
   <td>AB09<br>
   AB12</td>
   <td>5 p.m. PDT<br>
   6 p.m. PDT</td>
   <td>On schedule<br>
   On schedule</td>
  </tr>
  <tr>
   <td>September 25, 2026</td>
   <td>AB10<br>
   AB11</td>
   <td>4 p.m. PDT<br>
   5 p.m. PDT</td>
   <td>On schedule<br>
   On schedule</td>
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

## Updates and support {#support}

For the latest updates, bookmark this page. If you have any questions, contact Adobe Support via the Support portal in the Admin Console or [Experience League](https://experienceleague.adobe.com/en/support){target="_blank"}.

## FAQ {#faq}

**Where is the data stored?**
All Marketo user data is stored on Amazon Web Services (AWS). Marketo has migrated its infrastructure from owned physical data centers to AWS's enterprise-grade cloud platform.

**Where specifically is personal data stored?**
Personal data is stored in Amazon Aurora, AWS's fully managed relational database service. Aurora replicates data six ways across three separate Availability Zones within the AWS region to protect personal data against hardware failure, storage degradation, and localized infrastructure events.

**Who owns the storage environment?**
The storage infrastructure is owned and operated by Amazon Web Services (AWS). Adobe (Marketo) operates as a customer of AWS under a shared responsibility model: AWS is responsible for the security and availability of the underlying infrastructure, while Adobe is responsible for the security of the data and applications running within it.

**What are the full details on production, backup/DR locations, and storage technology?**
Marketo uses Amazon Aurora, a cloud-native relational database engine fully managed by AWS, as its primary database technology. Aurora decouples compute and storage, automatically replicating data six ways across three Availability Zones within the production region and requiring a quorum of four copies to confirm any write operation.

Aurora also performs continuous, automatic backups to Amazon S3 in real time, enabling Point-in-Time Recovery (PITR) to any second within the configured retention window.

At this time, Marketo's Aurora deployment operates within a single AWS region, without cross-region replication. Production data remains within the designated regional infrastructure, and disaster recovery is provided through Aurora's multi-AZ storage redundancy and continuous backups rather than geographic failover to a secondary region. This may be evaluated further as Marketo's AWS infrastructure matures.
