---
unique-page-id: 7511512
description: Install and Configure Marketo Sales Insight in Salesforce1 - Marketo Docs - Product Documentation
title: Install and Configure Marketo Sales Insight in Salesforce1
exl-id: 9f26e90b-3199-4ef8-92bc-95e8bd81f1c5
feature: Marketo Sales Insights
---
# Install and Configure Marketo Sales Insight in Salesforce1 {#install-and-configure-marketo-sales-insight-in-salesforce}

>[!NOTE]
>
>Existing customers, please [Upgrade Your MSI Package](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md) before you continue!

>[!PREREQUISITES]
>
>If you have Salesforce Enterprise/Unlimited:
>
>* [Step 1 of 3: Add Marketo Fields to Salesforce (Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-1-of-3-add-marketo-fields-to-salesforce-enterprise-unlimited.md)
>* [Step 2 of 3: Create a Salesforce User for Marketo (Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md)
>* [Step 3 of 3: Connect Marketo and Salesforce (Enterprise/Unlimited)](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-3-of-3-connect-marketo-and-salesforce-enterprise-unlimited.md)
>* [Configure Marketo Sales Insight in Salesforce Enterprise/Unlimited](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md)
>
>If you have Salesforce Professional:
>
>* [Configure Marketo Sales Insight in Salesforce Professional Edition](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md)
>

>[!NOTE]
>
>Marketo Sales Insight in Salesforce1 includes: Best Bets, Lead Feed, Interesting Moments, and Add to Marketo Campaign.

## Enable the Salesforce1 Mobile App {#enable-the-salesforce1-mobile-app}

1. Click **Setup** and then **Mobile Administration**.

   ![](assets/image2015-4-21-15-3a29-3a22.png)

1. Click **Salesforce1**.

   ![](assets/image2015-4-21-15-3a30-3a51.png)

1. Click **Salesforce1 Settings**.

   ![](assets/image2015-4-21-15-3a32-3a21.png)

1. Click **Enable the Salesforce1 mobile browser app**.

   ![](assets/image2015-4-21-15-3a34-3a27.png)

1. Click **Save**.

   ![](assets/image2015-4-21-15-3a42-3a48.png)

1. Select **Mobile Administration**.

   ![](assets/image2015-4-22-11-3a10-3a14.png)

1. Click **Manage the mobile navigation menu**.

   ![](assets/image2015-4-22-11-3a13-3a10.png)

1. Select **Marketo** and **Add** it to the **Selected** menu items.

   ![](assets/image2015-4-22-14-3a55-3a37.png)

1. Select **Marketo**, move it **Up** to a desired area, and click **Save**.

   ![](assets/image2015-4-22-17-3a20-3a56.png)

## Hide Outdated Marketo Custom Object {#hide-outdated-marketo-custom-object}

1. Click **Setup**.

   ![](assets/image2015-4-22-15-3a13-3a48.png)

1. Select **Manage Users**.

   ![](assets/image2015-5-5-11-3a13-3a45.png)

1. Select **Profiles**.

   ![](assets/image2015-5-5-11-3a15-3a21.png)

1. Click to **edit** any desired profiles.

   ![](assets/image2015-5-5-13-3a51-3a36.png)

1. Under **Tab Settings**, select the _first_ **Marketo**.

   ![](assets/image2015-5-5-13-3a55-3a36.png)

1. Select **Tab Hidden**.

   ![](assets/image2015-5-5-14-3a2-3a29.png)

   >[!NOTE]
   >
   >Make sure to hide the Marketo tab for all desired profiles!

## Customize Tabs {#customize-tabs}

1. Click **+**.

   ![](assets/image2015-4-22-17-3a14-3a49.png)

1. Click **Customize My Tabs**.

   ![](assets/image2015-4-22-17-3a16-3a22.png)

1. Select **Marketo** and **Add** it to the Selected Tabs.

   ![](assets/image2015-4-22-17-3a17-3a15.png)

1. Select **Marketo**, move it **Up** to a desired area, and click **Save**.

   ![](assets/image2015-4-22-18-3a29-3a47.png)

## Customize Page Layouts {#customize-page-layouts}

1. Click **Setup**.

   ![](assets/image2015-4-22-17-3a26-3a56.png)

1. Click **Setup**, type **Page Layouts**, and click **Page Layouts** under Leads.

   >[!NOTE]
   >
   >Repeat the steps for every Page Layout that your organization uses (marketing, sales, etc.) for Contact, Account, and Opportunity objects.

   ![](assets/image2015-4-22-17-3a34-3a33.png)

1. Click **Edit** to make changes to the Lead Layout.

   ![](assets/image2015-4-22-17-3a44-3a0.png)

1. Click **Visualforce Pages** and then drag **Lead Mobile** to the Mobile Cards section.

   ![](assets/image2015-4-22-17-3a49-3a37.png)

1. Change the Height to 66 and click **OK**.

   ![](assets/image2015-4-22-17-3a52-3a15.png)

1. Click **Fields** and drag **Add to Marketo Campaign** to the **Marketo Sales Insight** section.

   ![](assets/configure-step-6.png)

   >[!TIP]
   >
   >Type "Add to" into the Quick Find to make Add to Marketo Campaign easy to find.

1. Click **Save**.

   ![](assets/image2015-4-22-18-3a1-3a56.png)

Phew! You're finally done installing Marketo Sales Insight for Salesforce1! Go ahead and give yourself a pat on the back.

>[!MORELIKETHIS]
>
>* [Best Bets in Salesforce1](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/best-bets-in-salesforce1.md)
>* [Interesting Moments in Salesforce1](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/interesting-moments-in-salesforce1.md)
>* [Send Marketo Email and Campaign and Watchlist Actions in Salesforce1](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/msi-for-mobile/send-marketo-email-and-campaign-and-watchlist-actions-in-salesforce1.md)
