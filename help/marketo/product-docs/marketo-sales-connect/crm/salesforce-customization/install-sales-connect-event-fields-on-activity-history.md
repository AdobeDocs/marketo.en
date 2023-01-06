---
unique-page-id: 14352475
description: Install Sales Connect Event Fields on Activity History - Marketo Docs - Product Documentation
title: Install Sales Connect Event Fields on Activity History
exl-id: c1bdb5a6-04f0-4579-84b6-33f4a301128f
---
# Install Sales Connect Event Fields on Activity History {#install-sales-connect-event-fields-on-activity-history}

Once you have installed the Enterprise package into [!DNL Salesforce] you can install [!UICONTROL Sales Connect] event fields into your activity history section. [!UICONTROL Sales Connect] event fields include information such as views, clicks, and campaigns. This allows you to have information about your emails directly imported into [!DNL Salesforce].

Make sure you team up with your [!DNL Salesforce] Admin when performing these steps. In this example we will install the fields onto the **Leads Page Layout**. You can also install the fields onto the Contact, Account, and Opportunity Page Layouts. Remember, when logging emails to Accounts and Opportunities you will need the contact you are emailing associated as a contact role.

1. Click **[!UICONTROL Setup]**.
1. Click **[!UICONTROL Customize]**.
1. Click **[!UICONTROL Leads]**.
1. Click **[!UICONTROL Page Layouts]**.
1. Click **[!UICONTROL Edit]** next to the page layout you would like to change.

   >[!NOTE]
   >
   >[!DNL Sales Connect] will install some page layouts for you, but if you already have a default one your team is using you will want to install it there. You can delete the [!DNL Sales Connect] page layouts if you do not want to use them.

1. Scroll Down to the [!UICONTROL Activity History] section.
1. Click the wrench to edit.
1. Select the [!UICONTROL Sales Connect] fields you want to include on the [!UICONTROL Activity History] section. If you are not seeing [!UICONTROL Sales Connect] fields here, you may have installed the wrong [!UICONTROL Salesforce] package.
1. Click ** [!UICONTROL Add]** to move the desired fields over.
1. Click ** [!UICONTROL OK]**.
1. Click ** [!UICONTROL Save]**.

   Your users can now see valuable information and updates about their emails in [!DNL Salesforce]!
