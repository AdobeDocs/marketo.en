---
unique-page-id: 3571743
description: Configure Marketo Sales Insight in Salesforce Professional Edition - Marketo Docs - Product Documentation
title: Configure Marketo Sales Insight in Salesforce Professional Edition
---

# Configure Marketo Sales Insight in Salesforce Professional Edition {#configure-marketo-sales-insight-in-salesforce-professional-edition}

Configure Marketo Sales Insight in Salesforce Professional Edition - Marketo Docs - Product Documentation

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

Here are the steps you need to take to configure Marketo Sales Insight in Salesforce Professional Edition. Let's get started.

>[!NOTE]
>
>**Prerequisites**
>
>[Install Marketo in your Salesforce Professional Edition](../../../../../welcome-to-marketo-docs/product-docs/crm-sync/salesforce-sync/setup/professional-edition.md)
>
>[Install Marketo Sales Insight Package in Salesforce AppExchange](../../../../../welcome-to-marketo-docs/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md)

>[!NOTE]
>
>**Admin Permissions Required**

### What's in this article? {#what-s-in-this-article}

[Set up Marketo Sales Insight](#configuremarketosalesinsightinsalesforceprofessionaledition-setupmarketosalesinsight)  
[Customize Page Layouts](#configuremarketosalesinsightinsalesforceprofessionaledition-customizepagelayouts)  
[Map Custom Person Fields](#configuremarketosalesinsightinsalesforceprofessionaledition-mapcustompersonfields)  
[Marketo Sales Insight Config](#configuremarketosalesinsightinsalesforceprofessionaledition-marketosalesinsightconfig)

#### Set up Marketo Sales Insight {#configuremarketosalesinsightinsalesforceprofessionaledition-setupmarketosalesinsight}

##### 1. Log in to your Marketo instance and click Admin. {#configuremarketosalesinsightinsalesforceprofessionaledition-logintoyourmarketoinstanceandclickadmin.}

![](assets/login-admin.png)

##### 2. Click Sales Insight. {#configuremarketosalesinsightinsalesforceprofessionaledition-clicksalesinsight.}

![](assets/image2015-5-22-15-3a12-3a33.png)

##### 3. Click Edit API Configuration. {#configuremarketosalesinsightinsalesforceprofessionaledition-clickeditapiconfiguration.}

![](assets/image2015-5-22-15-3a15-3a0.png)

##### 4. Enter an API Secret Key and click Save. {#configuremarketosalesinsightinsalesforceprofessionaledition-enteranapisecretkeyandclicksave.}

>[!CAUTION]
>
>Don't use an ampersand (&) in your API Secret Key.

![](assets/image2015-5-27-16-3a36-3a56.png)

>[!TIP]
>
>Keep this window open. You will need this information later in Salesforce.

##### 5. Go back to Salesforce, click Setup. {#configuremarketosalesinsightinsalesforceprofessionaledition-gobacktosalesforce-clicksetup.}

![](assets/image2015-5-22-14-3a40-3a39.png) 

##### 6. Search for "remote site" and click Remote Site Setting under Security Controls. {#configuremarketosalesinsightinsalesforceprofessionaledition-searchfor"remotesite"andclickremotesitesettingundersecuritycontrols.}

![](assets/image2014-9-24-17-3a25-3a52.png) 

##### 7. Click New Remote Site. {#configuremarketosalesinsightinsalesforceprofessionaledition-clicknewremotesite.}

![](assets/image2014-9-24-17-3a26-3a6.png) 

##### 8. Enter Remote Site Name and Remote Site URL, then click Save. {#configuremarketosalesinsightinsalesforceprofessionaledition-enterremotesitenameandremotesiteurl-thenclicksave.}

![](assets/remote-site.png)

>[!NOTE]
>
>You choose your **Remote Site Name** (MarketoAPI is used here). The **Remote Site URL** can be found in the Marketo Host field of your Edit API Configuration dialog box from Step 4.

####  Customize Page Layouts {#configuremarketosalesinsightinsalesforceprofessionaledition-customizepagelayouts}

##### 1. Click Setup. {#configuremarketosalesinsightinsalesforceprofessionaledition-clicksetup.}

![](assets/image2015-5-22-14-3a40-3a39.png)

##### 2. Search for "page layout" and select the Page Layout under Leads. {#configuremarketosalesinsightinsalesforceprofessionaledition-searchfor"pagelayout"andselectthepagelayoutunderleads.}

![](assets/image2015-5-28-14-3a58-3a39.png)

1. Click **Visualforce Pages **on the left. Drag **Section** to the layout underneath Custom Links section.

   ![](assets/image2014-9-24-17-3a32-3a53.png)

   ##### Enter "Marketo Sales Insight" as the Section Name. Select 1-Column and click OK. {#configuremarketosalesinsightinsalesforceprofessionaledition-enter"marketosalesinsight"asthesectionname.select1-columnandclickok.}

   ![](assets/image2014-9-24-17-3a33-3a23.png)

1. Drag and drop **Lead** into the new section.

   ![](assets/image2014-9-24-17-3a33-3a45.png)

   >[!TIP]
   >
   >The name of this box will change based on the object type. For example, if you are modifying the page layout for Contacts, it will say Contact.

1. Double-click on the **Lead** block that you just added.

   ![](assets/image2014-9-24-17-3a34-3a0.png)

1. Edit height to **450** pixels and click **OK**.

   ![](assets/image2014-9-24-17-3a34-3a26.png)

   >[!TIP]
   >
   >We recommend a height of 410 pixels for the Accounts and Opportunities objects.

1. Click on **Fields **on the left. Then search and drag the **Engagement** label into the **Marketo Sales Insight** layout.

   ![](assets/image2015-5-22-16-3a32-3a46.png)

1. Repeat the above step for these fields as well.

<table class="wrapped confluenceTable"> 
 <tbody> 
  <tr> 
   <td colspan="1">Engagement</td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Relative Score Value</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Urgency Value</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Last Interesting Moment Date</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Last Interesting Moment Desc</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Last Interesting Moment Source</p></td> 
  </tr> 
  <tr> 
   <td colspan="1" rowspan="1"><p>Last Interesting Moment Type</p></td> 
  </tr> 
 </tbody> 
</table>

1. lick **Save** when finished.

   ![](assets/image2014-9-24-17-3a35-3a6.png)

   ##### Repeat this process to add Visualforce page sections and Sales Insight fields for Contact, Account and Opportunity. {#configuremarketosalesinsightinsalesforceprofessionaledition-repeatthisprocesstoaddvisualforcepagesectionsandsalesinsightfieldsforcontact-accountandopportunity.}

   ##### Repeat steps 5-7 to add Visualforce page sections for Contact, Account, and Opportunity. Then, repeat steps 8-10 to add Sales Insight fields for Contact. Be sure to save after any changes. {#configuremarketosalesinsightinsalesforceprofessionaledition-repeatsteps5-7toaddvisualforcepagesectionsforcontact-account-andopportunity.then-repeatsteps8-10toaddsalesinsightfieldsforcontact.besuretosaveafteranychanges.}

####  Map Custom Person Fields {#configuremarketosalesinsightinsalesforceprofessionaledition-mapcustompersonfields}

Marketo person fields need to be mapped to Salesforce contact fields to ensure that the conversion works properly. Here's how.

##### 1. Click Setup. {#configuremarketosalesinsightinsalesforceprofessionaledition-clicksetup..1}

![](assets/image2015-5-22-14-3a40-3a39.png)

##### 2. Search for "fields" in the search bar and click Fields under Leads. {#configuremarketosalesinsightinsalesforceprofessionaledition-searchfor"fields"inthesearchbarandclickfieldsunderleads.}

![](assets/image2015-6-1-9-3a54-3a50.png)

##### 3. Click Map Lead Fields. {#configuremarketosalesinsightinsalesforceprofessionaledition-clickmapleadfields.}

** ![](assets/image2015-6-1-9-3a58-3a48.png)

**

##### 4. Click on the dropdown on the right for Engagement. {#configuremarketosalesinsightinsalesforceprofessionaledition-clickonthedropdownontherightforengagement.}

![](assets/image2015-6-1-10-3a9-3a53.png)

##### 5. Select Contact.Engagement in the list. {#configuremarketosalesinsightinsalesforceprofessionaledition-selectcontact.engagementinthelist.}

![](assets/image2015-6-1-10-3a12-3a11.png)

##### 6. Repeat and map these fields as well. {#configuremarketosalesinsightinsalesforceprofessionaledition-repeatandmapthesefieldsaswell.}

<table class="wrapped confluenceTable"> 
 <tbody> 
  <tr> 
   <th colspan="1" rowspan="1">Marketo Person Custom Field</th> 
   <th colspan="1" rowspan="1">Salesforce Contact Custom Field</th> 
  </tr> 
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

1. Click **Save **when you’re done.

   ![](assets/image2014-9-24-17-3a37-3a17.png)

####  Marketo Sales Insight Config {#configuremarketosalesinsightinsalesforceprofessionaledition-marketosalesinsightconfig}

##### 1. Click + and then select Marketo Sales Insight Config. {#configuremarketosalesinsightinsalesforceprofessionaledition-click+andthenselectmarketosalesinsightconfig.}

![](assets/image2014-9-24-17-3a37-3a45.png)

1. Check **Enable Marketo API**. Then fill in the [API Configuration info in Marketo Admin](https://docs.marketo.com/display/DOCS/Configure+Marketo+Sales+Insight+in+Salesforce+Professional+Edition#ConfigureMarketoSalesInsightinSalesforceProfessionalEdition-SetupMarketoSalesInsight). Click **Save Changes **when you are done.

   ![](assets/image2014-9-24-17-3a38-3a0.png)

   >[!NOTE]
   >
   >If the diagnostics test failed, you might need to [add more fields to your page layout](https://nation.marketo.com/docs/DOC-1115).

And that's it! You should be able to see the Marketo Sales Insight fields for Leads, Contacts, Accounts and Opportunities.

![](assets/twenty-six.png)

>[!NOTE]
>
>For accounts, Sales Insight will include all emails, but only the most recent interesting moments, web activity, and score changes.

>[!NOTE]
>
>**Related Articles**
>
>* [Priority, Urgency, Relative Score, and Best Bets](../../../../../welcome-to-marketo-docs/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.md)
>* [Add Marketo Sales Insight Tab and Buttons to Salesforce](../../../../../welcome-to-marketo-docs/product-docs/marketo-sales-insight/msi-for-salesforce/features/bulk-actions/add-marketo-sales-insight-tab-and-buttons-to-salesforce.md)
>

