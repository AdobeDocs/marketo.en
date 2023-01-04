---
unique-page-id: 2951220
description: Build a People Performance Report with Mobile Platform Columns - Marketo Docs - Product Documentation
title: Build a People Performance Report with Mobile Platform Columns
exl-id: 93fb6cb4-a6ca-4b35-b8bf-c6657eb9343b
---
# Build a People Performance Report with Mobile Platform Columns {#build-a-people-performance-report-with-mobile-platform-columns}

Follow these steps to create a People Performance Report with mobile platform (iOS/Android) columns.

## Create Mobile Smart Lists {#create-mobile-smart-lists}

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/ma.png)

1. Choose a program.

   ![](assets/two-1.png)

1. Under **[!UICONTROL New]**, select **[!UICONTROL New Local Asset]**.

   ![](assets/three-1.png)

1. Click **[!UICONTROL Smart List]**.

   ![](assets/four-1.png)

1. Type in a name and click **[!UICONTROL Create]**.

   ![](assets/five-1.png)

1. Find and drag the [!UICONTROL Opened Email] filter into the canvas.

   ![](assets/six-1.png)

1. Set Email to **[!UICONTROL is any]**.

   ![](assets/seven.png)

1. Click on **[!UICONTROL Add Constraint]** and select **[!UICONTROL Platform]**.

   ![](assets/eight.png)

   >[!TIP]
   >
   >We used the [!UICONTROL Opened Email] filter in this example. You can also use the [!UICONTROL Clicked Email] filter as it has the Platform constraint.

1. Set [!UICONTROL Platform] to **[!UICONTROL iOS]**.

   ![](assets/nine.png)

   >[!NOTE]
   >
   >At least one person must have opened one of your emails on an iOS device in order for Marketo's autosuggest to find it. If it does not come up, you can manually type it in and save.

   Now create a second smart list for the "Android" platform. Once that's done, move on to the next section.

## Create a People Performance Report {#create-a-people-performance-report}

1. Under Marketing Activities, select the program that is housing your **[!UICONTROL iOS]** and **[!UICONTROL Android]** smart lists.

   ![](assets/ten.png)

1. Under **[!UICONTROL New]**, select **[!UICONTROL New Local Asset]**.

   ![](assets/eleven.png)

1. Click **[!UICONTROL Report]**.

   ![](assets/twelve.png)

1. Set Type to **[!UICONTROL People Performance]**.

   ![](assets/thirteen.png)

1. Click **[!UICONTROL Create]**.

   ![](assets/fourteen.png)

   You're doing great! Now on to the next section.

## Add Mobile Smart Lists as Columns {#add-mobile-smart-lists-as-columns}

1. In the report you just created, click **[!UICONTROL Setup]**, then drag **[!UICONTROL Custom Columns]** into the canvas.

   ![](assets/fifteen.png)

   >[!NOTE]
   >
   >By default the People Performance report is looking at the Last 7 days. You can change the timeframe by double-clicking on it.

1. Find and select the smart lists you created earlier and click **[!UICONTROL Apply]**.

   ![](assets/sixteen.png)

1. Click **[!UICONTROL Report]** to run the report and see your data.

   ![](assets/seventeen.png)

   Pretty cool, right? Nicely done!
