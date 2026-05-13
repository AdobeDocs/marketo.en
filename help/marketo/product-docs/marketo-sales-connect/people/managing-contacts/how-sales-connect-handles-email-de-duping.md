---
unique-page-id: 14352514
description: Understand how Sales Connect handles email de-duping. Learn how duplicate contacts are merged or handled when syncing.
title: How Sales Connect Handles Email De-Duping
exl-id: 1f57d943-8439-4653-a4e7-6dac65b3312d
feature: Marketo Sales Connect
TQID: https://experienceleague.adobe.com/gO6I2rCotAEDOGQNdRleeJbqMIix1wQizZe84JZSLPs
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: c5f60233-d5ea-4453-a799-0ad258b4d399
    internal-label: Database
---
# How [!DNL Sales Connect] Handles Email De-Duping {#how-sales-connect-handles-email-de-duping}

When you are [uploading a CSV](/help/marketo/product-docs/marketo-sales-connect/people/managing-contacts/import-contacts-via-csv.md) file into [!DNL Sales Connect], we merge all like contacts in the CSV before the import takes place.

We do this based on like email address. So, if there are two identical email addresses, we merge them into one contact.

If you later try to manually add/upload the same contact, we won't merge it.

If you try to add a contact that's already in your database, we will prevent you from adding it.
