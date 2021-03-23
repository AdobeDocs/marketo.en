---
unique-page-id: 37357050
description: Upgrading Your MSI Package - Marketo Docs - Product Documentation
title: Upgrading Your MSI Package
---

# Upgrading Your MSI Package {#upgrading-your-msi-package}

1. Navigate to [this page in the appexchange](https://appexchange.salesforce.com/listingDetail?listingId=a0N30000001SVZmEAO).

1. Log in to your Salesforce instance (the one connected to your Marketo instance, can be sandbox or production) from the top-right corner in the page from Step One. You must have Admin privileges to install/upgrade a managed package in Salesforce.

1. Click the **Get It Now** button. You'll be asked to choose where you’d like to install. You'll be given the option to upgrade since you already have a previous version of MSI. Choose an option based on the account you logged into during Step One.

   >[!TIP]
   >
   >We recommend you test this on your sandbox instance before upgrading your production instance.

1. You can upgrade the package by choosing “Install for Admins Only” (and provide MSI access to specific profiles later), “Install for All Users,” or, “Install for Specific Profiles.” In this example we're choosing Admins Only. When you've made your selection, click **Upgrade**.

   ![](assets/four.png)

>[!NOTE]
>
>It is recommended you update the package for Admins only and then [provide access to specific users](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/setting-up-sales-insight-for-your-team.md) based on the number of MSI seats purchased. Alternatively, you can create a specific Salesforce profile for MSI users and install or upgrade the package for those users only.
