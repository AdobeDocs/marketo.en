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

### What's in this article? {#whats-in-this-article}

[Create Mobile Smart Lists](#create-mobile-smart-lists)  
[Create a People Performance Report](#create-a-people-performance-report)  
[Add Mobile Smart Lists as Columns](#add-mobile-smart-lists-as-columns)

#### Create Mobile Smart Lists {#create-mobile-smart-lists}

1. Go to **Marketing Activities**.

   ![](assets/ma.png)

1. Choose a program.

   ![](assets/two-1.png)

1. Under **New**, select **New Local Asset**.

   ![](assets/three-1.png)

1. Click **Smart List**.

   ![](assets/four-1.png)

1. Type in a name and click **Create**.

   ![](assets/five-1.png)

1. Find and drag the Opened Email filter into the canvas.

   ![](assets/six-1.png)

1. Set Email to **is any**.

   ![](assets/seven.png)

1. Click on **Add Constraint** and select **Platform**.

   ![](assets/eight.png)

   >[!TIP]
   >
   >We used the Opened Email filter in this example. You can also use the Clicked Email filter as it has the Platform constraint.

1. Set Platform to **iOS**.

   ![](assets/nine.png)

   >[!NOTE]
   >
   >At least one person must have opened one of your emails on an iOS device in order for Marketo's autosuggest to find it. If it does not come up, you can manually type it in and save.

   Now create a second smart list for the "Android" platform. Once that's done, move on to the next section.

#### Create a People Performance Report {#create-a-people-performance-report}

1. Under Marketing Activities, select the program that is housing your **iOS** and **Android** smart lists.

   ![](assets/ten.png)

1. Under **New**, select **New Local Asset**.

   ![](assets/eleven.png)

1. Click **Report**.

   ![](assets/twelve.png)

1. Set Type to **People Performance**.

   ![](assets/thirteen.png)

1. Click **Create**.

   ![](assets/fourteen.png)

   You're doing great! Now on to the next section.

#### Add Mobile Smart Lists as Columns {#add-mobile-smart-lists-as-columns}

1. In the report you just created, click **Setup**, then drag **Custom Columns** into the canvas.

   ![](assets/fifteen.png)

   >[!NOTE]
   >
   >By default the People Performance report is looking at the Last 7 days. You can change the timeframe by double-clicking on it.

1. Find and select the smart lists you created earlier and click **Apply**.

   ![](assets/sixteen.png)

1. Click **Report** to run the report and see your data.

   ![](assets/seventeen.png)

   Pretty cool, right? Nicely done!

