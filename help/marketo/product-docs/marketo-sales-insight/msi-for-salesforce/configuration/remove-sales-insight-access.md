---
description: Remove Sales Insight Access - Marketo Docs - Product Documentation
title: Remove Sales Insight Access
exl-id: 3cda112a-524e-469b-a222-c0192b2f5301
---
# Remove [!DNL Sales Insight] Access {#remove-sales-insight-access}

Use the following steps to remove access to [!DNL Sales Insight] features in [!DNL Salesforce]. Applicable to [!DNL Salesforce] Classic and Lightning.

## Overview {#overview}

Permission to the objects mentioned below, apex classes, and visualforce pages is required to access all [!DNL Sales Insight] features. Removing these will remove access to [!DNL Sales Insight].

**Object Settings**

<table> 
 <tbody> 
 <tr> 
   <td>BestBetsCache</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>[!DNL Best Bets] View Details</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>[!DNL Best Bets] Views</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>EmailActivityCache</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>GetMethodArgus</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>GroupedWebActivityCache</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>InterestingMomentsCache</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>[!DNL Marketo Sales Insight] Config</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>ScoringCache</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>Values</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
  <tr> 
   <td>WebActivityCache</td> 
   <td>Read, Create, Edit, Delete, View All, Modify All</td> 
  </tr> 
 </tbody> 
</table>

* Apex Class Access: 159 Apex Classes that begin with “mkto_si”
* Visualforce Page Access: 64 Visualforce Pages that begin with “mkto_si”
* Custom Setting Definitions: mkto_si.Marketo Settings & mkto_si.User Preferences

## Removing Access to [!DNL Sales Insight] {#removing-access-to-sales-insight}

1. Log in to your [!DNL Salesforce] account.

1. Click **[!UICONTROL Setup]**.

   ![](assets/remove-sales-insight-access-1.png)

1. Under [!UICONTROL Administrator], click **[!UICONTROL Manage Users]**, then **[!UICONTROL Profiles]**.

1. Click on the profile you'd like to update, then **[!UICONTROL Edit]**.

1. Scroll down to “[!UICONTROL Custom Tab Settings]” under [!UICONTROL Tab Settings].

1. Select the “[!UICONTROL Tab Hidden]” option from the drop-down for [!DNL Marketo Sales Insight] Config and MSI [!DNL Marketo Sales] Outbox.

   ![](assets/remove-sales-insight-access-2.png)

   ![](assets/remove-sales-insight-access-3.png)

1. Scroll down to “[!UICONTROL Custom Object Permissions].”

1. Remove "Read, Create, Edit, Delete" access from following objects:

   * BestBetsCache
   * [!DNL Best Bets] View Details
   * [!DNL Best Bets] Views
   * EmailActivityCache
   * GetMethodArgus
   * GroupedWebActivityCache
   * InterestingMomentsCache
   * [!DNL Marketo Sales Insight] Config
   * ScoringCache
   * Values
   * WebActivityCache

1. Scroll down to the “[!UICONTROL Enabled Apex Class Access]” section. Click **[!UICONTROL Edit]**.

1. From the “[!UICONTROL Enabled Apex Classes]” section, select all classes that begin with “mkto_si”. This should add up to 159 classes.  

1. Click **[!UICONTROL Remove]**, then **[!UICONTROL Save]**.

   ![](assets/remove-sales-insight-access-4.png)

1. Scroll down to “[!UICONTROL Enabled Visualforce Page Access]” section. Click **[!UICONTROL Edit]**.

1. From the “[!UICONTROL Enabled Visualforce Pages]” section, select all pages that begin with “mkto_si”. This should add up to 64 pages.  

1. Click **[!UICONTROL Remove]**, then **[!UICONTROL Save]**.

   ![](assets/remove-sales-insight-access-5.png)

1. Scroll down to the “[!UICONTROL Enabled Custom Setting Definitions Access]” section. Click **[!UICONTROL Edit]**.

1. Select "Marketo Sales Insight.mkto_si.Marketo Settings" and "Marketo Sales Insight.mkto_si.User Preferences."  

1. Click **[!UICONTROL Remove]**, then **[!UICONTROL Save]**.

   ![](assets/remove-sales-insight-access-6.png)

That’s it! You’ve successfully removed [!DNL Sales Insight] access. Repeat the same steps for any other profile you’d like to remove access for.
