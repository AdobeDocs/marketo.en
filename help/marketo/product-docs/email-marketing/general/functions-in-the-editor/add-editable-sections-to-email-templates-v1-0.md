---
unique-page-id: 1900585
description: Learn how to add editable sections to email templates in v1.0. Let users edit specific areas while keeping the rest locked.
title: Add Editable Sections to Email Templates v1.0
exl-id: f397aa8e-0d0b-4007-91e1-9b9158bd6432
feature: Email Editor
TQID: https://experienceleague.adobe.com/j2rwpy7Bq-HH3-mva5FkDb3kKH8cvlH2hMUp0ic7sno
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
---
# Add Editable Sections to Email Templates v1.0 {#add-editable-sections-to-email-templates-v1.0}

If you are creating a template in the Email Template Editor v1.0, you can make any section editable by putting a special `<div>` around it.

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
