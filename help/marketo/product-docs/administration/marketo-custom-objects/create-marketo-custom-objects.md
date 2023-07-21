---
unique-page-id: 10093192
description: Create Marketo Custom Objects - Marketo Docs - Product Documentation
title: Create Marketo Custom Objects
exl-id: d68b41e1-a12b-436f-aad7-42c7264cd901
feature: Custom Objects
---
# Create Marketo Custom Objects {#create-marketo-custom-objects}

Use custom objects in Marketo to track metrics specific to your business. This could be anything from cars, to courses--whatever you would like to model in Marketo to run your campaigns.

>[!NOTE]
>
>You can set up custom objects to work on a one-to-many or many-to-many basis. You create the initial object the same way, but the steps are different when you start adding fields to the object. See  [Understanding Marketo Custom Objects](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) for more information.

>[!NOTE]
>
>You cannot create, edit, or delete a Link or Dedupe Field once the custom object is approved.

## Create a Custom Object for a One-to-Many Structure {#create-a-custom-object-for-a-one-to-many-structure}

This example shows a Car custom object, for use in a one-to-many structure. Later, you'll create a course custom object and an intermediary object to use in a many-to-many structure.

1. Go to the **Admin** area.

   ![](assets/create-marketo-custom-objects-1.png)

1. Click **Marketo Custom Objects**.

   ![](assets/create-marketo-custom-objects-2.png)

1. Click **New Custom Object**.

   ![](assets/create-marketo-custom-objects-3.png)

   >[!NOTE]
   >
   >The Marketo Custom Objects tab displays all custom objects on the right, and details for any approved ones, including number of records and fields at the most recent update.

1. Enter a display name. The API Name and Plural Name populate automatically. Enter a description (optional).

   ![](assets/create-marketo-custom-objects-4.png)

   >[!NOTE]
   >
   >You can edit these fields when you're creating them, but after they're saved, you can only edit the Plural Name field and the **Show in Lead Detail** slider.

1. Pull the **Show in Lead Detail** slider over to display **Show** if you want to view custom object data on the Database page. Click **Save**.

   ![](assets/create-marketo-custom-objects-5.png)

1. The custom object information displays the content you entered. Notice that it's in a Draft state.

   ![](assets/create-marketo-custom-objects-6.png)

   The next step is to add fields to [build out your custom object](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md).

   >[!NOTE]
   >
   >You can only populate Marketo Custom Objects via a list import, or the [API](https://developers.marketo.com/documentation/rest/).

## Create a Custom Object for a Many-to-Many Structure {#create-a-custom-object-for-a-many-to-many-structure}

This example shows a course custom object, which you'll use for creating a many-to-many relationship between people/companies and courses. When you're done, you'll create an intermediary object to connect it to people or companies in your database.

>[!NOTE]
>
>For a many-to-many relationship, you don't need to create a link in the custom object. Instead, you'll add two links to the intermediary object (see below).

1. Go to the **Admin** area.

   ![](assets/create-marketo-custom-objects-7.png)

1. Click **Marketo Custom Objects**.

   ![](assets/create-marketo-custom-objects-8.png)

1. Click **New Custom Object**.

   ![](assets/create-marketo-custom-objects-9.png)

1. Enter a display name. The API Name and Plural Name populate automatically. Enter a description (optional).

   ![](assets/create-marketo-custom-objects-10.png)

   >[!NOTE]
   >
   >You can edit these fields when you're creating them, but after they're saved, you can only edit the Plural Name field and the **Show in Lead Detail** slider.

1. Pull the **Show in Lead Detail** slider over to display **Show** if you want to view custom object data on the Database page. Click **Save**.

   ![](assets/create-marketo-custom-objects-11.png)

1. The custom object information displays the content you entered. Notice that it's in a Draft state.

   ![](assets/create-marketo-custom-objects-12.png)

   >[!NOTE]
   >
   >You can only populate Marketo Custom Objects via a list import, or the [API](https://developers.marketo.com/documentation/rest/).

The next step is for you create your intermediary object (see below). But before that, you need to create a field to link to with it.

## Create an Intermediary Object {#create-an-intermediary-object}

Use an intermediary object to connect a custom object to people or companies. In this example, it's used to connect courses in your course custom object to people or companies in your database.

>[!NOTE]
>
>You don't need to create an intermediary object for a one-to-many custom object structure.

1. Go to the **Admin** area.

   ![](assets/create-marketo-custom-objects-13.png)

1. Click **Marketo Custom Objects**.

   ![](assets/create-marketo-custom-objects-14.png)

1. Click **New Custom Object**.

   ![](assets/create-marketo-custom-objects-15.png)

1. Enter a display name. The API Name and Plural Name populate automatically. Enter a description (optional).

   ![](assets/create-marketo-custom-objects-16.png)

   >[!NOTE]
   >
   >You can edit these fields when you're creating them, but after they're saved, you can only edit the Plural Name field and the Show in Lead Detail slider.

1. Pull the **Show in Lead Detail** slider over to display **Show** if you want to view custom object data on the Database page. Click **Save**.

   ![](assets/create-marketo-custom-objects-17.png)

1. The custom object information displays the content you entered. Notice that it's in a Draft state.

   The next step is for you to [add link fields](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md) to connect your intermediary object to a person/company and a custom object.

>[!MORELIKETHIS]
>
>* [Add Marketo Custom Object Fields](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-fields.md)
>* [Add Marketo Custom Object Link Fields](/help/marketo/product-docs/administration/marketo-custom-objects/add-marketo-custom-object-link-fields.md)
>* [Understanding Marketo Custom Objects](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md)
