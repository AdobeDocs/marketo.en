---
unique-page-id: 1900585
description: Add Editable Sections to Email Templates v1.0 - Marketo Docs - Product Documentation
title: Add Editable Sections to Email Templates v1.0
---

# Add Editable Sections to Email Templates v1.0 {#add-editable-sections-to-email-templates-v1.0}

If you're creating a template in the Email Template Editor v1.0, you can make any section editable by putting a special `<div>` around it.

>[!NOTE]
>
>**Example**
>
>`<pre> <div class="mktEditable" id="UNIQUE_ID">This part is editable</div></pre>`

Rules:

1. The HTML must always be valid.
1. The class of **mktEditable** must be included.
1. The ID must be unique in that HTML.
1. No spaces in the ID.

>[!CAUTION]
>
>mktEditable statements cannot be nested.

If you want to learn how to do this in Email Template Editor v2.0, check out [email template syntax](/help/marketo/product-docs/email-marketing/general/email-editor-2/email-template-syntax.md).
