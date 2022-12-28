---
unique-page-id: 10097613
description: Add Marketo Custom Object Link Fields - Marketo Docs - Product Documentation
title: Add Marketo Custom Object Link Fields
exl-id: e7537d79-9fca-4966-881a-9d7d312008e2
---
# Add Marketo Custom Object Link Fields {#add-marketo-custom-object-link-fields}

When you create custom objects, you must provide link fields to connect the custom object record to the correct parent record.

* For a one-to-many custom structure, use the link field in the custom object to connect it to a person or a company.
* For a many-to-many structure, you use two link fields, connected from a separately created intermediary object (which is a type of custom object, too). One link connects to people or companies in your database and the other connects to the custom object. In this case, the link field is not located in the custom object itself.

## Create a Link Field for a One-to-Many Structure {#create-a-link-field-for-a-one-to-many-structure}

Here's how to create a link field in a custom object for a one-to-many structure.

1. Click **[!UICONTROL Admin]**, and in **[!UICONTROL Database Management]**, select **[!UICONTROL Marketo Custom Objects]**.

   ![](assets/image2016-1-18-13-3a25-3a11.png)

1. Select the custom object in the list.

   ![](assets/image2016-1-14-15-3a6-3a2.png)

1. In the **[!UICONTROL Fields]** tab, click **[!UICONTROL New Field]**.

   ![](assets/image2015-9-17-14-3a9-3a19.png)

1. Name the link field and add an optional [!UICONTROL Description]. Be sure to select the **[!UICONTROL Link]** **[!UICONTROL Data Type]**.

   ![](assets/image2015-10-5-13-3a24-3a57.png)

   >[!CAUTION]
   >
   >You won't be able to go back and create, edit, or delete a [!UICONTROL Link] or [!UICONTROL Dedupe Field] once the custom object is approved.

1. Select whether the **[!UICONTROL Link Object]** is for a **[!UICONTROL Lead]** (person) or a **[!UICONTROL Company]**.

   ![](assets/image2015-10-5-13-3a28-3a1.png)

   >[!NOTE]
   >
   >If you choose [!UICONTROL Lead], you'll see Id, email Address, and any custom fields in the list.
   >
   >If you choose [!UICONTROL Company], you'll see Id and any custom fields in the list.

1. Select the **[!UICONTROL Link Field]** you want to connect to as the parent of the new field.

   ![](assets/image2015-10-5-13-3a30-3a6.png)

   >[!NOTE]
   >
   >Only string field types are supported in the [!UICONTROL Link Field].

1. Click **[!UICONTROL Save].**

   ![](assets/image2015-10-5-13-3a34-3a0.png)

## Create a Link Field for a Many-to-Many Structure {#create-a-link-field-for-a-many-to-many-structure}

Here's how to create a link field in an intermediary object for use in a many-to-many structure.

>[!PREREQUISITES]
>
>You must have already created the intermediary object and any custom objects you intend to link it to.

1. Click **[!UICONTROL Admin]**, and in **[!UICONTROL Database Management]**, select **[!UICONTROL Marketo Custom Objects]**.

   ![](assets/image2016-1-18-9-3a8-3a14.png)

1. Select the intermediary object you want to add the field to.

   ![](assets/image2016-1-18-9-3a10-3a29.png)

1. In the **[!UICONTROL Fields]** tab, click **[!UICONTROL New Field]**.

   ![](assets/image2016-1-18-9-3a31-3a43.png)

1. You need to create two link fields. Create them one at a time. First, name the field for the members of your database list (leadID, for example). Add an optional [!UICONTROL Description]. Be sure to select the **[!UICONTROL Link]** **[!UICONTROL Data Type]**.

   ![](assets/image2016-1-18-9-3a38-3a59.png)

   >[!CAUTION]
   >
   >You won't be able to go back and create, edit, or delete a [!UICONTROL Link] or [!UICONTROL Dedupe Field] once the custom object is approved.

1. Select the **[!UICONTROL Link Object]** from your database, in this case **[!UICONTROL Lead]**.

   ![](assets/image2016-1-18-9-3a50-3a48.png)

1. Select the **[!UICONTROL Link Field]** you want to connect to, in this case, **[!UICONTROL Id]**.

   ![](assets/image2016-1-18-9-3a53-3a54.png)

   >[!NOTE]
   >
   >Only string field types are supported in the [!UICONTROL Link Field].

1. Click **[!UICONTROL Save[!UICONTROL .**

   ![](assets/image2016-1-18-9-3a55-3a18.png)

1. Repeat this process for the second link to your custom object, in this example, courseID. The **[!UICONTROL Link Object]** Name will be course, and the **[!UICONTROL Link Field]** will be courseID. Since you already created and approved the course custom object, these selections are available in the drop-down menus.

   ![](assets/image2016-1-18-9-3a57-3a46.png)

1. Create any other fields that you want to use in your intermediary object, such as enrollmentID or grade.

## Using Custom Objects {#using-custom-objects}

   The next step is to use these custom objects in filters in your smart campaigns. With a many-to-many relationship, you can select multiple people/companies and multiple custom objects. In the example below, anyone in your database who matches these criteria will be listed. The coursename field comes from the course custom object and the enrollment grade comes from the intermediate object.

   ![](assets/image2016-1-14-15-3a57-3a59.png)

>[!MORELIKETHIS]
>
>* [Add Marketo Custom Object Fields](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [Edit and Delete a Marketo Custom Object](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-a-marketo-custom-object.md)
>* [Understanding Marketo Custom Objects](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
>* [Edit and Delete Marketo Custom Object Fields](/help/marketo/product-docs/administration/marketo-custom-objects/edit-and-delete-marketo-custom-object-fields.md)
