---
unique-page-id: 2360335
description: Block Field Updates During List Import from Untrusted Sources - Marketo Docs - Product Documentation
title: Block Field Updates During List Import from Untrusted Sources
---

# Block Field Updates During List Import from Untrusted Sources {#block-field-updates-during-list-import-from-untrusted-sources}

Block Field Updates During List Import from Untrusted Sources - Marketo Docs - Product Documentation

You can trust the data in some lists more than others. Sometimes you have questionable data and want to take it if the field is blank, but not if there is an existing value. You can accomplish this by blocking field updates on key fields.

>[!NOTE]
>
>**Admin Permissions Required**

### What's in this article? {#what-s-in-this-article}

[Blocking Field Updates From Untrusted Sources](#blockfieldupdatesduringlistimportfromuntrustedsources-blockingfieldupdatesfromuntrustedsources)  
[Running an Untrusted List Import](#blockfieldupdatesduringlistimportfromuntrustedsources-runninganuntrustedlistimport)

#### Blocking Field Updates From Untrusted Sources {#blockfieldupdatesduringlistimportfromuntrustedsources-blockingfieldupdatesfromuntrustedsources}

1. Go to **Admin** and click **Field Management**.

   ![](assets/image2014-9-19-9-3a38-3a38.png)

1. Find the field you want, select it, then under **Field Actions**, click **Block Field Updates**.

   ![](assets/image2014-9-19-9-3a39-3a40.png)

1. Check **List Import untrusted source** and click **Apply**.

   ![](assets/blockupdates.png)

>[!TIP]
>
>You can keep fields safe from all lists, trusted and untrusted, by also checking **List Import trusted source**.

Repeat the above steps for any other fields you want to keep safe from untrusted lists. 

#### Running an Untrusted List Import {#blockfieldupdatesduringlistimportfromuntrustedsources-runninganuntrustedlistimport}

1. When running your list import, be sure to select **Untrusted **if you want all fields you set up in the previous step to be safe.

   ![](assets/importpersondetails.jpg)

For detailed instructions on importing lists, see [Import a List of People](../../../../welcome-to-marketo-docs/getting-started/quick-wins/import-a-list-of-people.md).

Nice work! Now you know how to keep key fields safe from untrusted lists.
