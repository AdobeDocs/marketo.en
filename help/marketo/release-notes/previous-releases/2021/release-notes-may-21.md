---
description: Release Notes - May 2021 - Marketo Docs - Product Documentation
title: Release Notes - May 2021
exl-id: e3de60a2-17bd-4760-848e-6e931ad85b3c
---
# Release Notes: May 2021 {#release-notes-may-21}

The following features are included in the May '21 release. Check your Marketo edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will be released on **May 7, 2021**.

## Account-Based Experiences {#Account-based-eaperiences}

* **Account Smart Lists (general availability)** ![](assets/yellow-star.png): Dynamically identify and qualify accounts with desired account and person attributes to target in cross-channel marketing campaigns and send timely alerts to Sales to close deals faster. This new capability allows for robust automation of account-based marketing strategies. Account Smart Lists are available for customers with Target Account Management that are on the next-generation user experience.

## Next-Generation User Experience {#next-generation-user-experience}

With global search preview, marketers can quickly see where a shared asset exists in their instance. Browser tabs display the location to improve navigation in Marketing Activities or Design Studio. Additional tree and global search filters help refine your search criteria. Drag-and-drop functionality within the tree has been reinstated, allowing you to move folders and assets quickly and efficiently within the main app areas. Newly updated icons (that meet Adobe’s accessibility standards) and status badges allow marketers to distinguish between folders and assets quickly and easily in the tree and identify the status of programs and assets.

## Experience Automation {#experience-automation}

* **Execute Campaign Flow Steps**: Streamline campaign creation workflows and improve campaign performance with a new flow step for Smart Campaigns. Create and save centralized, template campaigns for repetitive tasks in your workspace, such as country code normalization, to be called and run from any Smart Campaign via the new “Execute Campaign” flow step. Linked campaigns will run in the designated order and ensure task completion before advancing to the next flow step. Quickly edit the flow in just one centralized campaign to update every Smart Campaign that's using it to streamline data management, lead scoring and routing workflows.

## Cross-Channel Orchestration {#cross-channel-orchestration}

* **Sensitive Data Fields in Forms**: Protect customer’s personally identifiable information (PII) from showing in Adobe Marketo Engage forms by defining data fields as sensitive and restricting form prefill for those fields. Whenever a visitor views a form on the landing page, the fields defined as sensitive will not show any prefilled data.

* **Block Spam Form Submissions**: Protect your Adobe Marketo Engage database from junk data that can cause invalid alerts to sales, trigger campaign backlogs, and create unwanted activities. The new validation mechanism rejects invalid form submissions and stops bot attacks. Your data is cleaner, and your marketing campaigns run as intended, minimizing the risk of sending unqualified leads to sales.  

* **Email Program Approval Warning**: Prevent sending erroneous emails when the new edits were made to a previously approved program.  The warning acts as a guardrail when a marketer applies changes to an email that is already approved, but then forgets to approve the latest changes, and sends the email out to a large audience with no content, bad content, or old content.

* **Filter-out Email Bots Activity**: Prevent unintended sales alerts and inaccurate email reporting through the new email bot activity filtering capability. Identify and filter out opens and clicks that can be associated with email bots inspecting links leading to false triggers and sales alerts, or incorrect reporting.  

## API Enhancements {#api-enhancements}

Several critical updates to Bulk and Lead APIs, including the ability to export custom object data in bulk, associate company with lead in bulk, ability to filter bulk activity extract based on a primary attribute, and the ability to create and update program membership.

* **Nest Event Programs**: In Adobe Marketo Engage you can create, clone, or move event programs under other program types. This functionality is now permitted in assets API.

* **Enhanced Delete Program API**: Allows integrated applications to delete programs containing additional types of assets, without requiring users to do so manually from Adobe Marketo Engage.

* **Program Membership**: Marketers can query all program member records for a select program given different criteria, such as program member status. Share this information with an external application, business intelligence tool, or Adobe Experience Cloud to and improve segmentation and create more targeted engagement.

