---
unique-page-id: 42762519
description: Configuration for Existing Customers - Marketo Docs - Product Documentation
title: Configuration for Existing Customers
exl-id: e365f6b5-a3ec-492e-9348-2d3226e6c7eb
---
# Configuration for Existing Customers {#configuration-for-existing-customers}

Please set up the following configuration in order to begin using the new Insights Dashboard.

>[!PREREQUISITES]
>
>Please make sure you have upgraded your Salesforce package to the latest version

## Configure Sales Insight in Marketo {#configure-sales-insight-in-marketo}

1. Open a new tab in your browser to get the Marketo Sales Insights credentials from your Marketo account.

1. Go to the **Admin** area.

   ![](assets/configuration-for-existing-customers-1.png)

1. Click **Sales Insight**.

   ![](assets/configuration-for-existing-customers-2.png)

1. Click **View** to populate Rest API credentials.

   ![](assets/configuration-for-existing-customers-3.png)

1. You'll see a confirmation pop-up. Click **OK**.

## Configure Sales Insight in Salesforce {#configure-sales-insight-in-salesforce}

1. In Salesforce, click **Setup**.

   ![](assets/configuration-for-existing-customers-4.png)

1. Search for and select **Remote Site Settings**.

   ![](assets/configuration-for-existing-customers-5.png)

1. Click **New Remote Site**.

   ![](assets/configuration-for-existing-customers-6.png)

1. Enter the Remote Site Name (it can be something like “MarketoRestAPI”), and the Remote Site URL (your API URL from Rest API Configuration panel in Marketo).

   ![](assets/configuration-for-existing-customers-7.png)

1. Click **Save**.

   ![](assets/configuration-for-existing-customers-8.png)

   You have now created remote site setting for Rest API.

## Access Marketo Sales Insight {#access-marketo-sales-insight}

1. Copy the credentials from the Rest API panel in Marketo’s Sales Insight Admin page. Paste them in the Rest API section in Salesforce’s Sales Insight Configuration page.

1. Enter the API Secret Key.

   ![](assets/configuration-for-existing-customers-9.png)
