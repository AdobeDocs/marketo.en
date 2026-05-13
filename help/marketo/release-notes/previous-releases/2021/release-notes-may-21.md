---
description: Release Notes - May 2021 - Marketo Docs - Product Documentation
title: Release Notes - May 2021
exl-id: e3de60a2-17bd-4760-848e-6e931ad85b3c
feature: Release Information
TQID: https://experienceleague.adobe.com/9YQq7Ynf4XGDyhYPq4-pB3Zwh89DD-H13h8E-BRInRQ
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
    internal-label: Design Studio
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
  - id: d0251300-e25f-466f-9856-7e11ce8fa7aa
    internal-label: Smart Lists
  - id: d5c7388a-594e-4d15-9b39-98d6ce479e8b
    internal-label: Microsoft Dynamics
  - id: fd4ca7b1-bd80-47f4-ad1a-846912e45cc5
    internal-label: Target Account Management
  - id: ffdd6159-0e10-4a57-8021-94e93bab8183
    internal-label: Event programs
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
    internal-label: Metadata
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: cc72dcf1-72e1-48cc-b434-e7c27d62d67c
    internal-label: Accessibility
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
    internal-label: Security
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
    internal-label: Insights
  - id: ebde5b41-29c9-4f5e-9ef6-1197e85409e3
    internal-label: Data management
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
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

With global search preview, marketers can quickly see where a shared asset exists in their instance. Browser tabs display the location to improve navigation in [!UICONTROL Marketing Activities] or [!UICONTROL Design Studio]. Additional tree and global search filters help refine your search criteria. Drag-and-drop functionality within the tree has been reinstated, allowing you to move folders and assets quickly and efficiently within the main app areas. Newly updated icons (that meet Adobe’s accessibility standards) and status badges allow marketers to distinguish between folders and assets quickly and easily in the tree and identify the status of programs and assets.

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

* **Web API based Integration for the [!DNL Microsoft Dynamics Online] Customers**: [!DNL MS Dynamics] Web API was introduced with version 8.0 REST protocol and implements OData (Open Data Protocol) v4. OData is an OASIS (Organization for the Advancement of Structured Information Standards) standard for building and consuming RESTful services over rich data. Adobe Marketo Engage customers that require integration with [!DNL Microsoft Dynamics] using this method are currently being migrated to Web API-based connection from SOAP (Simple Object Access Protocol).

## Marketing Data Environment {#marketing-data-environment}

* **XLSX Export**: We upgraded export capabilities throughout the product to support XLSX in place of XLS. This means that anywhere in the product where XLS export is currently supported, this option will be replaced with an option to export to XLSX instead. This change will affect the file names for all Excel exports of reports and other data from Adobe Marketo Engage.

* **Search by Lead ID**: Quickly access lead record searching by Adobe Marketo Engage lead ID within the lead database or static list. In the Quick Find window simply type `[id]` with the corresponding number, then the lead information will be displayed. Users can quickly review lead, company, or opportunity details.

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Integration with [!DNL LinkedIn] Lead Gen Forms (Beta)**: Gain deep visibility into your [!DNL LinkedIn] channel spend and ROI with Bizible premium attribution solution. Through the latest integration with [!DNL LinkedIn]’s Lead Gen Forms, Bizible gains insight into forms that have been submitted within the [!DNL LinkedIn] platform. These form fills are matched against leads from your CRM (Customer Relationship Management) or Adobe Marketo Engage instance so that they’re eligible for attribution and can be tracked against your other marketing engagements.

## Announcements {#announcements}

* **Marketo Product Docs Switching Platforms**: We’re excited to announce that the Marketo Product Docs has joined the Adobe Experience League as of Friday, May 7. You’ll still be able to use the URL: docs.marketo.com, and if you have any existing articles bookmarked, you’ll be redirected. All product docs are available on the new platform, with enhancements planned for later this year.

* **Streamlined User Administration and Single Sign-on Powered by Adobe Identity System**: Beginning July 2021, the new Adobe Marketo Engage customers will be onboarded using Adobe user credentials. Migration of current customers to the integrated identity system will not occur until mid-2022 and no customer action is required until further notice. Single sign-on enables IT/Security admins to manage multiple Adobe Marketo Engage product instances along with other Experience Cloud solutions as well as configure SSO (Shared Services Organization) through a common console. Admins can conveniently manage user groups and user entitlements through a common Admin Console.

**_Product Release Webinar_**

[May 2021 Marketo Engage Release Webinar](https://engage.marketo.com/May_21_Release_webinar_RegistrationPage.html)
