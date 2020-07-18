---
unique-page-id: 18874718
description: Creating a Campaign List View for Salesforce Campaigns - Bizible - Product Documentation
title: Creating a Campaign List View for Salesforce Campaigns
---

# Creating a Campaign List View for Salesforce Campaigns {#creating-a-campaign-list-view-for-salesforce-campaigns}

Creating a Campaign List View for Salesforce Campaigns - Bizible - Product Documentation

Learn how to create a List View for those campaigns that you want to sync with Bizible Touchpoints.

The Campaign list view that can be created allows you to have a 'go-to' location to see and manage the 'Type' and 'Enable Bizible Touchpoints' fields to ensure that each of your Salesforce campaigns that inform your offline marketing channels are setup properly.

1. Head to Campaigns tab in Salesforce and create a new list view
1. Name the view 'Campaigns to sync with Bizible'
1. We want this list to only show those campaigns that we want to sync with Bizible so we need a couple filters:

    * **Type** [EQUALS] 'All the Campaign Types that we have mapped to your offline channels'. Refer to your Implementation Plan or the Offline Channels tab in Bizible ([apps.bizible.com](http://apps.bizible.com) -> My Account -> Settings -> Offline Channels). You can select the Types you want (those that are mapped to an offline marketing channel) via the magnifying glass icon.

        * Choose 3 Types max for each filter. There is a limit of characters you can have in a filter field. Start with 3 Types per filter and add additional rows of ‘Type’ filters if necessary.

    * **Created Date** [GREATER OR EQUAL] your Bizible start date. You can find your start date in the ROI dashboard within the Bizible App. Just select 'Since Creation Date' in the date range of the dash and it will show your start date.
    * **&#42;Record Type&#42;** - In order to make edits in the List View, you need to add a filter for Record Type. Each campaign record you may need to edit needs to be the same Record Type.

1. Edit your Selected fields to show in the list view. The complete setup of the list view should look like the example below:

   This view allows you see your campaigns and edit the ‘Type’ and 'Enable Bizible Touchpoints' fields if necessary. As you create new campaigns that should be synced with Bizible, they will surface in this view and you can manage all of the settings for those campaigns right from within the list.  
  
   In order to make inline edits from the List View you need to make sure the following is also true within your Salesforce setup:

    * Setup > User Interface > Enable Inline Editing
    * Also need enable enhanced lists checked (right under the box for inline editing):
    * Make sure to have permissions to the fields.

   [https://help.salesforce.com/articleView?id=000003911&language=en_US&type=1](http://help.salesforce.com/articleView?id=000003911&language=en_US&type=1)

