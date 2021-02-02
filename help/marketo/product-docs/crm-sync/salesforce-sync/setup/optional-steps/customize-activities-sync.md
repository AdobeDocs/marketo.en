---
unique-page-id: 4719294
description: Customize Activities Sync - Marketo Docs - Product Documentation
title: Customize Activities Sync
---

# Customize Activities Sync {#customize-activities-sync}

If you don't use Marketo Sales Insight, Marketo can create Salesforce Activity History Records for certain events. Here's how to enable them.

1. Go to **Admin**.

   ![](assets/admin.png)

1. Click **Salesforce**, then click **Edit Sync Options**.

   ![](assets/two-1.png)

1. Check the boxes next to activities you want Marketo to push to Salesforce, and click **Save**.

   ![](assets/three-1.png)

   >[!NOTE]
   >
   >Once enabled, Marketo will push three months' worth of activity history. Depending on the amount of data, _this could take several days to complete_. Updates that occur during the initial Activities push may be delayed until after the initial Activities sync is complete.

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <thead> 
  <tr> 
   <th>Activity Type</th> 
   <th>Description</th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td>Filled out form</td> 
   <td>Filled out any Marketo form</td> 
  </tr> 
  <tr> 
   <td>Added to list</td> 
   <td><p>Flow step: Was added to a static list</p></td> 
  </tr> 
  <tr> 
   <td>Email sent</td> 
   <td>Flow step: Was sent an email</td> 
  </tr> 
  <tr> 
   <td>Email delivered</td> 
   <td>Received an email (not bounced)</td> 
  </tr> 
  <tr> 
   <td>Email opened</td> 
   <td>Opened an email (without blocking images)</td> 
  </tr> 
  <tr> 
   <td>Clicked link in email</td> 
   <td>Clicked a link in an email sent by Marketo</td> 
  </tr> 
  <tr> 
   <td>Removed from list</td> 
   <td>Flow step: Was removed from a static list</td> 
  </tr> 
  <tr> 
   <td>Remove from flow</td> 
   <td>Flow step: Remove from flow</td> 
  </tr> 
  <tr> 
   <td>Sales email sent</td> 
   <td>Was sent an email through Marketo Sales Insight</td> 
  </tr> 
  <tr> 
   <td>Sales email opened</td> 
   <td>Opened an email sent through Marketo Sales Insight</td> 
  </tr> 
  <tr> 
   <td>Click link in sales email</td> 
   <td>Clicked a link in an email sent through Marketo Sales Insight</td> 
  </tr> 
  <tr> 
   <td>Sales email received</td> 
   <td>An email was received and logged by the Sales rep in the MSI Outlook Plugin</td> 
  </tr> 
 </tbody> 
</table>

   >[!NOTE]
   >
   >"Sales email received" does **not** mean delivered. Delivered status is not captured for emails sent via Sales Insight.

   >[!TIP]
   >
   >If you're interested in getting more Marketo information into Salesforce, check out our [Marketo Sales Insight](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md) product.
