---
unique-page-id: 10099680
description: Import Custom Object Data - Marketo Docs - Product Documentation
title: Import Custom Object Data
exl-id: ee11199a-57ca-47ec-8f59-8384a93ea05e
feature: Custom Objects
---
# Import Custom Object Data {#import-custom-object-data}

It's easy to import custom object data into your database. If you're using custom objects with companies, see [Using Custom Objects with Companies](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md#using-custom-objects-with-companies) for more information.

1. In My Marketo, go to **Database**.

   ![](assets/import-custom-object-data-1.png)

1. Click **New** and select **Import Custom Object Data**.

   ![](assets/import-custom-object-data-2.png)

1. Click **Browse** to locate the data file. Select the file format (Comma Separated Values in this example).

   ![](assets/import-custom-object-data-3.png)

1. Select your custom object.

   ![](assets/import-custom-object-data-4.png)

1. Select the Dedupe Mode from the drop-down. Click **Next**.

   ![](assets/import-custom-object-data-5.png)

   >[!NOTE]
   >
   >Use Dedupe field(s) as unique identifiers when you create or update custom object records. This example uses the Dedupe field of the **car** custom object - vin (vehicle ID number). If you are only updating custom object records, you can select the Marketo Guid as the Dedupe Mode.

1. Map each column to a Marketo field, selecting it from the drop-down.

   ![](assets/import-custom-object-data-6.png)

   >[!NOTE]
   >
   >Make sure the values in your file match the type of field you're matching them to (e.g., text, integer, etc.), otherwise the file will be rejected.

1. Click **Next**.

   ![](assets/import-custom-object-data-7.png)

1. Click **Import**.

   ![](assets/import-custom-object-data-8.png)

   >[!NOTE]
   >
   >The size limit for custom objects is 100MB.

   >[!TIP]
   >
   >Enter your email address in the **Send Alert To:** field and Marketo will email you when your import is done!

1. In the upper right corner of your screen, you'll see a notification while the import is running, and the final results when it completes.

   ![](assets/import-custom-object-data-9.png)

   Yay!

>[!MORELIKETHIS]
>
>[Understanding Marketo Custom Objects](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
