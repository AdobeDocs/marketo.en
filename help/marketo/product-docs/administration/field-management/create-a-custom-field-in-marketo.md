---
unique-page-id: 2360287
description: Create a Custom Field in Marketo - Marketo Docs - Product Documentation
title: Create a Custom Field in Marketo
exl-id: 6face1d7-6a4e-412b-9708-6aa7e43e8c11
feature: Field Management
---
# Create a Custom Field in Marketo {#create-a-custom-field-in-marketo}

If you need a new custom field in Marketo Engage to store/capture data, here's how to create one.

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/create-a-custom-field-in-marketo-1.png)

1. Click **[!UICONTROL Field Management]**.

   ![](assets/create-a-custom-field-in-marketo-2.png)

    >[!TIP]
    >
    >If you want the fields to be kept in sync with your CRM, create them in the CRM and they will automatically be created in Marketo.

1. Click **[!UICONTROL New Custom Field]**.

    ![](assets/create-a-custom-field-in-marketo-3.png)

1. Choose the _[!UICONTROL Object]_.

    ![](assets/create-a-custom-field-in-marketo-4.png)

   >[!NOTE]
   >
   >While you are not able to select the _Company_ object yourself, you can request it by contacting [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

1. Choose the field _[!UICONTROL Type]_. This will change how it's rendered in Smart Lists and forms in Marketo.

   >[!TIP]
   >
   >Check out the [Custom Field Types Glossary](/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md){target="_blank"}.

    ![](assets/create-a-custom-field-in-marketo-5.png)

1. Enter the _[!UICONTROL Name]_ as you want it to appear in Marketo (the _[!UICONTROL API Name]_ is automatically generated). Choose carefully, as it cannot be renamed after saving. Click **[!UICONTROL Create]** when done.

>[!CAUTION]
>
>Field names cannot start with the following characters: **. & + []**

![](assets/create-a-custom-field-in-marketo-6.png)

>[!NOTE]
>
>The API name is used by the SOAP API and other backend processes.

You can now use this custom field in forms, flow steps, and Smart Lists!
