---
description: Filtering Email Bot Activity - Marketo Docs - Product Documentation
title: Filtering Email Bot Activity
exl-id: 70c97159-72bf-46e5-b29b-247615d0fa80
---
# Filtering Email Bot Activity {#filtering-email-bot-activity}

Sometimes, email bot activity can erroneously inflate your email opens and clicks data. Here's how to fix that.

>[!NOTE]
>
>Using the [IAB/ABC International Spiders and Bots List](https://www.iab.com/guidelines/iab-abc-international-spiders-bots-list/), all open/click activity with an IP or User agent that matches anything from that list will be identified as bot activity and not get logged in Marketo.

1. Click **Admin**.

   ![](assets/filtering-email-bot-activity-1.png)

1. Click **Email**.

   ![](assets/filtering-email-bot-activity-2.png)

1. Click the **Bot Activity** tab.

   ![](assets/filtering-email-bot-activity-3.png)

1. Click the slider to enable **Filter Bot Activity**.

   ![](assets/filtering-email-bot-activity-4.png)

>[!NOTE]
>
>You can separately choose whether or not to have bot activity logged. If you choose not to, you may see a drop in email opens and clicks as false numbers are filtered out.

**OPTIONAL STEP**: To disable the feature, simply deselect the slider. If you disable, the "Bot Activity in last 90 days" data does **not** reset.

>[!TIP]
>
>Leverage bot activity data in Smart Lists via "Is Bot Activity" boolean (yes/no), or in applicable filter/trigger constraints.
