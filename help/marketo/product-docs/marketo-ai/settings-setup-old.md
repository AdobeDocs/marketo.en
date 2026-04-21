---
description: "Learn how to enable Marketo AI permissions, configure organizational rules, and manage settings like integrations and notifications."
title: Settings and Setup
hide: yes
hidefromtoc: yes
exl-id: d6f37214-65b9-48c1-bf9f-d64b4eda87b9
---
# Settings and setup {#settings-setup}

Learn how to enable permissions and use the Settings area to view connection details, define organizational rules, and set up integrations and notifications.

## Permissions {#permissions}

>[!IMPORTANT]
>
>In the Alpha phase of Marketo AI, _access is enabled by default_ for the following roles: Admin, Adobe Product Admin, Marketing User, Standard User. So instead of turning it on for roles you want to have access, you must turn it off for roles you don't.

### Access for all {#access-for-all}

If you want Marketo AI enabled for all roles listed above, you don't have to do anything.

### Access for some {#access-for-some}

If you want to remove access for any roles, follow the steps below.

1. In your My Marketo, click **Admin**, then **Users & Roles**.

   ![](assets/settings-setup-1.png)

1. In the _Roles_ tab, select the desired role and click **Edit Role**.

   ![](assets/settings-setup-2.png)

1. Scroll down and _uncheck_ the **Access Build with AI** checkbox and click **Save**.

   ![](assets/settings-setup-3.png)

Repeat these steps for any other desired roles.

### Custom role {#custom-role}

You also have the option to [create a new role](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role#create-a-role){target="_blank"} and customize its permissions, adding _Access Build with AI_, along with anything else you want, and [assigning that role](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user){target="_blank"} to specific users.

<!-- 
## Permissions {#permissions}

In order to access Marketo AI, Admins must first enable role permissions. 

1. In your My Marketo, click **Admin**, then **Users & Roles**.

   ![](assets/settings-setup-1.png)

1. In the _Roles_ tab, select the desired role and click **Edit Role**.

   ![](assets/settings-setup-2.png)

1. Scroll down and select the **Access Build with AI** checkbox and click **Save**.

   ![](assets/settings-setup-3.png)

-->

## Settings {#settings}

1. In your My Marketo, click the **Build with AI** tile.

   ![](assets/settings-setup-4.png)

1. Click the gear icon.

   ![](assets/settings-setup-5.png)

### Connection {#connection}

This tab is does not contain editable fields. It shows you account information like your Munchkin ID and IMS Organization.

   ![](assets/settings-setup-6.png)

### Organizational rules {#organizational-rules}

Define organizational guidelines and constraints that the Marketo AI follows when creating or modifying Marketo Engage assets.

   ![](assets/settings-setup-7.png){width="800" zoomable="yes"}

>[!NOTE]
>
>Rules use Markdown format with YAML frontmatter. Global rules apply to all workspaces. Workspace rules override global settings.

### Integrations (Coming soon) {#integrations}

Configure connections to external services and APIs.

_This tab may appear in the UI, but it is not yet available for use. Please check back for updates_.

### Notifications (Coming soon) {#notifications}

Manage alert preferences and notification channels.

_This tab may appear in the UI, but it is not yet available for use. Please check back for updates_.
