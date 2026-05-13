---
unique-page-id: 37355569
description: Learn about program member custom fields. Store and use custom data for each person in a program.
title: Program Member Custom Fields
exl-id: 66b5dac6-015f-4907-8c82-78c932102463
feature: Programs
TQID: https://experienceleague.adobe.com/77kJb3iO-IaaAQwYcAcXvzBCe1Y18qSEeJ9GXd-Fw38
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
    internal-label: Design Studio
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Program Member Custom Fields {#program-member-custom-fields}

Program Member custom fields allow you to collect program-specific data for each member. They can be used in: Marketo forms, Smart List filters and triggers, and Smart Campaign flow actions. The data is viewable in the program's Members tab.

## Create a Program Member Custom Field {#create-a-program-member-custom-field}

1. In Marketo, click **[!UICONTROL Admin]**.

   ![](assets/one.png)

1. Click **[!UICONTROL Field Management]**.

   ![](assets/two.png)

1. Click **[!UICONTROL New Custom Field]**.

   ![](assets/three.png)

1. Click the **[!UICONTROL Object]** drop-down and select the desired object.

   ![](assets/four.png)

   >[!NOTE]
   >
   >[!UICONTROL Person] and [!UICONTROL Program Member] custom fields cannot share the same name.

1. Fill out the remaining fields and click **[!UICONTROL Create]**.

   ![](assets/five.png)

   >[!NOTE]
   >
   >Types supported for [!UICONTROL Program Member] custom fields are: boolean, date, datetime, float, integer, string, URL. [Learn more about field types](/help/marketo/product-docs/administration/field-management/custom-field-type-glossary.md){target="_blank"}.

## Object Descriptions {#object-descriptions}

| Object |Description |
|---|---|
| Company |The name of the company associated with the person. |
| Opportunity |An opportunity can be associated with a person or account as a potential future sale. They usually enter Marketo through a CRM, or via API. |
| Person |An individual in your Marketo database that you are engaging with through marketing campaigns. |
| Program Member |Person who is also a member of a program |

## Triggers and Filters {#triggers-and-filters}

You can leverage this program-specific data in smart lists via [triggers](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md){target="_blank"} and/or [filters](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md){target="_blank"}.

![](assets/six.png)

## Things to Know {#things-to-know}

* Program Member custom fields are available in local assets only. They are not supported in Design Studio because there's no way to tie it to a specific program.
* You cannot clone/move a form (or a landing page with a form) that contains Program Member custom fields to the Design Studio.
* [You can sync](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-field-sync.md){target="_blank"} the Program Member Custom Fields with Campaign Member Custom Fields.
* The Program Member object can have up to 20 custom fields. Those fields are available to any program.
* When you remove a member of a program, if they have any data in their Program Member custom field, the data will be scrubbed from that field.
* To view the data, click the Members tab in the program and create a custom view that includes said field(s).
* Import and export via [list](/help/marketo/getting-started/quick-wins/import-a-list-of-people.md){target="_blank"} and [API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/home){target="_blank"} are supported. Exports work on Program Member lists only, not static lists.
* When you merge two people, the winner's Program Member custom field data will be used. But if the winner has none, the loser's value will be used.
* Change type is not allowed on Program Member Info fields.
* The "contains" Smart List constraint is not supported for Program Member custom fields.

>[!MORELIKETHIS]
>
>* [Create a Custom Field in Marketo](/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md){target="_blank"}
>
>* [Program Member Custom Field Sync](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/program-member-custom-field-sync.md){target="_blank"}
