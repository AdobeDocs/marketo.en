---
unique-page-id: 11382122
description: Enable Audit Trail - Marketo Docs - Product Documentation
title: Enable Audit Trail
---

# Enable Audit Trail {#enable-audit-trail}

Enable Audit Trail - Marketo Docs - Product Documentation

Audit Trail is available to all customers and controlled by two admin permissions.

>[!NOTE]
>
>By default, all system admin roles have both permissions enabled.

### What's in this article? {#what-s-in-this-article}

[Enable Audit Trail for a Role](#enableaudittrail-enableaudittrailforarole)  
[Assign Audit Trail Role to a User](#enableaudittrail-assignaudittrailroletoauser)

#### Enable Audit Trail for a Role {#enableaudittrail-enableaudittrailforarole}

##### 1. Click Admin. {#enableaudittrail-clickadmin.}

![](assets/one-2.png)

##### 2. Select Users & Roles and click Roles. {#enableaudittrail-selectusers&rolesandclickroles.}

![](assets/two-2.png)

##### 3. Select the role you want to enable Audit Trail for and click Edit Role. {#enableaudittrail-selecttheroleyouwanttoenableaudittrailforandclickeditrole.}

![](assets/three-1.png)

>[!NOTE]
>
>You also have the option here to create a new role and grant it Audit Trail access.

##### 4. Expand the Access Admin permission. Select Access Audit Trail and/or Access Login History, depending on your needs. Click Save. {#enableaudittrail-expandtheaccessadminpermission.selectaccessaudittrailand/oraccessloginhistory-dependingonyourneeds.clicksave.}

![](assets/four-1.png)

>[!NOTE]
>
>**Definition**
>
>**Access Audit Trail:** Gives users access to both Asset Audit Trail and Admin Audit Trail.
>
>**Access Login History:** Gives users access to [User Login History](user-login-history.md).

#### Assign Audit Trail Role to a User {#enableaudittrail-assignaudittrailroletoauser}

>[!NOTE]
>
>**Prerequisites**
>
>[Create](http://docs.marketo.com/display/DOCS/Create,+Delete,+Edit+and+Change+a+User+Role#Create,Delete,EditandChangeaUserRole-CreateaRole) or [enable](#EnableAuditTrail-Enable) an existing role, giving it Audit Trail permissions.

##### 1. In Users & Roles, click Users. {#enableaudittrail-inusers&roles-clickusers.}

![](assets/five-1.png)

##### 2. Select the user you want to give Audit Trail access to and click Edit User. {#enableaudittrail-selecttheuseryouwanttogiveaudittrailaccesstoandclickedituser.}

![](assets/six-1.png)

>[!NOTE]
>
>This process also applies when you're creating a new user.

##### 3. Select the Audit Trail roles you created. In this example we created "Audit Trail - Asset and Admin," and "Audit Trail - With Login History." {#enableaudittrail-selecttheaudittrailrolesyoucreated.inthisexamplewecreated"audittrail-assetandadmin-"and"audittrail-withloginhistory."}

![](assets/seven-1.png)

>[!CAUTION]
>
>If you have workspaces enabled, make sure to check the role's checkbox, which selects all workspaces. Deselecting an individual workspace will hide Audit Trail. This means you will see Audit Trail data for every workspace. You do have the option of hiding workspaces when [filtering](http://docs.marketo.com/display/DOCS/Filtering+in+Audit+Trail).

##### 4. Click Save. {#enableaudittrail-clicksave.}

![](assets/eight-1.png)

