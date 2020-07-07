---
unique-page-id: 2360368
description: Configure Marketo Sales Insight in Salesforce Enterprise/Unlimited - Marketo Docs - Product Documentation
title: Configure Marketo Sales Insight in Salesforce Enterprise/Unlimited
---

# Configure Marketo Sales Insight in Salesforce Enterprise/Unlimited {#configure-marketo-sales-insight-in-salesforce-enterprise-unlimited}

Configure Marketo Sales Insight in Salesforce Enterprise/Unlimited - Marketo Docs - Product Documentation

>[!NOTE]
>
>**Prerequisites**
>
>* [Configure Marketo field sync in your Salesforce Enterprise/Unlimited Edition](../../../../product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition.md)
>* [Install Marketo Sales Insight Package in Salesforce AppExchange](../../../../product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)
>

### What's in this article? {#whats-in-this-article}

[Configure Marketo Sales Insight](#configure-marketo-sales-insight)  
[Customize Page Layouts](#customize-page-layouts)  
[Map Custom Lead Fields](#map-custom-lead-fields)  
[Access Marketo Sales Insight](#access-marketo-sales-insight)

#### Configure Marketo Sales Insight {#configure-marketo-sales-insight}

1. Open a new web browser window to get the Marketo Sales Insight credential from your Marketo account.
1. Go to the **Admin** area. Select **Sales Insight**.

   ![](assets/image2015-6-12-16-3a27-3a24.png)

1. Click on **Edit API Configuration**.

   ![](assets/image2015-6-12-16-3a37-3a11.png)

1. Enter an **API Secret Key** of your choosing then click **Save**.

   >[!NOTE]
   >
   >Your API Secret Key is like a password for your organization and should be secure. **Caution**: Don't use an ampersand (&) in your API Secret Key.

   ![](assets/image2015-6-12-16-3a36-3a21.png)

   >[!TIP]
   >
   >You will need to enter these credentials in Salesforce, so keep this window open.

1. Back in Salesforce, click **Setup**.

   ![](assets/image2015-6-12-16-3a38-3a34.png)

1. Search for “remote site" and select **Remote Site Settings.**

   ![](assets/image2014-9-24-17-3a25-3a52.png)

1. Click **New Remote Site**.

   ![](assets/image2014-9-24-17-3a26-3a6.png)

1. Enter the **Remote Site Name** and **Remote Site URL** then click **Save**.

   >[!NOTE]
   >
   >Remote Site URL is the Marketo Host URL from the Edit API Configuration dialog window in the previous step.

   ![](assets/image2014-9-24-17-3a26-3a21.png)

#### Customize Page Layouts {#customize-page-layouts}

1. Use page layouts to set which fields are visible (accessible) to the users.

   >[!TIP]
   >
   >To limit access to a&nbsp;smaller set of users, follow the instructions in this article&nbsp; [Limit Sales Insight Access in Salesforce](https://nation.marketo.com/docs/DOC-1129).

1. Click **Setup**.

   ![](assets/image2015-6-12-16-3a38-3a34.png)

1. Search for "page layouts" and select **Page Layouts** under the **Leads** heading.

   ![](assets/image2014-9-24-17-3a32-3a16.png)

1. Click **Edit** for your Lead Layout.

   ![](assets/image2014-9-24-17-3a32-3a35.png)

1. Click **Visualforce Pages**. Drag **Section** to the layout underneath the **Custom Links** section.

   ![](assets/image2014-9-24-17-3a32-3a53.png)

1. Enter “Marketo Sales Insight” for the **Section Name**. Select **1-Column** and Click **OK**.

   >[!TIP]
   >
   >We recommend that you select 1-column layout.

   ![](assets/image2014-9-24-17-3a33-3a23.png)

1. Add the object element according to the object type (for instance, add Lead when you’re working on Lead Page Layouts).

   ![](assets/image2014-9-24-17-3a33-3a45.png)

1. Double-click on the object element that you just added.

   ![](assets/image2014-9-24-17-3a34-3a0.png)

1. Edit height to 450 pixels and click **OK**.

   >[!TIP]
   >
   >The height of 410 pixels is recommended for the Accounts and Opportunities objects.

   ![](assets/image2014-9-24-17-3a34-3a26.png)

1. Click on **Fields**&nbsp;on the left. Then search and drag **Engagement** into the Marketo Sales Insight layout.

   ![](assets/image2015-6-15-11-3a52-3a47.png)

1. **Repeat Step 10** for the following fields:

    * Engagement
    * Last Interesting Moment Date
    * Last Interesting Moment Desc
    * Last Interesting Moment
    * Last Interesting Moment Source
    * Last Interesting Moment Type
    * Relative Score
    * Relative Score Value
    * Urgency Value
    * View in Marketo

1. When finished, click **Save**.

   ![](assets/image2014-9-24-17-3a35-3a6.png)

1. Repeat steps 7-9 to add Visualforce page sections for **Contact**, **Account**, and **Opportunity**. Then repeat steps 10-12 to add Sales Insight fields for **Contact**. This is presuming you've already done both for **Lead**.

#### Map Custom Lead Fields {#map-custom-lead-fields}

Marketo lead fields need to be mapped to Salesforce contact fields to ensure no data gets lost during conversions.

1. Click **Setup**.

   ![](assets/image2015-6-12-16-3a38-3a34.png)

1. Search for "fields" in the search bar and click **Fields** under Leads.

   ![](assets/image2015-6-1-9-3a54-3a50.png)

1. Click **Map Lead Fields**.

   ![](assets/map-lead-fields.png)

1. Click on the dropdown on the right for **Engagement**.

   ![](assets/image2015-6-1-10-3a9-3a53.png)

1. Select **Contact.Engagement**&nbsp;in the list.

   ![](assets/image2015-6-1-10-3a12-3a11.png)

1. Repeat and map these fields as well.

<table> 
 <thead> 
  <tr> 
   <th colspan="1" rowspan="1"> 
    <div>
      Marketo Person Custom Field 
    </div></th> 
   <th colspan="1" rowspan="1"> 
    <div>
      Salesforce Contact Custom Field 
    </div></th> 
  </tr> 
 </thead> 
 <tbody> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Engagement</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Engagement</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Relative Score Value</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Relative Score Value</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Urgency Value</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Urgency Value</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Last Interesting Moment Date</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Last Interesting Moment Date</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Last Interesting Moment Desc</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Last Interesting Moment Desc</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Last Interesting Moment Source</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Last Interesting Moment Source</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Last Interesting Moment Type</p></td> 
   <td colspan="1" rowspan="1"><p>Contact.Last Interesting Moment Type</p></td> 
  </tr> 
 </tbody> 
</table>

1. Click **Save** when you’re done.

   ![](assets/image2014-9-24-17-3a37-3a17.png)

#### Access Marketo Sales Insight {#access-marketo-sales-insight}

1. Go to **+** and click **Marketo Sales Insight Config**.

   ![](assets/image2014-9-24-17-3a37-3a45.png)

1. Check **Enable Marketo API**. Enter your Marketo credentials from the Marketo Admin section (which you kept handy from the first section).

   ![](assets/image2014-9-24-17-3a38-3a0.png)

   >[!TIP]
   >
   >If the diagnostics test failed, you might need to&nbsp; [add more fields to your page layout](https://nation.marketo.com/docs/DOC-1115).

1. Woohoo! You've just unlocked the powerful Marketo Sales Insight. You can see the details for all your leads, contacts, accounts and opportunities in the Marketo Sales Insight section.
  
   ![](assets/twenty-six.png)

>[!NOTE]
>
>**Related Articles**
>
>* [Priority, Urgency, Relative Score, and Best Bets](../../../../product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.md)
>* [Add Marketo Sales Insight Tab and Buttons to Salesforce](../../../../product-docs/marketo-sales-insight/msi-for-salesforce/features/bulk-actions/add-marketo-sales-insight-tab-and-buttons-to-salesforce.md)
>* [Prepare Sales Insight for Multi-Lingual Support in Salesforce](../../../../product-docs/marketo-sales-insight/msi-for-salesforce/features/language-support/prepare-sales-insight-for-multi-lingual-support-in-salesforce.md)
>

