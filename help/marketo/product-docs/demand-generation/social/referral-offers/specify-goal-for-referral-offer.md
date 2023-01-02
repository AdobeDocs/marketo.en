---
unique-page-id: 2359791
description: Specify Goal for Referral Offer - Marketo Docs - Product Documentation
title: Specify Goal for Referral Offer
exl-id: 9869eb66-53df-4ea8-903f-e6650add8da2
---
# Specify Goal for Referral Offer {#specify-goal-for-referral-offer}

When you [create a referral offer](/help/marketo/product-docs/demand-generation/social/referral-offers/create-a-referral-offer.md), you need to define the fulfillment goal. The goal can be defined by person activity on the web page, such as page visits or sign-ups. You can even use a [custom JavaScript event](/help/marketo/product-docs/demand-generation/social/social-functions/conversion-script-for-custom-events.md).

Alternatively, you can use a smart list trigger in Marketo to wait for any milestone, such as an opportunity being created for the referred person.

Example goals:

* 10 referred visits
* 5 referred sign-ups
* 1 referred opportunity created
* 2 referred ecommerce purchases
* 5 referred webinar attendees

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/ma.png)

1. Select the referral offer, and click **[!UICONTROL Edit Draft]**.

   ![](assets/image2014-9-19-15-3a6-3a35.png)

1. In the referral offer editor, go to **[!UICONTROL App Settings]** > **[!UICONTROL Offer Details]**.

   ![](assets/image2014-9-19-15-3a6-3a44.png)

1. Under **[!UICONTROL Settings]**, choose an event type from the **[!UICONTROL Fulfillment Goal]** drop-down.

   ![](assets/image2014-9-19-15-3a6-3a56.png)

>[!TIP]
>
>If you plan to use the **[!UICONTROL Give Credit to Referrer]** flow step, you must select **[!UICONTROL Smart List Trigger]** as the fulfillment goal type here.

* **[!UICONTROL Referred Visits]**: Offer participants get credit for each visit from a friend to the page hosting your offer.
* **[!UICONTROL Referred Sign-Ups]**: Offer participants get credit for each friend who signs up for the offer.
* **[!UICONTROL Smart List Trigger]**: Offer participants get credit for each friend who meets the conditions of a [smart list](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists.md) trigger in a [smart campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/understanding-smart-campaigns.md). For example, you can use a trigger that fires when a referred prospect signs up for a webinar.

* **[!UICONTROL Custom JavaScript Event]**: Offer participants get credit for each friend who triggers a defined JavaScript event on your page. See [Conversion Script for Custom Events](/help/marketo/product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md).

>[!NOTE]
>
>There are new filters and triggers available in smart campaigns to monitor social activity. See [use triggers and filters for social activities](/help/marketo/product-docs/demand-generation/social/social-functions/triggers-and-filters-for-social-activities.md).

>[!MORELIKETHIS]
>
>Next, you can [select the sign-up and fulfillment emails](/help/marketo/product-docs/demand-generation/social/referral-offers/send-referral-offer-fulfillment-email.md) to send from your referral offer.
