---
unique-page-id: 10093688
description: Add Marketo Custom Object Fields - Marketo Docs - Product Documentation
title: Add Marketo Custom Object Fields
---

# Add Marketo Custom Object Fields {#add-marketo-custom-object-fields}

After you've created a custom object, you need to add fields to it to meet your business needs.

Fields define the specific information used by a custom object. Link fields have a special job, to connect custom objects, and are covered in a [separate article](add-marketo-custom-object-link-fields.md).

1. Click **Admin**, and in **Database Management**, select **Marketo Custom Objects**.

   ![](assets/image2016-1-18-9-3a2-3a6.png)

1. Select the object you want to add the field to on the right.

   ![](assets/image2016-1-18-9-3a5-3a3.png)

1. In the **Fields **tab, click **New Field**.

   ![](assets/image2015-9-15-16-3a53-3a40.png)

   >[!NOTE]
   >
   >The three fields shown above are created automatically by Marketo when you create a custom object. Marketo manages these fields automatically and you can't edit or delete them.

1. Enter a display name and description.

   ![](assets/image2015-10-5-11-3a35-3a48.png)

   >[!NOTE]
   >
   >The API name can be edited only until it's approved.

1. Now, choose an appropriate data type from the list.

   ![](assets/image2015-10-5-11-3a37-3a24.png)

1. Pull the Dedupe slider over if you want to use the new field as a unique identifier. Click **Save **to finish.

   ![](assets/image2015-10-5-11-3a40-3a12.png)

   >[!TIP]
   >
   >When you create a dedupe field, you can use it to remove duplicate fields in your database.

1. Add any other fields you need.

   >[!NOTE]
   >
   >**Reminder**
   >
   >
   >If you're building a one-to-many structure, you need to add a Link field to your custom object. For a many-to-many structure, you don't need a link field in the custom object, but you must add two link fields in the intermediary object. See [Add Marketo Custom Object Link Fields](add-marketo-custom-object-link-fields.md) to create the link fields, and [Understanding Marketo Custom Objects](understanding-marketo-custom-objects.md) for more information about types of custom objects.

>[!MORELIKETHIS]
>
>* [Add Marketo Custom Object Link Fields](add-marketo-custom-object-link-fields.md)
>* [Edit and Delete a Marketo Custom Object](edit-and-delete-a-marketo-custom-object.md)
>* [Understanding Marketo Custom Objects](understanding-marketo-custom-objects.md)
>* [Edit and Delete Marketo Custom Object Fields](edit-and-delete-marketo-custom-object-fields.md)
>

