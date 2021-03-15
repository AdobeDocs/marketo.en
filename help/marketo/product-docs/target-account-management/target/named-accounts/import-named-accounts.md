---
unique-page-id: 12615800
description: Import Named Accounts - Marketo Docs - Product Documentation
title: Import Named Accounts
---

# Import Named Accounts {#import-named-accounts}

Already have a CSV full of potential target accounts? Import them directly into TAM!

1. Click the **New** drop-down and select **Import Named Accounts**.

   ![](assets/inaone.png)

1. A new window will open. Click **Browse**, then select the file of named accounts you want to import.

   ![](assets/inatwo.png)

   >[!TIP]
   >
   >In your file, provide [as much information](/help/marketo/product-docs/target-account-management/target/named-accounts/named-account-overview.md#named-account-attributes) as possible. You can only add firmographic information; nothing Marketo calculates (i.e. Pipeline). To create named accounts based on CRM accounts, simply export the account name and CRM ID from your CRM into a CSV file, use the Account Name option, and map the CRM ID during the import process. To properly link a CRM account to a named account, you must provide the CRM account's exact name.

1. Choose from two dedupe modes: Account Name or Domain Name. In this example we'll choose Account. Click the **Modes** drop-down and select **By Account Name**.

   ![](assets/inathree.png)

   >[!NOTE]
   >
   >If you choose **By Domain Mode**, both the named account and domain fields must be included.

1. To choose which account list your named account gets added to, click the **Account List** drop-down and make your selection.

   ![](assets/inafour.png)

   >[!NOTE]
   >
   >You can also create a brand new Account List by simply typing its name in the drop-down box.

1. To send a notification of the import, click the **Send Alert To** drop-down and select a Marketo user. You _cannot_ manually enter an email address.

   ![](assets/inafive-2.png)

1. Click **Next**.

   ![](assets/inasix-2.png)

1. Map each field by double-clicking on the **Marketo Field** drop-down and selecting the appropriate field. Click **Next** when done.

   ![](assets/inaseven.png)

   Success!

   ![](assets/inanine.png)

   >[!NOTE]
   >
   >"Check Import Status" only shows the last three days of activity.

Scenarios when you dedupe by Account Name:

<table> 
 <tbody> 
  <tr> 
   <td><strong>Importing record with existing Named Account name</strong></td> 
   <td><p>We will update the existing record</p></td> 
  </tr> 
  <tr> 
   <td><strong>Importing record with new Named Account name</strong></td> 
   <td>We will create a new record</td> 
  </tr> 
 </tbody> 
</table>

   Scenarios when you dedupe by Domain Name:

<table> 
 <tbody> 
  <tr> 
   <td><strong>Importing record with a new account name & new domain name</strong></td> 
   <td>We will create a new Named Account with the info provided</td> 
  </tr> 
  <tr> 
   <td><strong>Importing record with an existing account name & existing domain name</strong></td> 
   <td>We will update the existing Named Account</td> 
  </tr> 
   <tr> 
   <td><strong>Importing record with a new account name & existing domain name</strong></td> 
   <td>We will append the new account name to the existing Named Account that matches the domain name and update other info (i.e. Industry, State, etc)</td> 
  </tr> 
  <tr> 
   <td><strong>Importing record with existing Named Account name & new domain name</strong></td> 
   <td>We will append the new domain name to the existing Named Account that matches the account name and update other info (i.e. Industry, State, etc)</td> 
  </tr> 
 </tbody> 
</table>

   >[!NOTE]
   >
   >When Marketo appends a named account, we are updating a rule (behind the scenes) that allows us to identify people that should be a part of the Named Account. Example: if you update "IBM" to "IBM, USA," people with either company name will be associated to the Named Account.

   If Marketo finds records that we see as duplicates, we will only process the first one.
