---
unique-page-id: 15695939
description: Release Notes -Fall '18 - Marketo Docs - Product Documentation
title: Release Notes -Fall '18
exl-id: a3cc4cc5-38a6-4648-91f2-092daa9b0113
---
# Release Notes: Fall '18 {#release-notes-fall}

The following features are included in the Fall '18 release. Check your Marketo edition for feature availability.

Please click the title links to view detailed articles for each feature, if available.

## Core Platform Enhancements {#core-platform-enhancements}

**[Web Personalization](/help/marketo/product-docs/web-personalization/getting-started/workspaces-in-web-personalization.md)**

Web personalization now supports multiple workspaces.

## Marketo Sales Engage {#marketo-sales-engage}

* **SFDC Lightning Support**: Users migrating to or currently using Lightning can leverage MSE for smarter engagement across the buyer journey.

* **Expanded support: Microsoft Office**

   * Outlook as a Delivery Channel: Marketers can now leverage Outlook for email engagements, improving deliverability rates and response tracking.
   * Office 365 Email Support Improvements: Marketo Sales Engage is directly available in Outlook for Mac, Outlook for Windows, and the Outlook Web Application for Office 365 Email clients, making Marketo Sales Engage more readily available to all Office users.

* **Improved admin and user login experience**

   * Improved Admin Workflows: Admins will find a more efficient workflow when enabling team features through General Admin Settings.

## Marketo Sky {#marketo-sky}

For more details and updates, check our [Sky release notes](https://help.marketo.com).

* **Design System Updates**

* Design updates: refreshed color palette as well as consistent color usage, spacing, layout, shadows, and animation
* Typography updates for better readability
* Design enhancements to the tree navigation: purposeful use of color, clearer typography, new iconography, and badges for quick status checks
* Re-designed program summary screens

* **Marketing Activities Homepage**: Quickly access common functions right from the Marketing Activities homepage.

   * Take specific actions (i.e., start new programs and smart campaigns) and see important information around current programs, like programs and campaigns scheduled to run today, recently updated programs and assets, and total number of active trigger campaigns.

* **Design Studio Updates**: We've reimagined the Design Studio experience to help you move faster and be more productive.
* Design Studio Homepage: Create new assets, drag and drop images and files, and manage all existing assets.
* Design Studio List Views: Users now have the ability to view landing page templates and email templates in list-view format, allowing for quick navigation and bulk actions on a single asset type.
* Design Studio Asset Detail Pages: Save time and headaches by viewing, organizing, and performing bulk actions on all assets in one place.
* **Default Programs Now Available in Marketo Sky**: Marketo Sky now supports default programs, the versatile program style that allows you to create any campaign you can imagine.
* **Email Programs - Phase 1**: You can now view email programs in Sky. Take a look at the new design and [let us know what you think](https://go.marketo.com/NextGenUX---USA---Apr-2018-fcp_Landing-Page-Feedback.html).

## Analytics {#analytics}

**Bizible**

* **Reduce Required Dependency on CRM**

   * With the new option of defining Campaign rules within the Bizible settings, customers no longer need to jump through the hoops of installing a package or solution inside of their CRM to get started with Bizible. It’s now as easy as setting up an account, setting up the ad and CRM connections, then going through the standard settings and configurations. We expect that this will significantly improve onboarding times for our Sales Engineering team.

* **Discover GA**

   * Discover is out of beta and has started rolling out to new customers. We’re also migrating our current customer base from Bizible Measure to Bizible Discover. With the shift from beta to GA, we’ve made updates to the database schema to allow for more efficient and complex queries.

* **Single Sign-On**

   * Customers can now sign in to the Bizible web application using their company’s identity provider and credentials, which complies with enterprise security requirements.

**[Marketo Performance Insights Enhancements](/help/marketo/product-docs/reporting/performance-insights/performance-insights-overview.md)**

* **Usability enhancements**

   * Missing Acquisition Date Alert: To most accurately capture First- and Multi-Touch attribution insights, marketers are alerted when acquisition dates are missing from contact records so they can find and correct any issues.
   * Trend Chart Time Range Improvements: Users can now go back 24 months to compare program performance.
   * Scale-to-Fit Setting: The main dashboard bar chart is more easily readable to help compare program performance over time.
   * Alerts Icon: The new alerts icon displays all active alerts regarding data quality issues and setup notifications.

* **Engagement by Activity Date**: Users can select to view Engagement metrics by activity date or cost period.
* **ABM Named Account Filters**: Filter the Pipeline and Revenue dashboards by specific Named Accounts.

## Ad Networks {#ad-networks}

**[Refresh Token](/help/marketo/product-docs/demand-generation/social/social-functions/set-up-linkedin-lead-gen-forms.md)**

We’ve implemented a refresh token within our retargeting and LinkedIn Lead Gen Form solutions that extends access time to one year before re-authentication is required.

## API {#api}

**Lead Map REST API**

Marketo now supports the use of email-disposition fields over the Lead APIs (includes Black Listed, Marketing Suspended, Email Suspended, and Relative Urgency).

>[!NOTE]
>
>As part of the Q3 release we will be upgrading the OAuth version for GoToWebinar from 1.0 to 2.0. This change is being made in advance of GoToWebinar deprecating the support for OAuth 1.0 in January 2019. If you are a GoToWebinar customer, you will need to re-authenticate through LaunchPoint (in the Admin area) before January 2019 to ensure that your integration will continue working.

>[!NOTE]
>
>Marketo is also upgrading libraries related to identity and authentication. While the upgrade is underway, you may notice intermittent errors if you have an active session open. If you experience issues, please log out and back in to your subscription.
