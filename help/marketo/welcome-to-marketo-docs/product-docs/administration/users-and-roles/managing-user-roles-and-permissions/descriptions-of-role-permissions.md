---
unique-page-id: 6848747
description: Descriptions of Role Permissions - Marketo Docs - Product Documentation
title: Descriptions of Role Permissions
---

# Descriptions of Role Permissions {#descriptions-of-role-permissions}

Descriptions of Role Permissions - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Below is a list of all available permissions that you can assign to your roles. Permissions are generally associated with specific functional areas inside Marketo and can help you control what areas and functionality different users have access to.

Some additional information about permissions:

* The “Access" permission gives a role permission to view and sometimes edit that part of the application.
* For a role to have access to the sub-permissions ("Create", "Delete", etc.), that role must have "Access" permission to that part of the application. For example, if you want to give someone permission for Edit Campaigns, they must have overall permission to Access Marketing Activities.
* You may be able to see actions or assets that you do not have permission to use. However, if you try to access them, you'll see a message warning you about your limited access.

### What's in this article? {#what-s-in-this-article}

[Available Permissions](#descriptionsofrolepermissions-availablepermissions)  
[Access Admin](#descriptionsofrolepermissions-accessadmin)  
[Access API](#descriptionsofrolepermissions-accessapi)  
[Access Calendar Presentations](#descriptionsofrolepermissions-accesscalendarpresentations)  
[Access Design Studio](#descriptionsofrolepermissions-accessdesignstudio)  
[Access Database](#descriptionsofrolepermissions-accessdatabase)  
[Access Marketing Activities](#descriptionsofrolepermissions-accessmarketingactivities)  
[Targeting and Personalization](#descriptionsofrolepermissions-targetingandpersonalization)

#### Available Permissions {#descriptionsofrolepermissions-availablepermissions}

When you [create or edit a role](../../../../../welcome-to-marketo-docs/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md), you can select which of the following permissions to allow for that role by checking the appropriate boxes.

![](assets/createnewrole.png)

#### Access Admin  {#descriptionsofrolepermissions-accessadmin}

View and make changes to settings in the My Account section of Admin.

* `Access Audit Trail - Gives users access to both Asset Audit Trail and Admin Audit Trail`
* `Access Channels` - Gives users access only to modify the Channel tag, not other custom tags
* Access Communication Limit - Gives users access to enable a communication limit in Admin
* `Access CRM - Gives users access to the CRM, such as Salesforce or Microsoft Dynamics, in Admin`
* `Access [Data.com](http://Data.com) - Gives users access to the Data.com flow action`
* `Access Email Admin - Gives users to Email Admin, to change default settings, such as unsubscribe and branding domains`
* `Access Event Partners - Gives users access to LaunchPoint in Admin`
* `Access Field Management - Gives users access to Field Management in Admin`
* `Access File Upload - Gives users the ability to upload images and files to the Design Studio  
  `
* `Access Landing Pages - Gives users access to Landing Pages in Admin  
  `
* `Access Location - Gives users access to Location in Admin for setting default language, locale, time zone, and currency`
* `Access Login History - Gives users access to User Login History in Audit Trail`
* `Access Login Settings - Gives users access to Login Settings in Admin for Security, IP Restrictions, and Smart List Report settings`
* `Access Marketo Custom Activity - Gives users access to Marketo Custom Activities in Admin`
* `Access Marketo Custom Object - Gives users access to Marketo Custom Objects in Admin`
* `Access Munchkin - GIves users access to Munchkin in Admin, for setting tracking code, person tracking, and enabling API configuration`
* `Access Revenue Cycle Analytics - Gives users access to Revenue Cycle Analytics in Admin, for setting Sync Summary and Attribution`
* `Access Roles` - Gives users access to manage and edit roles, but not users
* `Access Sales Insight - Gives users access to manage Sales Insight in Admin, for setting Status, API Configuration, Person Scoring, and other settings`
* `Access Single Sign-on - Gives users access to manage Single Sign-on in Admin, for enabling SAML and working with SAML settings and Redirect Page URLs`
* `Access Smart Campaign - Gives users access to Smart Campaign in Admin, for restricting limits on qualified people`
* `Access SOAP API - Gives users access to manage SOAP APIs in Web Services in Admin`
* `Access Tags` - Gives users access to all custom tags except the Channel tag
* `Access Treasure Chest - Gives users access to the experimental features in the Treasure Chest in Admin`
* `Access Users` - Gives users access to edit and manage users (but not roles) in Admin
* `Access Webhooks - Gives users to Webhooks in Admin, for setting details and Response Mappings`
* `Access Workspaces and Partitions - Gives users access to create, edit, and delete Workspaces and Partitions in Admin`

#### Access API  {#descriptionsofrolepermissions-accessapi}

Gives users with the **API Only** **Role** access to the individual APIs listed below.

* `Approve Assets`
* `Execute Campaign  
  `
* `R`ead-Only Activity
* Read-Only Activity Metadata
* `R`ead-Only Assets
* `R`ead-Only Campaign
* `R`ead-Only Company
* `R`ead-Only Custom Object
* `R`ead-Only Person
* Read-Only Named Account
* `R`ead-Only Opportunity
* `R`ead-Only Sales Person
* `R`ead-Write Activity
* Read-Write Activity Metadata
* `R`ead-Write Assets
* `R`ead-Write Campaign
* `R`ead-Write Company
* `R`ead-Write Custom Object
* `R`ead-Write Person
* Read-Write Named Account
* `R`ead-Write Opportunity
* `R`ead-Write Sales Person

Access Analytics

Gives users access to the Analytics tabs, Email Insights, reports, and the three items below, unless they are unchecked.

* `Access Revenue Explorer - Unchecking removes user's access to Revenue Explorer`
* `Delete Report - Unchecking removes user's ability to delete reports   
  `
* `Export Analytics Data - Unchecking removes user's ability to export Analytics data`

#### Access Calendar Presentations {#descriptionsofrolepermissions-accesscalendarpresentations}

Gives users access to Calendar presentations ??- enables display of the Presentations button at the bottom?

* `Edit Calendar Presentations` `- Enables users to edit presentations in Calendar`

#### Access Design Studio {#descriptionsofrolepermissions-accessdesignstudio}

Gives users access to the Design Studio tab and view of the tree, but not to details.

* `Access Email`

    * Edit Email - Gives users permission to edit, create, and clone emails

        * Make Email Operational - Gives users permission to make an email operational. See: [Make an Email Operational](../../../../../welcome-to-marketo-docs/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md)

    * `Approve Email - Enables users to approve emails.`
    * `Delete Email - Enables users to delete emails.`
    * Set Branded Domain - Enables users to work with branding domains. See: [Add Multiple Branding Domains](../../../../../welcome-to-marketo-docs/product-docs/administration/email-setup/add-multiple-branding-domains.md)

* Access Email Template

    * `Approve Email Template`
    * `Delete Email Template`
    * `Edit Email Template` - Edit, create, and clone email templates

* Access Form

    * `Delete Form`
    * `Edit Form` - Edit, create, and clone forms

* Access Image

    * `Delete Image`
    * `Upload Image`

* Access Landing Page

    * `Approve Landing Page`
    * `Delete Landing Page`
    * `Edit Landing Page` - Edit, create, and clone landing pages

* Access Landing Page Template

    * `Approve Landing Page Template`
    * `Delete Landing Page Template`
    * `Edit Landing Page Template` - Edit, create, and clone landing page templates

* Access Snippet

    * Approve Snippet
    * Delete Snippet
    * Edit Snippet

* Access Social App

    * Approve Social App
    * Delete Social App
    * Edit Social App

#### Access Database {#descriptionsofrolepermissions-accessdatabase}

View the database as well as view and edit smart/static lists.

* Access Segmentation

    * Approve Segmentation
    * Delete Segmentation
    * Edit Segmentation

* Advanced List Import
* `Delete Person`
* `Delete List`
* `Edit Person` - Prevents manual editing and running single flow steps; you can still edit people by running campaigns against them
* `Export Person` - Export spreadsheets with from your database lists
* Import Custom Object
* Import List
* `Merge People`
* `Run Single Flow Actions` - Enables users to run **Change Data Value** flow step on people from the database `  
  `

* `View Opportunity Data` - Hides the opportunity info on the person detail page

#### Access Marketing Activities {#descriptionsofrolepermissions-accessmarketingactivities}

View the Marketing Activities tab, campaigns, and campaign folders.

* `Access SMS Message`

    * `Approve SMS Message`
    * `Delete SMS Message`
    * `Edit SMS Message`

* `Access Push Notification`

    * `Approve Push Notification`
    * `Delete Push Notification`
    * `Edit Push Notification  
      `

* Access Awards
* Activate Trigger Campaign
* Approve Email Program
* `Clone Marketing Asset`
* `Delete Marketing Asset`
* `Edit Campaign Restrictions`
* `Edit Marketing Asset`
* `Import Program`
* `List Import  
  `
* `Schedule Batch Campaign`

Access SEO

* `Administer SEO`
* `Standard SEO`

#### Targeting and Personalization  
{#descriptionsofrolepermissions-targetingandpersonalization}

* `Administer Web Personalization`
* `CRE Campaign Editor`
* `CRE Campaign Launcher`
* `Web Campaign Editor`
* `Web Campaign Launcher  
  `

Workspace Administration

* Admin access for a specific Workspace (only if you have Workspaces enabled)
* `Move assets between Workspaces`(only if you have Workspaces enabled)

Access Mobile Application
