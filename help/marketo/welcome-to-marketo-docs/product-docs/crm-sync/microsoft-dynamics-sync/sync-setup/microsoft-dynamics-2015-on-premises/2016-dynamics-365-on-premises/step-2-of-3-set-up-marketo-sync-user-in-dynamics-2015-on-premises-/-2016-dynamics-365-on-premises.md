---
unique-page-id: 7504739
description: Step 2 of 3: Set Up Marketo Sync User in Dynamics 2015 On-Premises / 2016 Dynamics 365 On-Premises - Marketo Docs - Product Documentation
title: Step 2 of 3: Set Up Marketo Sync User in Dynamics 2015 On-Premises / 2016 Dynamics 365 On-Premises
---

# Step 2 of 3: Set Up Marketo Sync User in Dynamics 2015 On-Premises / 2016 Dynamics 365 On-Premises {#step-of-set-up-marketo-sync-user-in-dynamics-on-premises-dynamics-on-premises}

Step 2 of 3: Set Up Marketo Sync User in Dynamics 2015 On-Premises / 2016 Dynamics 365 On-Premises - Marketo Docs - Product Documentation

`Great job completing the previous steps. Let's keep moving through this.`

>[!NOTE]
>
>**Prerequisites**
>
>* [Step 1 of 3: Install the Marketo Solution - 2015 On-Premises / 2016 Dynamics 365 On-Premises](../../../../../../../../welcome-to-marketo-docs/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises/2016-dynamics-365-on-premises/step-1-of-3-install-the-marketo-solution-2015-on-premises-/-2016-dynamics-365-on-premises.md)
>

### What's in this article? {#what-s-in-this-article}

[Assign Sync User Role](#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-assignsyncuserrole)  
[Configure Marketo Solution](#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-configuremarketosolution)  
[Before Proceeding to Step 3](#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-beforeproceedingtostep3)

#### Assign Sync User Role {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-assignsyncuserrole}

Assign the Marketo Sync User role only to the Marketo sync user. You don't need to assign it to any other users.

>[!NOTE]
>
>This applies to Marketo version 4.0.0.14 and later. For earlier versions, all users must have the sync user role. To upgrade your Marketo, see [Upgrade the Marketo Solution for Microsoft Dynamics](../../../../../../../../welcome-to-marketo-docs/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/download-the-marketo-lead-management-solution/upgrade-the-marketo-solution-for-microsoft-dynamics.md).

##### 1. Under Settings, click Security. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-undersettings-clicksecurity.}

![](assets/assign1.png)

##### 2. Click Users. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-clickusers.}

![](assets/assign2.png)

##### 3. You will see a list of users here. Select the dedicated Marketo Sync user or contact your [Active Directory Federation Services](https://msdn.microsoft.com/en-us/library/bb897402.aspx)(ADFS) administrator to create a dedicated user for Marketo. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-youwillseealistofusershere.selectthededicatedmarketosyncuserorcontactyouractivedirectoryfederationservices(adfs)administratortocreateadedicateduserformarketo.}

![](assets/image2015-3-26-10-3a39-3a35.png)

##### 4. Select the sync user. Click Manage Roles. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-selectthesyncuser.clickmanageroles.}

![](assets/assign4.png)

##### 5. Check Marketo Sync User and click OK. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-checkmarketosyncuserandclickok.}

![](assets/assign5.png)

>[!TIP]
>
>If you don't see the role, go back to [step 1 of 3](#) and import the solution.

>[!NOTE]
>
>Any updates made in your CRM by the Sync User will **not** be synced back to Marketo.

#### Configure Marketo Solution {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-configuremarketosolution}

Almost done! We just have a few last pieces of configuration before moving onto the next article.

##### 1. Under Settings, click Marketo Config. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-undersettings-clickmarketoconfig.}

![](assets/configure1.png)

>[!NOTE]
>
>If `Marketo Config is missing, try refreshing the page. If the issue persists,` [publish the Marketo Solution](#) [again](https://docs.marketo.com/pages/viewpage.action?pageId=3571822#publish-customizations) or try logging out and back in.

##### 2. Click Default. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-clickdefault.}

![](assets/configure2.png)

##### 3. Click the Marketo User field and select the sync user. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-clickthemarketouserfieldandselectthesyncuser.}

![](assets/configure3.png)

##### 4. Click the save icon in the bottom right corner. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-clickthesaveiconinthebottomrightcorner.}

![](assets/configure4.png)

##### 5. Click Publish All Customizations. {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-clickpublishallcustomizations.}

![](assets/publish-all-customizations1.png)

#### Before Proceeding to Step 3 {#step2of3-setupmarketosyncuserindynamics2015on-premises/2016dynamics365on-premises-beforeproceedingtostep3}

* If you want to restrict the number of records you sync, [set up a custom sync filter](../../../../../../../../welcome-to-marketo-docs/product-docs/crm-sync/microsoft-dynamics-sync/create-a-custom-dynamics-sync-filter.md) now.
* Run the [Validate Microsoft Dynamics Sync](../../../../../../../../welcome-to-marketo-docs/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md) process. It verifies that your initial setups were done correctly.
* Log into the Marketo Sync User in Microsoft Dynamics CRM.

>[!NOTE]
>
>**Related Articles**
>
>[Step 3 of 3: Connect Marketo and Dynamics 2015 On-Premises / 2016 Dynamics 365 On-Premises](../../../../../../../../welcome-to-marketo-docs/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/microsoft-dynamics-2015-on-premises/2016-dynamics-365-on-premises/step-3-of-3-connect-marketo-and-dynamics-2015-on-premises-/-2016-dynamics-365-on-premises.md)

`  
` 