---
description: Learn how to enable Marketo AI permissions, configure organizational rules, and manage settings like integrations and notifications.
title: Settings and Setup
exl-id: faf642a1-25f0-4566-b35d-074b003835ed
---
# Settings and setup {#settings-setup}

Learn how to enable permissions and use the Settings area to view connection details, define organizational rules, and set up integrations and notifications.

>[!AVAILABILITY]
>
>This feature is in limited availability. To request access, fill out [this form](https://forms.cloud.microsoft/Pages/ResponsePage.aspx?id=Wht7-jR7h0OUrtLBeN7O4Y-uSf63sAxCmWyqMJg8eMFUMVZSVExSNDA3T0I4SEcwRDFSVTBGWU01Uy4u&origin=QRCode){target="_blank"}. Be sure to have your subscription's Munchkin ID ready.

>[!PREREQUISITES]
>
>To use this feature you must first agree to the [Core Gen-AI terms and the supplemental terms](https://www.adobe.com/legal/terms/enterprise-licensing/genai-ww.html){target="_blank"}. Contact your account manager for details.

## Permissions and roles {#permission-and-role}

There is an _Access Marketo AI_ permission and a _Marketo AI User_ role, giving administrators greater control over which users can access the **Marketo AI** feature. The permission is assigned at the role level. The _Marketo AI User_ role comes with the _Access Marketo AI_ permission enabled by default.

>[!IMPORTANT]
>
>The _Access Marketo AI_ permission is not enabled by default for all roles. See the table below for details.

| Role | Default status |
| --- | --- |
| Admin | Enabled |
| Adobe Product Admin | Enabled |
| Marketing User | Disabled |
| Standard User | Not available |
| Marketo AI User | Enabled |
| Custom roles | Disabled |

### Access Marketo AI permission {#access-marketo-ai-permission}

Follow the steps below to enable _Access Marketo AI_ for qualifying roles that do not already have it enabled.

1. In your My Marketo, click **Admin**, then **Users & Roles**.

   ![](assets/settings-setup-1.png)

1. In the _Roles_ tab, select the desired role and click **Edit Role**.

   ![](assets/settings-setup-2.png)

1. Scroll down and check the _Access Marketo AI_ checkbox and click **Save**.

   ![](assets/settings-setup-3.png)

   >[!NOTE]
   >
   >You can use these same steps to remove the permission by **un**checking the _Access Marketo AI_ checkbox.

### Marketo AI User role {#marketo-ai-user-role}

Follows these steps to assign a specific user to the _Marketo AI User_ role.

>[!NOTE]
>
>This role **only** contains the _Access Marketo AI_ permission.

1. In your My Marketo, click **Admin**, then **Users & Roles**.

   ![](assets/settings-setup-4.png)

1. Select the desired user and click **Edit User**.

   ![](assets/settings-setup-5.png)

1. In _Roles and Workspaces_, select the _Marketo AI User_ checkbox. If you have more than one workspace, you can specify which ones get access in the **+** sign drop-down. Click **Save** when done.

   ![](assets/settings-setup-6.png)

### Custom role {#custom-role}

You also have the option to [create a new role](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role#create-a-role){target="_blank"} and customize its permissions, adding _Access Marketo AI_, along with anything else you want, and [assigning that role](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user){target="_blank"} to specific users.

## Settings {#settings}

1. In your My Marketo, click the **Marketo AI** tile.

   ![](assets/settings-setup-7.png)

1. Click the gear icon.

   ![](assets/settings-setup-8.png)

### Connection {#connection}

This tab is does not contain editable fields. It shows you account information like your Munchkin ID and IMS Organization.

   ![](assets/settings-setup-9.png)

### Organizational rules {#organizational-rules}

Define organizational guidelines and constraints that the Marketo AI follows when creating or modifying Marketo Engage assets.

   ![](assets/settings-setup-10.png){width="800" zoomable="yes"}

>[!NOTE]
>
>Rules use Markdown format with YAML frontmatter. Global rules apply to all workspaces. Workspace rules override global settings.

### Integrations (Coming soon) {#integrations}

Configure connections to external services and APIs.

_This tab may appear in the UI, but it is not yet available for use. Please check back for updates_.

### Notifications (Coming soon) {#notifications}

Manage alert preferences and notification channels.

_This tab may appear in the UI, but it is not yet available for use. Please check back here for updates_.
