---
description: AWS Migration - Marketo Engage Docs - Product Documentation
title: AWS Migration
feature: Getting Started
hide: yes
hidefromtoc: yes
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

* Add the following IP addresses and keep your current IPs as-is:

   * 54.160.246.246
   * 54.237.141.197
   * 52.20.211.99

## Expected service impacts

The impacts below require no action on your part.

* **CRM integrations and LaunchPoint services** will be disabled but should resume automatically afterward. 
* **Landing pages, forms, and data collection** will be unavailable, and a maintenance message will be displayed instead. 

## Updates and support

For the latest updates, bookmark this page. If you have any questions, contact Adobe Support via the Support portal in the Admin Console or [Experience League](https://experienceleague.adobe.com/en/support).

TO ADD: POD/DATA CENTER DETAILS
