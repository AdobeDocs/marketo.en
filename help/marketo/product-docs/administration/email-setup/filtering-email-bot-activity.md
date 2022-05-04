---
description: Filtering Email Bot Activity - Marketo Docs - Product Documentation
title: Filtering Email Bot Activity
exl-id: 70c97159-72bf-46e5-b29b-247615d0fa80
---
# Filtering Email Bot Activity {#filtering-email-bot-activity}

Sometimes, email bot activity can erroneously inflate your email opens and clicks data. Follow the steps below to fix that.

We use three separate methods to confirm bot activity:

* Match with [Interactive Advertisng Bureau bot list](https://www.iab.com/guidelines/iab-abc-international-spiders-bots-list/){target="_blank"}: Activities that match with anything on the IAB UA/IP (User Agent/IP address) list will be marked as bots.
* Match with hidden link UA/IPs: We add a hidden link to all emails and capture UA/IP clicks coming from them. Activities that match with these UA/IPs will be marked as bots.
* Match with proximity pattern: When more than two activities happen at the same time (under two seconds), they're identified as bots.

Against email link click and email open activity, new attribtues will be populated with the values below:

* Activities that are identified as bots will have "Bot Activity" as "True" and "Bot Activity Pattern" as the identified pattern/method
* Activities that are identified as not bots will have "Bot Activity" as "False" and "Bot Activity Pattern" as "N/A"
* Activities that happened before we introduced these attributes will have "Bot Activity" as " " (empty) and "Bot Activity Pattern" as " " (empty)

1. Click **Admin**.

   ![](assets/filtering-email-bot-activity-1.png)

1. Click **Email**.

   ![](assets/filtering-email-bot-activity-2.png)

1. Click the **Bot Activity** tab.

   ![](assets/filtering-email-bot-activity-3.png)

1. Click the **Enable Bot Activity Identification** slider to activate.

   ![](assets/filtering-email-bot-activity-4.png)

>[!NOTE]
>
>You can separately choose whether or not to have bot activity logged. If you choose not to, you may see a drop in email opens and clicks as false numbers are filtered out.

**OPTIONAL STEP**: To disable the feature, simply deselect the slider. If you disable, the data does **not** reset.

>[!TIP]
>
>Leverage bot activity data in Smart Lists via "Is Bot Activity" boolean (yes/no) and "Bot Activity Pattern" in the "Clicked Link in Email" and "Open Email" filters, and "Clicks Link in Email" and "Opens Email" triggers.
