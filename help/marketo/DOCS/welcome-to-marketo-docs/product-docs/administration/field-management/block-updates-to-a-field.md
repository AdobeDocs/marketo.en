---
unique-page-id: 2360291
description: Block Updates to a Field - Marketo Docs - Product Documentation
title: Block Updates to a Field
---

# Block Updates to a Field {#block-updates-to-a-field}

Block Updates to a Field - Marketo Docs - Product Documentation

Blocking updates to a field allows you to write to the field once and then retain the original value for the lifetime of the field. This can be useful for a field like Person Source.

>[!NOTE]
>
>**Admin Permissions Required**

1. Go to **Admin** and click **Field Management**.

   ![](assets/image2014-9-24-13-3a54-3a40.png)

1. Find the field, select it, then under **Field Actions**, click **Block Field Updates**.

   ![](assets/two-1.png)

1. Select the **Input Sources** you want to block and click **Apply**.

   ![](assets/image2014-9-24-13-3a55-3a16.png)

   >[!CAUTION]
   >
   >When performing a list import, the status of a field being blocked in the Import Preview will only show if the field is automatically recognized by Marketo based on the name of the field matching **exactly** (or if aliases are established). If the field is manually chosen from the Marketo Field drop-down, the blocked status will not show in the Import Preview, but update-blocking to that field will still be implemented.

