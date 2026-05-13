---
unique-page-id: 2360287
description: Steps to create a new custom field in Marketo Engage to store and capture data for people or companies.
title: Create a Custom Field in Marketo
exl-id: 6face1d7-6a4e-412b-9708-6aa7e43e8c11
feature: Field Management
TQID: https://experienceleague.adobe.com/xdG07VzIcNYcqCsR3wfXHTGE07nsLYAvbM8QZZJf0oo
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Create a Custom Field in Marketo {#create-a-custom-field-in-marketo}

Learn how to create a custom field in Marketo Engage to store and capture data.

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

1. Choose the field _[!UICONTROL Type]_. This will change how it is rendered in Smart Lists and forms in Marketo.

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

You can now use this custom field in forms, flow steps, and Smart Lists.
