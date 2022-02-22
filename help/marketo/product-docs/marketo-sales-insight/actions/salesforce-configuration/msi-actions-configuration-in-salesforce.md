---
description: MSI Actions Configuration in Salesforce - Marketo Docs - Product Documentation
title: MSI Actions Configuration in Salesforce
hide: yes
hidefromtoc: yes
exl-id: 2d842886-3501-4aca-96fb-0d6763ab2b01
---
# MSI Actions Configuration in Salesforce {#msi-actions-configuration-in-salesforce}

>[!PREREQUISITES]
>
>* [Install]() or [Upgrade]() Sales Insight Package in your Salesforce instance
Install/Upgrade to the [MSI Actions Package](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md) in your Salesforce instance.
>* [Configure Marketo Sales Insight in Salesforce Enterprise/Unlimited]()

## Add New Remote Site in Salesforce {#add-new-remote-site-in-salesforce}

1. In Salesforce, click **Setup**.

   ![](assets/msi-actions-configuration-in-salesforce-1.png)

1. Search for “remote site" and select **Remote Site Settings**.
   ![](assets/msi-actions-configuration-in-salesforce-2.png)

1. Click **New Remote Site**.

   ![](assets/msi-actions-configuration-in-salesforce-3.png)

1. Enter the Remote Site Name (it can be something like “MarketoSalesInsight”). Enter the Remote Site URL (https://ims-na1-stg1.adobelogin.com) and click **Save**.

   ![](assets/msi-actions-configuration-in-salesforce-4.png)

## Enabling MSI-Actions across the CRM {#enabling-msi-actions-across-the-crm}

1. In Salesforce, click the **Marketo Sales Insight Config** tab.

   ![](assets/msi-actions-configuration-in-salesforce-5.png)

   >[!NOTE]
   >
   >If you don't see "Marketo Sales Insight Config" in your top bar, click the **+** sign and find it under All Tabs.

1. Select the **Enable MSI Actions** checkbox.

   ![](assets/msi-actions-configuration-in-salesforce-6.png)

1. Enter the API Secret Key.

   ![](assets/msi-actions-configuration-in-salesforce-7.png)

   >[!NOTE]
   >
   >If you don't have your API Secrey Key handy, you can find it by following the steps in [this article](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md).

1. Click **Save** when done.

This will automatically enable all MSI Actions features outlined in the feature overview article.

>[!NOTE]
>
>You can disable all MSI Actions features by simply unchecking the “Enable MSI Actions” checkbox.

## MSI-Actions Governance {#msi-actions-governance}

1. You can disable Sales Campaigns and/or the Task tab in the upcoming section. This will be applicable to lead, contact, account, and opportunity panels.

   ![](assets/msi-actions-configuration-in-salesforce-8.png)

1. You can disable MSI Actions by unchecking corresponding features under Actions settings.

   ![](assets/msi-actions-configuration-in-salesforce-9.png)

>[!NOTE]
>
>Governance settings are applicable to all MSI users.
