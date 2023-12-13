---
description: Use Vibes SMS Messages in Smart List Triggers and Filters - Marketo Docs - Product Documentation
title: Use Vibes SMS Messages in Smart List Triggers and Filters
hide: yes
hidefromtoc: yes
feature: Mobile Marketing
---
# Use Vibes SMS Messages in Smart List Triggers and Filters {#use-vibes-sms-messages-in-smart-list-triggers-and-filters}

After you [create a Vibes SMS message](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/create-a-vibes-sms-message.md){target="_blank"}, you'll want to use Smart List triggers and filters within a Smart Campaign to get the benefits. Here's how.

1. In My Marketo, click **Marketing Activities**.

   ![](assets/use-sms-options-in-smart-list-triggers-and-filters-1.png)

1. Choose a Smart Campaign in which you want to use your SMS assets. Drag over a trigger. In this example we're using **Fills Out Form**.

   ![](assets/fills-out-form-pull-over.jpg)

## SMS Triggers {#sms-triggers}

There are other SMS triggers available. The SMS triggers appear only if Vibes service is enabled.

SEND A SMS MESSAGE:

* Marketing Activities > choose New Smart Campaign
  * Smart List > Choose Vibes List filter & correct logic > Vibes list: Choose list from drop-down (mobile database list that syncs from Vibes platform)  
    * Can refine segmentation & utilize SMS and email filters & triggers within one campaign 
    * Vibes Filters: Subscribed to Vibes List vs. Member of Vibes List - logic is consistent with email 
       * Subscribed to Vibes List - participants who have ever subscribed to that Vibes list even if they are now unsubscribed.  - mostly utilized for cross channel marketing efforts 
          * Note: a SMS message will not send to anyone unsubscribed if they are not in the Vibes Mobile Database list  
       * Member of Vibes List - active, confirmed subscriber 
       * Added to List - Vibes lists will not populate with this filter; this is for Marketo lists  

![](assets/new-sms-search2.png)

Here are a few examples:

The **SMS Message Bounces** trigger initiates a flow, such as sending an email, when an SMS message bounces.

![](assets/sms-message-bounces-real.jpg)

The **Subscribes to Vibes List** trigger initiates a flow when a person subscribes.

![](assets/subscribes-to-vibes-list-real.jpg)

The **Clicks Link in SMS Message** trigger initiates a flow when a person clicks on a link in the SMS message.

![](assets/clicks-link-in-sms-message.jpg)

## SMS Filters {#sms-filters}

You can also use Vibes filters in smart lists. The **Subscribed to Vibes List** filter finds anyone who has *ever* subscribed to Vibes. This includes both unsubscribed and deleted people, even though deleted people are omitted from the flow. This filter is best suited for reporting.

![](assets/subscribed-to-vibes-list-filter-real.jpg)

By contrast, the **Member of Vibes List** filter finds _anyone_ currently subscribed to Vibes and is most suited for use in Smart Campaigns or lists.

![](assets/image001.png)

>[!NOTE]
>
>All SMS filters includes the **Date of Activity** constraint by default.

After you set up Vibes triggers and filters in your smart list, you can [define the flow](/help/marketo/product-docs/mobile-marketing/vibes-sms-messages/add-a-flow-step-for-sms.md).

>[!MORELIKETHIS]
>
>* [Define Smart List for Smart Campaign | Trigger](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/define-smart-list-for-smart-campaign-trigger.md)
>* [Find and Add Filters to a Smart List](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/find-and-add-filters-to-a-smart-list.md)
