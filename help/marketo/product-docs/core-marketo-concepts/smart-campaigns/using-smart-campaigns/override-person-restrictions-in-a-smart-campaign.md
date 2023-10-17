---
unique-page-id: 1147066
description: Override Person Restrictions in a Smart Campaign - Marketo Docs - Product Documentation
title: Override Person Restrictions in a Smart Campaign
exl-id: 45ff3e36-01fd-42ea-ba74-efd98867a58a
feature: Smart Campaigns
---
# Override Person Restrictions in a Smart Campaign {#override-person-restrictions-in-a-smart-campaign}

Marketo Engage allows you to set the maximum number of people that can qualify for a Smart Campaign; this helps you avoid accidentally emailing your whole database. If you want to _override_ this limit, here's how.

>[!PREREQUISITES]
>
>Be sure to [enable person restrictions for Smart Campaigns](/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md){target="_blank"} in Marketo Admin.

1. In Marketing Activities, go to your Smart Campaign and click **Schedule**.

   ![](assets/override-person-restrictions-in-a-smart-campaign-1.png)

1. In Smart Campaign Settings, click **[!UICONTROL Edit]**.

   ![](assets/override-person-restrictions-in-a-smart-campaign-2.png)

   >[!NOTE]
   >
   >The default limit is the one set in Admin.

1. Enter a new limit and then click **[!UICONTROL Save]**.

   ![](assets/override-person-restrictions-in-a-smart-campaign-3.png)

   The Smart Campaign will not run if the number of people who qualify exceed the set limit.

   >[!CAUTION]
   >
   >Be careful with this feature so that you do not accidentally include too many people.
