---
unique-page-id: 10099102
description: Plug-In Releases for Microsoft Dynamics MSI - Marketo Docs - Product Documentation
title: Plug-In Releases for Microsoft Dynamics MSI
exl-id: 830f7dc3-07fd-429b-b0fd-290ffdda88e6
---
# Plug-In Releases for Microsoft Dynamics MSI {#plug-in-releases-for-microsoft-dynamics-msi}

When you first sync to Microsoft Dynamics, you download and install the latest version of the plug-ins for Marketo Sales Insight (MSI). Periodically, Marketo updates these plug-ins, so you can return to the same place to download the new version.

Please [download the latest plug-in](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/installing/download-the-marketo-sales-insight-solution-for-microsoft-dynamics.md) corresponding to your Dynamics release.

>[!NOTE]
>
>These versions work for both on-premise and online versions of Dynamics.

## Upgrading your MSI Solution {#upgrading-your-msi-solution}

1. Import the latest version of the solution _over the existing version_ of your Dynamics CRM by pressing the **Import** button in Dynamics.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-1.png)

>[!NOTE]
>
>Example: if your Dynamics CRM has version 2.0.0.20 and the latest version is 2.0.0.21, you would import _over_ version 2.0.0.20.

1. Click **Next**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-2.png)

1. Select **Stage for Upgrade** and **Maintain customizations**, then click **Import**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-3.png)

1. Click **Next**.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-4.png)

1. After a successful import you'll see two MSI solutions: MarketoSalesInsight and MarketoSalesInsight_Upgrade. Select the older solution and click Apply Solution Upgrade.

   ![](assets/plug-in-releases-for-microsoft-dynamics-msi-5.png)

And that's it! After the upgrade you will only see one MSI Solution.

## Version Updates {#version-updates}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th colspan="1">Release Date</th> 
   <th colspan="1">Version</th> 
   <th colspan="1">Notes</th> 
  </tr> 
  <tr> 
   <td colspan="1">10/1/20</td> 
   <td colspan="1">2.0.0.21</td> 
   <td colspan="1">Bug Fix: Assigning access to MSI API config fields for users with Sales Insight role</td> 
  </tr> 
  <tr> 
   <td colspan="1">07/20/20</td> 
   <td colspan="1">2.0.0.20</td> 
   <td colspan="1">Bug fix: Add a validation message for non-synced records</td> 
  </tr> 
  <tr> 
   <td colspan="1">06/12/20</td> 
   <td colspan="1">2.0.0.19</td> 
   <td colspan="1">Bug fix: To hide MSI Secret Password on MSD API Config</td> 
  </tr> 
  <tr> 
   <td colspan="1">05/26/20</td> 
   <td colspan="1">2.0.0.18</td> 
   <td colspan="1">Bug fix: To change MSI role ID validation for displaying MSI buttons</td> 
  </tr> 
  <tr> 
   <td colspan="1">05/21/20</td> 
   <td colspan="1">2.0.0.17</td> 
   <td colspan="1">Bug fix: Unhide owner field and making fields non-mandatory</td> 
  </tr> 
  <tr> 
   <td colspan="1">04/28/20</td> 
   <td colspan="1">2.0.0.16</td> 
   <td colspan="1">Bug fix: Removing MSD CRM sitemap setting link dependency</td> 
  </tr> 
 </tbody> 
</table>
