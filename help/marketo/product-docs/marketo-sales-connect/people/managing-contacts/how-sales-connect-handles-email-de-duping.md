---
unique-page-id: 14352514
description: How Sales Connect Handles Email De-Duping - Marketo Docs - Product Documentation
title: How Sales Connect Handles Email De-Duping
exl-id: 1f57d943-8439-4653-a4e7-6dac65b3312d
feature: Marketo Sales Connect
---
# How Sales Connect Handles Email De-Duping {#how-sales-connect-handles-email-de-duping}

When you're [uploading a CSV](/help/marketo/product-docs/marketo-sales-connect/people/managing-contacts/import-contacts-via-csv.md) file into Sales Connect, we merge all like contacts in the CSV before the import takes place.

We do this based on like email address. So, if there are two identical email addresses, we merge them into one contact.

If you later try to manually add/upload the same contact, we won't merge it.

If you try to add a contact that's already in your database, we will prevent you from adding it.
