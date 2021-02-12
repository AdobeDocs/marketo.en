---
unique-page-id: 37356893
description: MSI Feature Overview - Marketo Docs - Product Documentation
title: MSI Feature Overview
---

# MSI Feature Overview {#msi-feature-overview}

MSI has the following features available in Salesforce Lightning and Classic.

## Visualforce Panel {#visualforce-panel}

MSI Visualforce Panel includes the following functionalities:

* Tabs

    * [Insights Dashboard](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/insights-dashboard-feature-overview.md)
    * Interesting Moment
    * Web Activity
    * Email
    * Score

* Actions

    * Add to Marketo Campaign
    * Send Marketo Email
    * Add/Remove from Watch List

* Stars & Flames

## Lead Layout {#lead-layout}

Visualforce pages:

* Lead - Includes the option to click on hyper “Go to Full List”, you will be sent to a new tab in Salesforce where the MSI panel will be visible in a full page layout
* Lead Full List - Does not include “Go to Full List” option
* Lead Mobile - Visible in Salesforce mobile application
* Lead Contact Bridge - Displays MSI panel of the contact you have added in the MSI Contact ID field

Fields:

* Last Interesting Moment
* Last Interesting Moment Date
* Last Interesting Moment Desc
* Last Interesting Moment Source
* Last Interesting Moment Type
* Last Marketo Activity by Sales
* Last Marketo Engagement by Sales
* Relative Score
* Relative Score Value
* Urgency
* Urgency Value
* View in Marketo - Click on this field to open a non-editable view of the lead in Marketo. Includes: Lead Info, Company Info, SFDC Lead Info, SFDC Custom Fields, Activity Log
* MSI Contact Id - Add a Salesforce contact to this field and include “Lead Contact Bridge” panel in the lead layout to see the MSI panel of the contact

## Contact Layout {#contact-layout}

Visualforce pages:

* Contact - Includes option to click on hyper “Go to Full List,” you will be sent to a new tab in Salesforce where the MSI panel will be visible in a full page layout
* Contact Full List - Does not include “Go to Full List” option
* Contact Mobile - Visible in Salesforce mobile application
* Add to Marketo Campaign ContactPage - Add to Marketo Campaign feature is available within this panel

Fields:

* Last Interesting Moment
* Last Interesting Moment Date
* Last Interesting Moment Desc
* Last Interesting Moment Source
* Last Interesting Moment Type
* Last Marketo Activity by Sales
* Relative Score
* Relative Score Value
* Urgency
* Urgency Value
* View in Marketo - Click on this field to open a non-editable view of the lead in Marketo. Includes: Lead Info, Company Info, SFDC Lead Info, SFDC Custom Fields, Activity Log
* Mkto Lead Score
* Sales Insight - Opens contact full list page

## Account Layout {#account-layout}

Visualforce pages:

* Account - Includes option to click on hyper “Go to Full List”, you will be sent to a new tab in Salesforce where the MSI panel will be visible in a full page layout
* Account Full List - Does not include “Go to Full List” option
* Account Mobile - Visible in Salesforce mobile application

Fields:

* Sales Insight - Opens contact full list page

The following features are **not available** in the Account Layout page:

* Actions: Add to Marketo Campaign, Send Marketo Email, Add/Remove from Watch List
* Stars & Flames

## Opportunity Layout {#opportunity-layout}

Visualforce pages:

* Opportunity - Includes option to click on hyper “Go to Full List,” you will be sent to a new tab in Salesforce where the MSI panel will be visible in a full page layout
* Opportunity Full List - Does not include “Go to Full List” option
* Opportunity Mobile - Visible in Salesforce mobile application

Fields:

* Sales Insight - Opens contact full list page
* Marketo Opportunity Analysis – Opens Opportunity Influence Analyzer in Marketo

The following features are **not available** in the Opportunity Layout page:

* Actions: Add to Marketo Campaign, Send Marketo Email, Add/Remove from Watch List
* Stars & Flames

## Lead and Contact List view (Bulk Actions) {#lead-and-contact-list-view-bulk-actions}

Salesforce Lightning: Add to Watchlist, Add to Marketo Campaign and Send Marketo Email bulk action buttons in Lead and Contact list view.

Salesforce Classic: Add to Watchlist, Add to Marketo Campaign, and Send Marketo Email bulk action buttons in Lead and Contact list view.

## Marketo Tab {#marketo-tab}

* Best Bets

    * Includes ability to create and edit views. Ability to Hide Best Bets depending on configuration of “Default Hide” option in Marketo Configuration page
    * Columns - Name, Account, Last Interesting Moment, Status Header, Engagement (Stars & Flames), Hide

* My Watch List

    * Includes ability to create and edit views
    * Columns - Name, Account, Last Interesting Moment, Status Header, Engagement (Stars & Flames), Remove

* Web Activity

    * Includes ability to create and edit views, time frame filter functionality
    * Column - Page view, Name, Account, Last Visit

* Anonymous Web Activity

    * Includes ability to create and edit views, time frame filter functionality
    * Columns - Page View, Company, Last Visit, Research (opens LinkedIn page of the company)

* My Email

    * Includes ability to create and edit views
    * Columns - Name, Account, Subject, Date, Open, Click

* Lead feed - Includes ability to subscribe to interesting moments, RSS feed on Configuration page must be enabled to use this feature

    * Lead/Contact who had this interesting moment
    * Interesting Moment type (web, email, or milestone) and description
    * Account Name
    * Time this interesting moment occurred
    * Subscribe option to receive email notification for this type of event
    * High priority icon to show this person is a Best Bet

## Marketo Sales Insight Configuration Tab {#marketo-sales-insight-configuration-tab}

* Operational Settings: Includes Soap & Rest API credentials needed to set up MSI in SFDC
* MSI Configuration: Includes configuration of Marketo tab and MSI visualforce panel
* Reset Marketo Sales Insight: Includes ability to wipe out all configurations

>[!MORELIKETHIS]
>
>[Marketo Sales Insight Configuration tab in Salesforce](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.md)

## Sales Insight Performance Reports {#sales-insight-performance-reports}

View the performance of emails sent through Salesforce, Microsoft Dynamics, or a Gmail or Outlook plug-in

## MSI for Mobile {#msi-for-mobile}

MSI features are supported in Salesforce mobile application

## Language Support {#language-support}

Marketo Sales Insight is stored by language. So, if you want it to work for more than one language, you have to enter the credentials separately for each language.
