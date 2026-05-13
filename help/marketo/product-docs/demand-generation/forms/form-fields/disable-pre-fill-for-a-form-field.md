---
unique-page-id: 2359675
description: Learn how to disable pre-fill for a form field in Marketo. Stop known visitor data from auto-filling the field.
title: Disable Pre-fill for a Form Field
exl-id: c600e0ce-1b94-4f7b-b75d-f550a2904799
feature: Forms
TQID: https://experienceleague.adobe.com/loH0b6d25kDL0dReI7lU62IFyXGr3p8tygqwTPx-OVk
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
# Disable Pre-fill for a Form Field {#disable-pre-fill-for-a-form-field}

When a web visitor is known (cookied), Marketo forms will pre-fill fields with their information by default. If you want to turn this off, here's how to do it.

>[!NOTE]
>
>**Form Pre-fill** is enabled by default. Landing page level pre-fill settings and admin level pre-fill settings trump the form level setting:
>
>Form > Landing Page > Admin

## How to Disable Pre-fill {#how-to-disable-pre-fill}

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/login-marketing-activities-7.png)

1. Select your form and click **[!UICONTROL Edit Form]**.

   ![](assets/image2014-9-15-14-3a26-3a46.png)

   >[!CAUTION]
   >
   >Form Pre-fill does not work when embedding a form on your own pages. It only works on Marketo landing pages.

1. Select one of the fields and set **[!UICONTROL Form Pre-fill]** to **[!UICONTROL Disabled]**.

   ![](assets/image2014-9-15-14-3a26-3a54.png)

   >[!TIP]
   >
   >You can also disable form pre-fill at the landing page level or at the admin level.

1. Click **[!UICONTROL Finish]**.

   ![](assets/image2014-9-15-14-3a27-3a1.png)

1. Click **[!UICONTROL Approve and Close]**.

   ![](assets/image2014-9-15-14-3a27-3a6.png)

## Sensitive Fields {#sensitive-fields}

When you [mark a field as sensitive](/help/marketo/product-docs/administration/field-management/mark-a-field-as-sensitive.md), preventing its values from being pre-filled in forms, you will see this on the Pre-fill option.

   ![](assets/disable-pre-fill.png)
