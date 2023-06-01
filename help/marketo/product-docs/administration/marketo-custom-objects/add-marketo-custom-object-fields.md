---
unique-page-id: 10093688
description: Add Marketo Custom Object Fields - Marketo Docs - Product Documentation
title: Add Marketo Custom Object Fields
exl-id: 6d776d97-93e2-4708-9ce5-2172e02b71c3
---
# Add Marketo Custom Object Fields {#add-marketo-custom-object-fields}

After you've created a custom object, you need to add fields to it to meet your business needs.

Fields define the specific information used by a custom object. Link fields have a special job, to connect custom objects, and are covered in a [separate article](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md).

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/add-marketo-custom-object-fields-1.png)

1. Click **[!UICONTROL Marketo Custom Objects]**.

   ![](assets/add-marketo-custom-object-fields-2.png)

1. Select the object you want to add the field to on the right.

   ![](assets/add-marketo-custom-object-fields-3.png)

1. Ckick the **[!UICONTROL Fields]** tab, then **[!UICONTROL New Field]**.

   ![](assets/add-marketo-custom-object-fields-4.png)

   >[!NOTE]
   >
   >The three fields shown above are created automatically by Marketo when you create a custom object. Marketo manages these fields automatically and you can't edit or delete them.

1. Enter a [!UICONTROL Display Name] and (optional) [!UICONTROL Description].

   ![](assets/add-marketo-custom-object-fields-5.png)

   >[!NOTE]
   >
   >The API name can be edited only until it's approved.

1. Now, choose an appropriate [!UICONTROL Data Type] from the list.

   ![](assets/add-marketo-custom-object-fields-6.png)

1. Pull the [!UICONTROL Dedupe] slider over if you want to use the new field as a unique identifier. Click **[!UICONTROL Save]** to finish.

   ![](assets/add-marketo-custom-object-fields-7.png)

   >[!TIP]
   >
   >Dedupe fields can be used to retrieve, update, or delete custom objects. Every custom object definition must contain at least one (and no more than three) dedupe fields.

1. Add any other fields you need.

   >[!NOTE]
   >
   >If you're building a one-to-many structure, you need to add a Link field to your custom object. For a many-to-many structure, you don't need a link field in the custom object, but you must add two link fields in the intermediary object. See [Add Marketo Custom Object Link Fields](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md) to create the link fields, and [Understanding Marketo Custom Objects](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) for more information about types of custom objects.

>[!MORELIKETHIS]
>
>* [Add Marketo Custom Object Link Fields](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md)
>* [Edit and Delete a Marketo Custom Object](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-a-marketo-custom-object.md)
>* [Edit and Delete Marketo Custom Object Fields](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-marketo-custom-object-fields.md)
>* [Understanding Marketo Custom Objects](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
