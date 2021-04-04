---
unique-page-id: 2360287
description: Create a Custom Field in Marketo - Marketo Docs - Product Documentation
title: Create a Custom Field in Marketo
exl-id: 6face1d7-6a4e-412b-9708-6aa7e43e8c11
---
# Create a Custom Field in Marketo {#create-a-custom-field-in-marketo}

If you need a new custom field in Marketo to store/capture data, here's how to create one.

1. Go to Admin and click **Field Management**.

    ![](assets/image2014-9-24-13-3a46-3a26.png)

    >[!TIP]
    >
    >If you want the fields to be kept in sync with your CRM, create them in the CRM and they will automatically be created in Marketo.

1. Click **New Custom Field**.

    ![](assets/two.png)

1. Choose the field Type. This will change how it's rendered in smart lists and forms in Marketo.

    >[!TIP]
    >
    >Check out the [Custom Field Types Glossary](/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md).

    ![](assets/image2014-9-24-13-3a47-3a42.png)

1. Enter the Name as you want it to appear in Marketo. The API Name is automatically generated. You can tweak it, but it cannot be renamed once set. Click **Create** when done.

>[!CAUTION]
>
>Field names cannot start with the following characters: **. & + []**

![](assets/image2014-9-24-13-3a48-3a26.png)

>[!NOTE]
>
>The API name is used by the SOAP API and other backend processes.

You can now use this custom field in forms, flow steps and smart lists!
