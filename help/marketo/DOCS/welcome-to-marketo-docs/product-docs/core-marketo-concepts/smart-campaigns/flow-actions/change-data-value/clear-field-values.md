---
unique-page-id: 1147324
description: Clear Field Values - Marketo Docs - Product Documentation
title: Clear Field Values
---

# Clear Field Values {#clear-field-values}

Clear Field Values - Marketo Docs - Product Documentation

** [Change Data Value](../../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/change-data-value.md)** is great, but how do you *remove* the value completely? Good question!

1. In the flow step, choose the field you would like to clear and type in **NULL **(all caps) as the **New Value**.

   ![](assets/image2015-3-19-10-3a6-3a14.png)

1. Boom! I bet you didn't know that! After the flow step finishes, the value of the field you chose is cleared.

   ![](assets/image2015-3-19-10-3a11-3a9.png)

   >[!CAUTION]
   >
   >Leaving the new value blank or simply entering a SPACE will not truly empty the field. You have to type in NULL. Also, remember, flow steps can't be undone after running.

   ![(smile)](assets/smile.svg)

By the way, this little technique is on the Marketo certification exam. Don't tell them we said so! 