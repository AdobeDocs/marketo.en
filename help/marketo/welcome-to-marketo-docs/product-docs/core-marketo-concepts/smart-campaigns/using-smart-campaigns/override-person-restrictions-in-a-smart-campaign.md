---
unique-page-id: 1147066
description: Override Person Restrictions in a Smart Campaign - Marketo Docs - Product Documentation
title: Override Person Restrictions in a Smart Campaign
---

# Override Person Restrictions in a Smart Campaign {#override-person-restrictions-in-a-smart-campaign}

Override Person Restrictions in a Smart Campaign - Marketo Docs - Product Documentation

Marketo allows you to set the maximum**number of people that can qualify for a smart campaign; this helps you avoid accidentally emailing your whole database. If you want to *override* this limit, here's how.

>[!NOTE]
>
>**FYI**
>
>Marketo is now standardizing language across all subscriptions, so you may see lead/leads in your subscription and person/people in docs.marketo.com. These terms mean the same thing; it does not affect article instructions. There are some other changes, too. [Learn more](http://docs.marketo.com/display/DOCS/Updates+to+Marketo+Terminology).

>[!NOTE]
>
>**Prerequisites**
>
>Be sure to [enable person restrictions for smart campaigns](../../../../../welcome-to-marketo-docs/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md) in Marketo Admin.

1. In Marketing Activities, go to your** **smart campaign and click **Schedule**.

   ![](assets/one.png)

   `In Smart Campaign Settings, click` **Edit** `.`
   ![](assets/two.png)

   >[!NOTE]
   >
   >The default limit is the one set in Admin.

1. Enter a new `limit`and then click **Save.**

   ![](assets/three.png)

   The smart campaign will not run if the number of people who qualify exceed the set limit.

   >[!CAUTION]
   >
   >Be careful with this feature so that you do not accidentally include too many people.