* **Bulk Custom Object Extract**: Bulk data export complements the import capabilities that data analysts are already enjoying in Adobe Marketo Engage. Now they can extract data stored in the 1st level Adobe Marketo Engage Custom Objects in bulk, load this data into another application, data warehouse, or BI (Business Intelligence) tool to gain better insights into the data in the Adobe Marketo Engage instance.  Custom object bulk data movement is bi-directional and can be scheduled at a convenient time.

* **Custom Fields Metadata API**: Save time by automating the creation of custom fields while setting up your Adobe Marketo Engage integrations with a 3rd party application. This automation especially benefits customers with multiple Adobe Marketo Engage instances who are now able to streamline custom fields creation that used to require manual work in each instance. Streamline custom fields creation and save time on this resource consuming activity.  

* **Bulk Activity Extract API**: Gain control over the amount and type of data when performing bulk extractions. Filter out unnecessary data points and control the number of API calls necessary to extract activity data in bulk.  For example, select open emails, visit a webpage, or change in lead score and leave behind other changes in value you don’t want to analyze. Streamline the process to decrease the number of API calls and data cleanup.  

* **Lead API**: Identify leads in Adobe Marketo Engage that have Adobe ECID (Experience Cloud ID) associated with them.  Adobe Marketo Engage customers can create a list of leads from a select campaign and use the ECIDs (Experience Cloud ID) to create reporting in Adobe Analytics for that specific list. Integration between Adobe Marketo Engage and Adobe Experience Cloud opens up unlimited opportunities for segmentation, targeting and reporting.

* **Bulk Lead Import API**: Control bulk lead import and resources it takes. This enhancement creates association between lead and company during bulk lead import process. Increase efficiency and of working with data and decrease usage if API calls.

* **Web API based Integration for the Microsoft Dynamics Online Customers**: MS Dynamics Web API was introduced with version 8.0 REST protocol and implements OData (Open Data Protocol) v4. OData is an OASIS (Organization for the Advancement of Structured Information Standards) standard for building and consuming RESTful services over rich data. Adobe Marketo Engage customers that require integration with Microsoft Dynamics using this method are currently being migrated to Web API-based connection from SOAP (Simple Object Access Protocol).

## Marketing Data Environment {#marketing-data-environment}

* **XLSX Export**: We upgraded export capabilities throughout the product to support XLSX in place of XLS. This means that anywhere in the product where XLS export is currently supported, this option will be replaced with an option to export to XLSX instead. This change will affect the file names for all Excel exports of reports and other data from Adobe Marketo Engage.

* **Search by Lead ID**: Quickly access lead record searching by Adobe Marketo Engage lead ID within the lead database or static list. In the Quick Find window simply type `[id]` with the corresponding number, then the lead information will be displayed. Users can quickly review lead, company, or opportunity details.

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Integration with LinkedIn Lead Gen Forms (Beta)**: Gain deep visibility into your LinkedIn channel spend and ROI with Bizible premium attribution solution. Through the latest integration with LinkedIn’s Lead Gen Forms, Bizible gains insight into forms that have been submitted within the LinkedIn platform. These form fills are matched against leads from your CRM (Customer Relationship Management) or Adobe Marketo Engage instance so that they’re eligible for attribution and can be tracked against your other marketing engagements.

## Announcements {#announcements}

* **Marketo Product Docs Switching Platforms**: We’re excited to announce that the Marketo Product Docs has joined the Adobe Experience League as of Friday, May 7. You’ll still be able to use the URL: docs.marketo.com, and if you have any existing articles bookmarked, you’ll be redirected. All product docs are available on the new platform, with enhancements planned for later this year.

* **Streamlined User Administration and Single Sign-on Powered by Adobe Identity System**: Beginning July 2021, the new Adobe Marketo Engage customers will be onboarded using Adobe user credentials. Migration of current customers to the integrated identity system will not occur until mid-2022 and no customer action is required until further notice. Single sign-on enables IT/Security admins to manage multiple Adobe Marketo Engage product instances along with other Experience Cloud solutions as well as configure SSO (Shared Services Organization) through a common console. Admins can conveniently manage user groups and user entitlements through a common Admin Console.

**_Product Release Webinar_**

[May 2021 Marketo Engage Release Webinar](https://engage.marketo.com/May_21_Release_webinar_RegistrationPage.html)
