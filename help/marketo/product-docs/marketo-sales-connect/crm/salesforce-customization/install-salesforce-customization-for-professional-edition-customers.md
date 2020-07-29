---
unique-page-id: 27656223
description: Install Salesforce Customization for Professional Edition Customers - Marketo Docs - Product Documentation
title: Install Salesforce Customization for Professional Edition Customers
---

# Install Salesforce Customization for Professional Edition Customers {#install-salesforce-customization-for-professional-edition-customers}

Customers with Salesforce Professional Edition will have to follow these steps to install customization.

>[!NOTE]
>
>**Prerequisites**
>
>* Sales Connect Admin needs to connect their Salesforce and Sales Connect accounts.
>* Salesforce Instance used needs to have space to install thirteen Custom Activity Fields.
>

#### Installation {#installation}

1. In Sales Connect, click the gear icon on the upper-right and select **Settings**.

   ![](assets/one-4.png)

1. Under Admin Settings, click **Salesforce**.

   ![](assets/two-4.png)

1. Verify you are connected to your Salesforce account.

   >[!CAUTION]
   >
   >If you are connected, you'll see a green "Install" button. **DO NOT** click this button, proceed to step 4 instead.

1. Log-in to the Salesforce account you are connected to and then click [this link](http://login.salesforce.com/packaging/installPackage.apexp?p0=04t0b000001oWEZ).
1. You'll be sent to the Sales Connect Installation page.

   ![](assets/install-package.png)

1. Choose the users you would like to install customizations for: Admin only, all users, or specific profiles.
1. Click on the **Install** button to install customization.
1. To confirm successful installation, log-in to your Salesforce account.
1. Click **Setup**, search for "Installed Packages" in the search bar, and click **Installed Packages**.

   You will see Marketo Sales Connect Customizations there.  
  
   In order to configure Sales Connect in your Salesforce instance, please follow the steps starting from "CONFIGURING THE SALES ENGAGE SALESFORCE PACKAGE" section on page 7 of the Installation Guide.

   >[!NOTE]
   >
   >Sales Engage is the previous name for Sales Connect.

   [Installation Guide for Salesforce Classic](http://s3.amazonaws.com/tout-user-store/salesforce/assets/Marketo+Sales+Engage+For+Salesforce_+Installation+and+Success+Guide.pdf)  
  
   [Installation Guide for Salesforce Lightning](http://s3.amazonaws.com/tout-user-store/salesforce/assets/SF+Guide+for+Lightning.pdf)

