---
unique-page-id: 11384433
description: Account Team Setup - Marketo Docs - Product Documentation
title: Account Team Setup
exl-id: a4aee37f-5e39-4296-b720-b1c73c98df9e
---
# Account Team Setup {#account-team-setup}

An account team is a group of stakeholders who work together on a named account. Follow these steps to choose which CRM account roles should be added.

1. Click **Admin**.

   ![](assets/one-3.png)

1. Click **Target Account Management**.

   ![](assets/account-team-setup-2.png)

1. Under Account Team Members, click **Edit**.

   ![](assets/3.png)

   >[!NOTE]
   >
   >For Account Role, give it a name and match it to the desired User Lookup Field in your CRM.

1. Type in your Account Role name and select the **CRM** field. Add up to 10.

   ![](assets/four-2.png)

   >[!NOTE]
   >
   >You are not able to select Account Owner. It's chosen by default from the account level in your CRM.

1. Click **Save** when done.

   ![](assets/five-2.png)

   >[!CAUTION]
   >
   >If you make an update, it may take some time for the changes to reflect in TAM.

   >[!NOTE]
   >
   >* When Multiple CRM Accounts with different account owners are merged into a Named Account, Marketo will pick one "Account Owner" and add other account owners as "Account Co-Owners"
   >
   >* If a CRM "Role" field is later renamed or deleted, Marketo TAM will stop syncing the updated values until the user manually updates the setup in TAM
