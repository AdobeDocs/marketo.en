---
description: Salesforce Sync Errors - Marketo Docs - Product Documentation
title: Salesforce Sync Errors
exl-id: 4819f423-30c6-48e3-8cec-5d298ceb7b56
---
# Salesforce Sync Errors {#salesforce-sync-errors}

View a summary of the errors faced during the sync process. This includes errors caused by failures to sync incompatible data.

>[!NOTE]
>
>**Admin Permissions Required**

## View Sync Errors {#view-sync-errors}

1. Click **Admin**.

   ![](assets/salesforce-sync-errors-1.png)

1. Under Integration, click **Salesforce**, then the **Sync Errors** tab.

   ![](assets/salesforce-sync-errors-2.png)

>[!NOTE]
>
>Errors listed range from the current time to five days prior to the current sync.

| Field | Description |
|---|---|
| Failed On | Record Level _or_ Job Level |
| Date/Time of the failure | Error Details |
| Error Type | SFDC Return message |

>[!TIP]
>
>Clicking on the record level record shows the Marketo and Salesforce IDs of the related object. In some cases, the message on the record and job level errors are directly from Salesforce. Searching for them online may provide additional details.

## Filter Sync Errors {#filter-sync-errors}

1. To filter the data, click the filter icon to the far right of the page.

   ![](assets/salesforce-sync-errors-3.png)

1. Select your date and time range, then filter by Error Type (Job Level or Record Level). Click **Apply** when done.

   ![](assets/salesforce-sync-errors-4.png)

**OPTIONAL STEP**: To export sync errors, click **Export**. The data will be exported as a CSV.

   ![](assets/salesforce-sync-errors-5.png)
