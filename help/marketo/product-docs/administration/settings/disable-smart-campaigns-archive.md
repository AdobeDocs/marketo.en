---
description: Learn how to enable the Disable Smart Campaigns on Archive feature, which automatically deactivates campaigns when a folder or program is archived in Marketo.
title: Disable Smart Campaigns on Archive
feature: Administration
hide: true
---
# Disable Smart Campaigns on Archive {#disable-smart-campaigns-on-archive}

When this feature is enabled, archiving a folder or program automatically deactivates its campaigns to prevent unexpected activity.

When a folder or program is archived, or an active Smart Campaign is moved into a folder that is already archived, Marketo Engage stops the affected campaigns from running:

* **Triggered campaigns** are deactivated.
* **Batch campaigns** have their pending runs canceled.
* **Executable campaigns** have no running state, so no action is taken.

## How to enable {#how-to-enable}

1. In the **Admin** section, click **Treasure Chest**.

   ![The Admin navigation menu with Treasure Chest highlighted](assets/disable-smart-campaigns-on-archive-1.png)

1. Scroll to _Disable Smart Campaigns on Archive_ and click **Edit**.

   ![Treasure Chest settings page showing the Disable Smart Campaigns on Archive row with the Edit button](assets/disable-smart-campaigns-on-archive-2.png)

1. Select the **Enabled** checkbox and click **Save**.

   ![The Disable Smart Campaigns on Archive dialog showing the Enabled checkbox and Save button](assets/disable-smart-campaigns-on-archive-3.png)

<table>
  <tr>
    <td><b>Enabled (checked)</b></td>
    <td>Archiving deactivates every campaign, per the rules above.</td>
  </tr>
  <tr>
    <td><b>Disabled (unchecked)</b></td>
    <td>Archiving a folder or program still works, but campaigns are left running or scheduled as-is.</td>
  </tr>
</table>

>[!IMPORTANT]
>
>After toggling this setting, you must refresh your browser for the change to take effect.

## Supported actions

The following actions deactivate campaigns when _Disable Smart Campaigns on Archive_ is enabled:

* Dragging and dropping a **folder** containing active campaigns into an archived folder
* Dragging and dropping a **program** (any type) containing active campaigns into an archived folder
* Dragging and dropping a **single Smart Campaign** into an archived folder
* Right-clicking **Move** on a single Smart Campaign into an archived folder
* Right-clicking **Move Folder** on a folder containing active campaigns into an archived folder
* Right-clicking **Move** on a program containing active campaigns into an archived folder
* Right-clicking **Convert to Archived Folder** on a folder to archive it in place without moving it

>[!NOTE]
>
>If a Smart Campaign inside the folder or program being archived is referenced elsewhere (e.g., via a "Request Campaign" flow step), archiving is blocked to prevent breaking that other campaign.
