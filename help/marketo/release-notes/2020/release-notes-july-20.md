---
unique-page-id: 45416698
description: Release Notes -July '20 - Marketo Docs - Product Documentation
title: Release Notes -July '20
exl-id: 3c9b1f1d-961c-4bf8-8b99-37b483230506
---
# Release Notes: July '20 {#release-notes-july}

The following features are included in the July '20 release. Check your Marketo edition for feature availability.

>[!AVAILABILITY]
>
>Please note that, depending on your current package, items with a star ( ![(star)](assets/star-yellow.svg)) may require the purchase of a value add-on. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_** The following features will be released on **July 31, 2020**.

## Administration {#administration}

* **[“Used By” Export in Field Management](/help/marketo/product-docs/administration/field-management/export-used-by-data-for-a-field.md)**: Admins can now export all “Used By” asset links for a selected field into a CSV file. This enhancement can aid both admins and non-admins in cleaning up unused fields. Additionally, assets can now be opened in a new browser tab or window.

## Account-Based Marketing {#account-based-marketing}

![(star)](assets/star-yellow.svg)

* **Updated UI for Account Profiling**: Simplify the creation of your target account list in Account Profiling with streamlined steps all in a single screen.

<br>&nbsp;

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the coming months.

* **Forms Service**: We are introducing stronger form field syntax validation and the ability to block common bot patterns with new Secured Domains for Landing Pages capabilities. Blocking bot patterns can reduce spam form submissions and improve your database quality.

>[!NOTE]
>
>Full rollout of enhanced form field syntax validation has been postponed until after our Jan 2021 release.

* **Increased Asset API URI Size Limit**: The uniform resource identifier (URI) size limit is being increased from 8KB to 65KB in advance of the removal of “_method” parameter. When performing long query strings, this size limit increase will allow the data to to pass more easily. The removal of the "_method" parameter is part of an upcoming security upgrade.

## Sales Insight {#sales-insight}

![(star)](assets/star-yellow.svg)

* **[Sales Insight Enabled for Customers with Non-Native Salesforce CRM Integration](/help/marketo/product-docs/marketo-sales-insight/sales-insight-for-non-native-salesforce-integrations.md) (Beta)**: Marketo Engage customers with non-native Salesforce CRM integrations can now use Sales Insight to help their sales teams understand, prioritize, and interact with the most engaged leads and opportunities to enable smart selling and faster deals.

## Sales Connect {#sales-connect}

![(star)](assets/star-yellow.svg)

* **[Enhanced Two-Party Consent for Sales Calls:](/help/marketo/product-docs/marketo-sales-connect/phone/two-party-consent-settings.md)** Admins now have greater control over call recording configurations. [Enable call recordings](/help/marketo/product-docs/marketo-sales-connect/phone/enable-call-recording.md) with confidence that you comply with the two-party consent law. Automate the notification of the call being recorded and activate audio clips to be played before the call.

<br>&nbsp;

## Announcements & Deprecations {#announcements-deprecations}

* **Asset API "_method" Parameter Removal**: After September 2020, Asset API endpoints will no longer accept "_method" to pass Query Parameters in a POST body to bypass URI length limitations. To accommodate requests which required this parameter, the URI limits for Asset APIs will be increased from 8KB to 65KB.
* **[Munchkin Associate Lead](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/)**: With this release of the Munchkin JavaScript Client, version 159, we will begin deprecation of the Munchkin Associate Lead method. If invoked, you will receive a warning indicating that the method will be removed in a future release. Once removed, the method will no longer be functional and attempts to use it will fail. Marketo Engage customers who have used this method recently will be notified individually of their use.
* **Support for Internet Explorer**: As previously announced, Marketo Engage support for Internet Explorer 11 ends on **July 31, 2020**. We will continue to support Google Chrome, Mozilla Firefox, Apple Safari, and Microsoft Edge.
* **Sky Default Experience**: The option for admins or users to set Marketo Sky as the default experience will be removed in this release in preparation for an update to the primary user experience. More details on the update to the primary experience, scheduled for later this year, will be available in July. Users who have set Marketo Sky as their default experience, or have been granted access to Marketo Sky, can continue to access Marketo Sky from a tile on the My Marketo home page.
* **EdgeHTML (non-Chromium) Microsoft Edge support**: Marketo Engage will no longer support EdgeHTML versions of Microsoft Edge at the end of 2020. Beginning January 1, 2021, we will only support the latest Chromium version of Microsoft Edge.
