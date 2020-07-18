---
unique-page-id: 14352475
description: Install Sales Connect Event Fields on Activity History - Marketo Docs - Product Documentation
title: Install Sales Connect Event Fields on Activity History
---

# Install Sales Connect Event Fields on Activity History {#install-sales-connect-event-fields-on-activity-history}

Install Sales Connect Event Fields on Activity History - Marketo Docs - Product Documentation

Once you have installed the Enterprise package into Salesforce you can install Sales Connect event fields into your activity history section. Sales Connect event fields include information such as views, clicks, and campaigns. This allows you to have information about your emails directly imported into Salesforce.

Make sure you team up with your Salesforce Admin when performing these steps. In this example we will install the fields onto the **Leads Page Layout**. You can also install the fields onto the Contact, Account, and Opportunity Page Layouts. Remember, when logging emails to Accounts and Opportunities you will need the contact you are emailing associated as a contact role.

1. Click **Setup**.
1. Click **Customize**.
1. Click **Leads**.
1. Click **Page Layouts**.
1. Click **Edit** next to the page layout you would like to change.

   >[!NOTE]
   >
   >Sales Connect will install some page layouts for you, but if you already have a default one your team is using you will want to install it there. You can delete the Sales Connect page layouts if you do not want to use them.

1. Scroll Down to the Activity History section.
1. Click the wrench to edit.
1. Select the Sales Connect fields you want to include on the Activity History section. If you are not seeing Sales Connect fields here, you may have installed the wrong Salesforce package.
1. Click **Add** to move the desired fields over.
1. Click **OK**.
1. Click **Save**.

   Your users can now see valuable information and updates about their emails in Salesforce!

