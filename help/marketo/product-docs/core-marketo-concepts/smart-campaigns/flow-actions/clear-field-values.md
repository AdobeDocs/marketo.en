---
unique-page-id: 1147324
description: Learn how to clear field values in a Smart Campaign flow step. Remove values from person or company fields.
title: Clear Field Values
exl-id: cddc7697-4e8f-4a62-865c-efd451abea0c
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/57QZb7T-y2JVdNeP4nhTl9PDjIX1S9GcQmRAMJ-53E0
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
---
# Clear Field Values {#clear-field-values}

[Change Data Value](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md) is great, but how do you _remove_ the value completely? Good question!

1. In the flow step, choose the field you would like to clear and type in **[!UICONTROL NULL]** (all caps) as the **[!UICONTROL New Value]**.

   ![](assets/clear-field-values-1.png)

1. After the flow step finishes, the value of the field you chose is cleared.

   ![](assets/clear-field-values-2.png)

   >[!CAUTION]
   >
   >Leaving the new value blank or entering a SPACE will not truly empty the field. You have to type in NULL. Also, remember, flow steps cannot be undone after running.
