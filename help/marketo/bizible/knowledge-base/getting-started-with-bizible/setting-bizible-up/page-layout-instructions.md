---
unique-page-id: 18874799
description: Page Layout Instructions - Bizible - Product Documentation
title: Page Layout Instructions
---

# Page Layout Instructions {#page-layout-instructions}

Page Layout Instructions - Bizible - Product Documentation

To easily see Bizible data, it's recommended to update Page Layouts for the Account, Contact, Lead, Opportunity, and Campaign Objects. The instructions are broken out for each Object Page Layout below.

To begin, first navigate&nbsp;to your Salesforce Setup settings and locate the Customize tab.

### What's in this article? {#what-s-in-this-article}

[Campaign Object](#pagelayoutinstructions-campaignobject)  
[Leads](#pagelayoutinstructions-leads)  
[Contacts](#pagelayoutinstructions-contacts)  
[Opportunities](#pagelayoutinstructions-opportunities)  
[Accounts](#pagelayoutinstructions-accounts)

#### Campaign Object {#pagelayoutinstructions-campaignobject}

##### 1. Within your Build option, selectCampaigns. {#pagelayoutinstructions-withinyourbuildoption-selectcampaigns.}

##### 2. ClickPage Layouts. {#pagelayoutinstructions-clickpagelayouts.}

![](assets/1-2.jpg)

##### 3. Click Edit next to the page layout you want to update.  {#pagelayoutinstructions-clickeditnexttothepagelayoutyouwanttoupdate.}

![](assets/2-2.jpg)

##### 4. Within the fields option, select theEnable Bizible Touchpointsfield and drag it wherever you would like on the page. Next, add theTouchpoint Start Dateand Touchpoint End Datefields.  
{#pagelayoutinstructions-withinthefieldsoption-selecttheenablebizibletouchpointsfieldanddragitwhereveryouwouldlikeonthepage.next-addthetouchpointstartdateandtouchpointenddatefields.}

![](assets/3-5.png)

##### 5. Next, at the top of the page click the “Buttons” option within the quick find menu. {#pagelayoutinstructions-next-atthetopofthepageclickthe“buttons”optionwithinthequickfindmenu.}

##### 6. Drag theBulk Update Touchpoint Datebutton to your custom buttons section. {#pagelayoutinstructions-dragthebulkupdatetouchpointdatebuttontoyourcustombuttonssection.}

![](assets/4-2.jpg)

##### 7. Click Save. {#pagelayoutinstructions-clicksave.}

>[!NOTE]
>
>`If you are using multiple Campaign record types, the picklist values for the`**Enable Bizible Touchpoints** `field will need to be updated. Please reference` [this article](http://docs.marketo.com/x/PgEgAQ) `for instructions.`

`  
` 

#### Leads {#pagelayoutinstructions-leads}

##### 1. Within your Build option, selectLeads. {#pagelayoutinstructions-withinyourbuildoption-selectleads.}

##### 2. ClickPage Layouts. {#pagelayoutinstructions-clickpagelayouts..1}

##### 3. Click Edit next to the page layout you want to update. Keep in mind that multiple page layouts can contain the Bizible Touchpoints sections. {#pagelayoutinstructions-clickeditnexttothepagelayoutyouwanttoupdate.keepinmindthatmultiplepagelayoutscancontainthebizibletouchpointssections.}

##### 4. Click on the VisualForce page option on the left within your quick find menu. {#pagelayoutinstructions-clickonthevisualforcepageoptionontheleftwithinyourquickfindmenu.}

##### 5. Create a new section and name it “Bizible Touchpoints.”  {#pagelayoutinstructions-createanewsectionandnameit“bizibletouchpoints.”}

>[!NOTE]
>
>Select the "one column" format for each of these sections.

##### 6. Drag theBizible Lead Related ListVisualForce page into your page layout section. {#pagelayoutinstructions-dragthebizibleleadrelatedlistvisualforcepageintoyourpagelayoutsection.}

![](assets/5-5.png)

##### 7. Click on the wrench within the VisualForce page and change the height to 100 and enable scrollbars. {#pagelayoutinstructions-clickonthewrenchwithinthevisualforcepageandchangetheheightto100andenablescrollbars.}

##### 8. Back in the menu, select the Canvas Apps section and create a new section called "Bizible Insights" beneath the Touchpoints VisualForce section you just created. {#pagelayoutinstructions-backinthemenu-selectthecanvasappssectionandcreateanewsectioncalled"bizibleinsights"beneaththetouchpointsvisualforcesectionyoujustcreated.}

>[!NOTE]
>
>Select the "one column" format for each of these sections.

##### 9. Drag the Bizible Insights Canvas App into that newly created section. Click Save! Sometimes it is necessary to save the page layout first before dropping in the Canvas App because Salesforce doesn't instantly recognize it. So after creating the new section, save the page layout and then re-edit to drag the canvas app within that section. This applies to every object. {#pagelayoutinstructions-dragthebizibleinsightscanvasappintothatnewlycreatedsection.clicksave!sometimesitisnecessarytosavethepagelayoutfirstbeforedroppinginthecanvasappbecausesalesforcedoesn'tinstantlyrecognizeit.soaftercreatingthenewsection-savethepagelayo}

>[!NOTE]
>
>For the Bizible Insights Canvas App to function properly, [permissions need to be configured properly](http://docs.marketo.com/x/kQEgAQ). [  
>](https://support.bizible.com/hc/en-us/articles/360002043794-Bizible-Insights-Configuration)

`If you are leveraging Bizible's ABM feature, [please click here for additional page layout instructions](http://docs.marketo.com/x/agEgAQ).` 

#### Contacts {#pagelayoutinstructions-contacts}

##### 1. Within your Build option, selectContacts. {#pagelayoutinstructions-withinyourbuildoption-selectcontacts.}

##### 2. Click Page Layouts. {#pagelayoutinstructions-clickpagelayouts..2}

##### 3. Select the Page Layout you’d like to edit. {#pagelayoutinstructions-selectthepagelayoutyou’dliketoedit.}

Go to the Related Lists option within the quick find menu and add the**Bizible Touchpoints**related list.

##### 4. Click the wrench icon and add the following columns in this order: {#pagelayoutinstructions-clickthewrenchiconandaddthefollowingcolumnsinthisorder-}

* `Bizible Touchpoint`
* `Marketing Channel`
* `Touchpoint Source`
* `Ad Campaign Name`
* `Touchpoint Position`
* `Touchpoint Date`

##### 5. Sort By: Touchpoint Date, Ascending. {#pagelayoutinstructions-sortby-touchpointdate-ascending.}

![](assets/6.jpg)

##### 6. Expand the Buttons option and deselect New.  {#pagelayoutinstructions-expandthebuttonsoptionanddeselectnew.}

![](assets/7-3.png)

##### 7. Go back to the Related List option in the menu and now add theBizible Attribution Touchpointrelated list. {#pagelayoutinstructions-gobacktotherelatedlistoptioninthemenuandnowaddthebizibleattributiontouchpointrelatedlist.}

##### 8. Click the wrench icon and add the following columns in this order: {#pagelayoutinstructions-clickthewrenchiconandaddthefollowingcolumnsinthisorder-.1}

* `Attribution Touchpoint`
* `Marketing Channel`
* `Opportunity`
* `Ad Campaign Name`
* `Touchpoint Type`
* `Touchpoint Position`
* `Attribution % W-Shaped (or most robust attribution model such as Full Path or Custom)`
* `Revenue W-Shaped (or most robust attribution model such as Full Path or Custom)`
* `Touchpoint Date`

##### 9. Sort by Touchpoint Date > Ascending. {#pagelayoutinstructions-sortbytouchpointdate>ascending.}

##### 10. Expand the Buttons section and deselect New. {#pagelayoutinstructions-expandthebuttonssectionanddeselectnew.}

##### 11. Click Save. {#pagelayoutinstructions-clicksave..1}

#### Opportunities {#pagelayoutinstructions-opportunities}

##### 1. Within your Build option, selectOpportunities. {#pagelayoutinstructions-withinyourbuildoption-selectopportunities.}

##### 2. Click Page Layouts. {#pagelayoutinstructions-clickpagelayouts..3}

##### 3. Select the Page Layout you’d like to edit. {#pagelayoutinstructions-selectthepagelayoutyou’dliketoedit..1}

##### 4. Add theBizible Attribution TouchpointRelated List and click the wrench to add the following columns for Opportunities: {#pagelayoutinstructions-addthebizibleattributiontouchpointrelatedlistandclickthewrenchtoaddthefollowingcolumnsforopportunities-}

* `Attribution Touchpoint`
* `Marketing Channel`
* `Contact`
* `Ad Campaign Name`
* `Touchpoint Type`
* `Touchpoint Position`
* `Attribution % W-Shaped (*or most robust attribution model such as Full Path or Custom*)`
* `Revenue W-Shaped (*or most robust attribution model such as Full Path or Custom*)`
* `Touchpoint Date`

##### 5. Sort by Touchpoint Date > Ascending. {#pagelayoutinstructions-sortbytouchpointdate>ascending..1}

##### 6. Deselect New within the Buttons section. {#pagelayoutinstructions-deselectnewwithinthebuttonssection.}

##### 7. Click Save. {#pagelayoutinstructions-clicksave..2}

#### Accounts {#pagelayoutinstructions-accounts}

##### 1. Within your Build option, selectAccounts. {#pagelayoutinstructions-withinyourbuildoption-selectaccounts.}

##### 2. Click Page Layouts. {#pagelayoutinstructions-clickpagelayouts..4}

##### 3. Select the Page Layout you’d like to edit. {#pagelayoutinstructions-selectthepagelayoutyou’dliketoedit..2}

##### 4. Add theBizible Attribution Touchpoint Related List and click the wrench to add the following columns: {#pagelayoutinstructions-addthebizibleattributiontouchpointrelatedlistandclickthewrenchtoaddthefollowingcolumns-}

* `Attribution Touchpoint`
* `Marketing Channel`
* `Opportunity`
* `Ad Campaign Name`
* `Touchpoint Type`
* `Touchpoint Position`
* `Attribution % W-Shaped (*or most robust attribution model such as Full Path or Custom*)`
* `Revenue W-Shaped (*or most robust attribution model such as Full Path or Custom*)`
* `Touchpoint Date`

##### 5. Sort by Touchpoint Date > Ascending. {#pagelayoutinstructions-sortbytouchpointdate>ascending..2}

##### 6. Deselect New within the Buttons section. {#pagelayoutinstructions-deselectnewwithinthebuttonssection..1}

##### 7. Click Save. {#pagelayoutinstructions-clicksave..3}

`  
If you are leveraging Bizible's ABM feature, [please click here for additional page layout instructions](http://docs.marketo.com/x/agEgAQ)` `.` `  
`

