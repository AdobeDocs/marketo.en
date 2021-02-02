---
unique-page-id: 4719291
description: Set Default Person Last Name and Company Name - Marketo Docs - Product Documentation
title: Set Default Person Last Name and Company Name
---

# Set Default Person Last Name and Company Name {#set-default-person-last-name-and-company-name}

Salesforce requires (minimum) last name and company name for its Leads and Contacts. Incomplete records will not sync to Salesforce. If you wish to sync partial records, you must set default values for Marketo to use with Salesforce.

1. Go to **Admin** and click **Salesforce**.

   ![](assets/image2014-12-9-13-3a41-3a58.png)

1. Click **Edit Sync Options**.

   ![](assets/image2014-12-9-13-3a42-3a6.png)

1. Enter a **Default person last name** and a **Default person company** then click **Save**.

   ![](assets/sync-options-hands.png)

   >[!NOTE]
   >
   >Marketo only assigns a default value when the record is initially synced to Salesforce, and only if either of the required fields are empty.

And that's that! Every time a person is missing a last name and/or company name, Marketo will add the default value as it syncs the record over.
