---
unique-page-id: 11382122
description: Enable Audit Trail - Marketo Docs - Product Documentation
title: Enable Audit Trail
---

# Enable Audit Trail {#enable-audit-trail}

Audit Trail is available to all customers and controlled by two admin permissions.

>[!NOTE]
>
>By default, all system admin roles have both permissions enabled.

### What's in this article? {#whats-in-this-article}

[Enable Audit Trail for a Role](#enable-audit-trail-for-a-role)  
[Assign Audit Trail Role to a User](#assign-audit-trail-role-to-a-user)

#### Enable Audit Trail for a Role {#enable-audit-trail-for-a-role}

1. Click **Admin**.

   ![](assets/one-2.png)

1. Select **Users & Roles** and click **Roles**.

   ![](assets/two-2.png)

1. Select the role you want to enable Audit Trail for and click **Edit Role**.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >You also have the option here to create a new role and grant it Audit Trail access.

1. Expand the **Access Admin** permission. Select **Access Audit Trail** and/or **Access Login History**, depending on your needs. Click **Save**.

   ![](assets/four-1.png)

   >[!NOTE]
   >
   >**Definition**
   >
   >
   >**Access Audit Trail:** Gives users access to both Asset Audit Trail and Admin Audit Trail.
   >
   >
   >**Access Login History:** Gives users access to [User Login History](user-login-history.md).

#### Assign Audit Trail Role to a User {#assign-audit-trail-role-to-a-user}

>[!NOTE]
>
>**Prerequisites**
>
>[Create](http://docs.marketo.com/display/DOCS/Create,+Delete,+Edit+and+Change+a+User+Role#Create,Delete,EditandChangeaUserRole-CreateaRole) or [enable](#Enable) an existing role, giving it Audit Trail permissions.

1. In **Users & Roles**, click **Users**.

   ![](assets/five-1.png)

1. Select the user you want to give Audit Trail access to and click **Edit User**.

   ![](assets/six-1.png)

   >[!NOTE]
   >
   >This process also applies when you're creating a new user.

1. Select the Audit Trail roles you created. In this example we created "Audit Trail - Asset and Admin," and "Audit Trail - With Login History."

   ![](assets/seven-1.png)

   >[!CAUTION]
   >
   >If you have workspaces enabled, make sure to check the role's checkbox, which selects all workspaces. Deselecting an individual workspace will hide Audit Trail. This means you will see Audit Trail data for every workspace. You do have the option of hiding workspaces when [filtering](http://docs.marketo.com/display/DOCS/Filtering+in+Audit+Trail).

1. Click **Save**.

   ![](assets/eight-1.png)

