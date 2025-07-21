---
unique-page-id: 11378814
description: "[!UICONTROL Account Lists] - Marketo Docs - Product Documentation"
title: "[!UICONTROL Account Lists]"
exl-id: 31bb4341-d012-4239-8f40-10a07cd4c51c
feature: Target Account Management
---
# [!UICONTROL Account Lists] {#account-lists}

An account list is a collection of named accounts that can be targeted together. Account lists allow you to target named accounts by industry, location, or size of the company.

In addition to account lists, you can also create dynamic account lists that are generated from public CRM Account Views. A CRM Account View is a set of rules that acts as a filter when displaying accounts. For example, you can use it to find accounts where Industry is Healthcare *and* Revenue is over $100M.

![](assets/one.png)

>[!NOTE]
>
>Account lists created in Marketo [!UICONTROL Target Account Management] are automatically available when building smart lists and web campaigns in [Web Personalization](/help/marketo/product-docs/web-personalization/using-web-segments/web-segments.md).

## Create a New Account List {#create-a-new-account-list}

1. Click the **[!UICONTROL New]** drop-down and select **[!UICONTROL Create New Account List]**.

   ![](assets/1a.png)

1. Give your list a name and click **[!UICONTROL Create]**.

   ![](assets/three-0.png)

1. After you create your account list, get started on [adding named accounts to it](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)!

   >[!NOTE]
   >
   >Marketo will only display insights for account lists with 2,000 or fewer named accounts.

## Create a New Dynamic Account List {#create-a-new-dynamic-account-list}

1. Click the **[!UICONTROL New]** drop-down and select **[!UICONTROL Create New Dynamic List]**.

   ![](assets/1.png)

1. In the dialog, select a **CRM Account View** from the drop-down, or type in the name to search for it.

   ![](assets/image2017-7-18-9-48-23.png)

1. Click **[!UICONTROL Create]**.

   ![](assets/step4.jpg)

   >[!NOTE]
   >
   >In Salesforce, be sure to provide List View Object permissions to the sync user.

## Rename an Account List {#rename-an-account-list}

>[!NOTE]
>
>These steps apply only to account lists. _Dynamic_ account lists use the name of their associated CRM Account Views.

1. Select the account you want to rename, click the **[!UICONTROL Account List Actions]** drop-down and select **[!UICONTROL Rename Account List]**.

   ![](assets/three.png)

1. Enter the new name and click **[!UICONTROL Rename]**.

   ![](assets/four.png)

   >[!NOTE]
   >
   >The CRM Account View syncs to the dynamic account list every 8 hours. If they are not yet synced, Marketo will sync them during the next cycle.

## Delete an Account List {#delete-an-account-list}

>[!NOTE]
>
>These steps are the same for both account lists and dynamic account lists.

1. Select the account you want to delete, click the **[!UICONTROL Account List Actions]** drop-down and select **[!UICONTROL Delete Account List]**.

   ![](assets/five.png)

1. Click **[!UICONTROL Delete]**.

   ![](assets/six.png)

>[!MORELIKETHIS]
>
>* [Add an Existing [!UICONTROL Named Account] to an Account List](/help/marketo/product-docs/target-account-management/target/named-accounts/add-an-existing-named-account-to-an-account-list.md)
>* [Account List Insights](/help/marketo/product-docs/target-account-management/measure/account-list-insights.md)
