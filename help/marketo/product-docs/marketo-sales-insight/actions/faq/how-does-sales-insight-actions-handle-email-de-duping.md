---
description: How Does Sales Insight Actions Handle Email De-Duping - Marketo Docs - Product Documentation
title: How Does Sales Insight Actions Handle Email De-Duping
exl-id: 40b01f7f-df50-4bd2-ac35-4c4e4f80915e
---
# How Does [!DNL Sales Insight Actions] Handle Email De-Duping? {#how-does-sales-insight-actions-handle-email-de-duping}

When you're [uploading a CSV](/help/marketo/product-docs/marketo-sales-insight/actions/people/managing-contacts/import-contacts-via-csv.md) file into [!DNL Sales Insight Actions], we merge all like contacts in the CSV before the import takes place.

We do this based on like email address. So, if there are two identical email addresses, we merge them into one contact.

If you later try to manually add/upload the same contact, we won't merge it.

If you try to add a contact that's already in your database, we will prevent you from adding it.
