---
unique-page-id: 2951220
description: Build a People Performance Report with Mobile Platform Columns - Marketo Docs - Product Documentation
title: Build a People Performance Report with Mobile Platform Columns
---

# Build a People Performance Report with Mobile Platform Columns {#build-a-people-performance-report-with-mobile-platform-columns}

Build a People Performance Report with Mobile Platform Columns - Marketo Docs - Product Documentation

Follow these steps to create a People Performance Report with mobile platform (iOS/Android) columns.

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

### What's in this article? {#what-s-in-this-article}

[Create Mobile Smart Lists](#buildapeopleperformancereportwithmobileplatformcolumns-createmobilesmartlists)  
[Create a People Performance Report](#buildapeopleperformancereportwithmobileplatformcolumns-createapeopleperformancereport)  
[Add Mobile Smart Lists as Columns](#buildapeopleperformancereportwithmobileplatformcolumns-addmobilesmartlistsascolumns)

#### Create Mobile Smart Lists {#buildapeopleperformancereportwithmobileplatformcolumns-createmobilesmartlists}

##### 1. Go to Marketing Activities. {#buildapeopleperformancereportwithmobileplatformcolumns-gotomarketingactivities.}

![](assets/ma.png)

##### 2. Choose a program. {#buildapeopleperformancereportwithmobileplatformcolumns-chooseaprogram.}

![](assets/two-1.png)

##### 3. Under New, select New Local Asset. {#buildapeopleperformancereportwithmobileplatformcolumns-undernew-selectnewlocalasset.}

![](assets/three-1.png)

##### 4. Click Smart List. {#buildapeopleperformancereportwithmobileplatformcolumns-clicksmartlist.}

![](assets/four-1.png)

##### 5. Type in a name and click Create. {#buildapeopleperformancereportwithmobileplatformcolumns-typeinanameandclickcreate.}

![](assets/five-1.png)

##### 6. Find and drag the Opened Email filter into the canvas. {#buildapeopleperformancereportwithmobileplatformcolumns-findanddragtheopenedemailfilterintothecanvas.}

![](assets/six-1.png)

##### 7. Set Email to is any. {#buildapeopleperformancereportwithmobileplatformcolumns-setemailtoisany.}

![](assets/seven.png)

##### 8. Click on Add Constraint and select Platform. {#buildapeopleperformancereportwithmobileplatformcolumns-clickonaddconstraintandselectplatform.}

![](assets/eight.png)

>[!TIP]
>
>We used the Opened Email filter in this example. You can also use the Clicked Email filter as it has the Platform constraint.

##### 9. Set Platform to iOS. {#buildapeopleperformancereportwithmobileplatformcolumns-setplatformtoios.}

![](assets/nine.png)

>[!NOTE]
>
>At least one person must have opened one of your emails on an iOS device in order for Marketo's autosuggest to find it. If it does not come up, you can manually type it in and save.

Now create a second smart list for the "Android" platform. Once that's done, move on to the next section.

#### Create a People Performance Report {#buildapeopleperformancereportwithmobileplatformcolumns-createapeopleperformancereport}

##### 1. Under Marketing Activities, select the program that is housing your iOS and Android smart lists. {#buildapeopleperformancereportwithmobileplatformcolumns-undermarketingactivities-selecttheprogramthatishousingyouriosandandroidsmartlists.}

![](assets/ten.png)

##### 2. Under New, select New Local Asset. {#buildapeopleperformancereportwithmobileplatformcolumns-undernew-selectnewlocalasset..1}

![](assets/eleven.png)

##### 3. Click Report. {#buildapeopleperformancereportwithmobileplatformcolumns-clickreport.}

![](assets/twelve.png)

##### 4. Set Type to People Performance. {#buildapeopleperformancereportwithmobileplatformcolumns-settypetopeopleperformance.}

![](assets/thirteen.png)

##### 5. Click Create. {#buildapeopleperformancereportwithmobileplatformcolumns-clickcreate.}

![](assets/fourteen.png)

You're doing great! Now on to the next section.

#### Add Mobile Smart Lists as Columns {#buildapeopleperformancereportwithmobileplatformcolumns-addmobilesmartlistsascolumns}

##### 1. In the report you just created, click Setup, then drag Custom Columns into the canvas. {#buildapeopleperformancereportwithmobileplatformcolumns-inthereportyoujustcreated-clicksetup-thendragcustomcolumnsintothecanvas.}

![](assets/fifteen.png)

>[!NOTE]
>
>By default the People Performance report is looking at the Last 7 days. You can change the timeframe by double-clicking on it.

##### 2. Find and select the smart lists you created earlier and click Apply. {#buildapeopleperformancereportwithmobileplatformcolumns-findandselectthesmartlistsyoucreatedearlierandclickapply.}

![](assets/sixteen.png)

##### 3. Click Report to run the report and see your data. {#buildapeopleperformancereportwithmobileplatformcolumns-clickreporttorunthereportandseeyourdata.}

![](assets/seventeen.png)

Pretty cool, right? Nicely done!
