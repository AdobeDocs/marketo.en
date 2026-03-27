---
description: Description goes here.
title: Picklist Management
hide: yes
hidefromtoc: yes
feature: Field Management
exl-id: 2b75edbb-0ce3-495b-a245-dac2db9c0126
---
# Picklist Management {#picklist-management}

Picklist management allows you to define a fixed set of values for a field to simplify data and workflow management within Marketo Engage. Only non-text fields not mapped to a CRM field with a defined picklist may be managed in Marketo. If a field is mapped to a CRM field that has a defined picklist, the values for that field must be defined in the CRM.

You can see the status of a picklist from its Field Management page. A field may have one of the following picklist statuses:

* **Managed**: A user has defined the set of values that can be autosuggested for this field. Only values defined in field management are autosuggested. If a managed picklist is deleted, the picklist status reverts to the initial value for the field, either Unmanaged or Seeded.

* **Unmanaged**: The possible values for this field are not defined. Values are autosuggested based on those that exist in those fields in the database.

* **Seeded**: The field has a system-defined list of values that are suggested to the user.

* **CRM**: The field has value that is defined by the CRM system, Salesforce.com or Microsoft Dynamics, which is synchronized to the instance.

   ![](assets/picklist-management-1.png)

## Manage Picklist {#manage-picklist}

To modify the values for a field, go to **Admin** > **Field Management** and select the desired field.

Click the _Field Actions_ drop-down and select **Manage Picklist**.

   ![](assets/picklist-management-2.png)

In the _Manage Picklist_ dialog you can add, edit, or delete values. You can also delete the managed picklist to revert the field to its original picklist status, either _Unmanaged_ or _Seeded_.

   ![](assets/picklist-management-3.png)

Each picklist entry has a Display Value and a Submitted Value. The Display Value is what is suggested to the user when building Smart Lists, Smart Campaigns, or forms, while the submitted value is the one that is stored. For example, your Territory Code use case may suggest the full name of a territory (e.g., Alberta), while storing the two-letter code (AB).

## Autosuggest {#autosuggest}

When the _Managed Picklist_ setting is enabled, Filters, Flow Step Choices, and Change Data Value steps will autosuggest values from your managed picklist. When this setting is disabled, only unmanaged values are suggested.

   ![](assets/picklist-management-4.png)

   ![](assets/picklist-management-5.png)

   ![](assets/picklist-management-6.png)

### Switching Between Managed and Unmanaged Picklists {#switching}

Most Marketo Engage subscriptions contain data from before the introduction of Managed Picklists. To use values in smart lists or flow steps from this unmanaged version picklist (e.g., from the full set of values that exist on records in your database), toggle the Managed Picklist setting in your Smart List or Campaign view. When toggled on, only the managed picklist values are shown. When toggled off, the unmanaged picklist is used and values are autosuggested based on existing values in the database.

## Form Picklists (Select Type Fields) {#form-picklists}

Like Seeded and CRM-managed picklists, the values for Managed Picklists propagate into Forms when using the Select field type. For a field with a managed picklist, select that field and set the Field Type to _Select_.

   ![](assets/picklist-management-7.png)

This shows the set of managed picklist values defined for that field.

   ![](assets/picklist-management-8.png)
