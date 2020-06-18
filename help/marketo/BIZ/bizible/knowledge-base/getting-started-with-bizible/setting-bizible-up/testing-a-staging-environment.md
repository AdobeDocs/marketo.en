---
unique-page-id: 18874765
description: Testing a Staging Environment - Bizible - Product Documentation
title: Testing a Staging Environment
---

# Testing a Staging Environment {#testing-a-staging-environment}

Testing a Staging Environment - Bizible - Product Documentation

#### Testing a Sandbox Environment {#testingastagingenvironment-testingasandboxenvironment}

One of Bizible’s core functionalities is its ability to track your digital marketing efforts through actions on your site and then pushing that data to your production Salesforce org through Leads and Contacts. However, typically there are not inbound Leads created from your website within the Sandbox environment so the focus on data will be from a purely offline standpoint.

Here are the two sources referenced for both phases of the testing.&nbsp; [Steps 1-4](http://help.salesforce.com/apex/HTViewHelpDoc?id=lead_import_wizard.htm&language=en_US)&nbsp;and&nbsp; [Steps 5-6](http://docs.marketo.com/x/6AAgAQ). I would encourage you to also review these documents as they provide more detail in some areas.

1. You'll need to create some leads in a CSV so that you can upload them to the Campaign. The quickest way to do this is to export some Leads through a report in your production Salesforce. Otherwise, you can manually create Leads in an Excel file and then save it as a CSV for import. You only need about 20 records. The report needs to have the following columns:

    1. Email
    1. Company
    1. Last Name
    1. First Name (optional but recommended)

1. Log-in to your Sandbox environment.
1. You'll first create a test campaign. We recommend using a campaign type such as Event or Newsletter.
1. Once the campaign is created, you'll upload Leads as Campaign Members by selecting **Manage Members** > **Add Members** > **Import Files**.
1. After that is complete, back on the Campaign page layout, you will “Enable Bizible Touchpoints” which is a picklist field. Choose the value: **Include All Campaign Members**.

Once this is done, it will kick-off a sync between Bizible and Salesforce and apply touchpoints to the Lead records. It’s recommended to check back the next day through a report called: “Bizible Touchpoint on Leads” found in the Bizible Touchpoints Reports folder within the Reports tab. If the report is populating a touchpoint for each Lead, this is a sign of success.

If at any point you have questions, we can walk through the process over a call or you can reach out to  [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#8cfff9fcfce3fef8cceee5f6e5eee0e9a2efe3e1)&nbsp;for help.
