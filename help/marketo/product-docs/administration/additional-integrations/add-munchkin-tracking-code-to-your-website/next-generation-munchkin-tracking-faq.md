---
unique-page-id: 10096583
description: "Next Generation [!DNL Munchkin] Tracking FAQ - Marketo Docs - Product Documentation"
title: "Next Generation [!DNL Munchkin] Tracking FAQ"
exl-id: 283189ac-c817-479a-b896-91233980608c
feature: "Administration, Munchkin Tracking Code"
---
# Next Generation [!DNL Munchkin] Tracking FAQ {#next-generation-munchkin-tracking-faq}

We are excited to announce that we will soon begin a phased rollout of our next-generation web tracking technology.

Here are the most important things to know:

* We are removing the "Is Anonymous" Smart List filter with our Q1 release (already done)
* We are increasing the number of web events (Visit Web Page, Clicked Link on Web Page) we can ingest
* Your [!DNL Munchkin] code will not change, so no updates on your website are required

## When will my Marketo subscription be on [!DNL Munchkin] V2? {#when-will-my-marketo-subscription-be-on-munchkin-v}

We don't have an exact date yet, but please check back here for updates.

## Will I need to make any changes to my [!DNL Munchkin] tracking on my website? {#will-i-need-to-make-any-changes-to-my-munchkin-tracking-on-my-website}

No. The [!DNL Munchkin] tracking code remains the same. No changes need to be made to your website.

>[!NOTE]
>
>This change does not affect Web Personalization (Real-Time Personalization). It continues to identify anonymous and known web visitors and personalize content in real time to these visitors.

## Why did Marketo remove the "Is Anonymous" filter from Smart Lists? {#why-did-marketo-remove-the-is-anonymous-filter-from-smart-lists}

We changed how anonymous people interact with Smart Campaigns. Before, they flowed through a smart campaign, just like known people. The "Is Anonymous" filter was used to specify that only known or only anonymous people flow through the campaign.

With [!DNL Munchkin] V2, we will continue to track all anonymous activities; however, you are no longer able to apply filters to anonymous people. At the point of conversion (when the person becomes known in Marketo), all activities that occurred when the person was anonymous are appended to the person activity log and at this time they flow through the campaigns they qualify for.

If you are already using this filter in a Smart List (for example, in a Smart Campaign or a Report), it is not automatically removed from the Smart List. See below for more details.

>[!NOTE]
>
>**Trigger**: Visits Web Page, Web Page is Pricing Page  
>**Flow**: Change Score +10 and Interesting Moment
>**Web**: Viewed Pricing Page
>
>With [!DNL Munchkin] V2, if an anonymous person visits the pricing page, she does not enter the campaign immediately. At the time the anonymous person becomes known, we'll run this campaign on her. She will:
>
>* Get a score of 10
>
>* Have the Web Page activity set to the right date (when she actually visited)
>
>* Have an Interesting Moment logged for her (with the date she actually visited the page, not when she became known)
>
>* Have a "New Person" activity logged, as it is today

## What happens to my Smart Lists that already have the "Is Anonymous" filter? {#what-happens-to-my-smart-lists-that-already-have-the-is-anonymous-filter}

After our Winter '16 Release, if you have old Smart Campaigns with a Smart List that has the "Is Anonymous" filter in it, one of two things will happen:

1. If the Smart List has the filter "Is Anonymous = False", then nothing will happen. We'll just ignore it. 
1. If the Smart List has the filter "Is Anonymous = True", then this campaign will fail and you'll be sent a notification.

## I've been using Marketo for a while. How do I know which of my campaigns use the "Is Anonymous" filter? {#ive-been-using-marketo-for-a-while-how-do-i-know-which-of-my-campaigns-use-the-is-anonymous-filter}

Before we made this change, we sent out several weekly notifications to your Notifications inbox with a list of Smart Lists, Smart Campaigns and Reports that use the "Is Anonymous" filter. These can help you identify where you are currently using this filter.

Please review them and identify where you have "Is Anonymous" set to True, as these are the campaigns that are affected. Most times, customers use this setting for some kind of scoring. Please see the example above to understand how these campaigns will work now.

## I'd like more detailed documentation. Where can I find it? {#id-like-more-detailed-documentation-where-can-i-find-it}

Check out these links:

[Anonymous Lead Upgrades Overview](https://nation.marketo.com/docs/DOC-2937){target="_blank"}

[Anonymous Lead Upgrades - Changes Inside Marketo UI](https://nation.marketo.com/docs/DOC-2938){target="_blank"}

[Anonymous Lead Upgrades - Customer Action Needed](https://nation.marketo.com/docs/DOC-2939){target="_blank"}

[Anonymous Lead Upgrades - Analytics Reports](https://nation.marketo.com/docs/DOC-2940){target="_blank"}

[Anonymous Lead Upgrades - Release Schedule](https://nation.marketo.com/docs/DOC-2961){target="_blank"}

[Anonymous Lead Upgrades - Under The Hood](https://nation.marketo.com/docs/DOC-2962){target="_blank"}

[Anonymous Lead Promotion to Known Lead - [!DNL Munchkin] V2 Behavior](https://nation.marketo.com/docs/DOC-2963){target="_blank"}

## I have more questions! How do I get them answered? {#i-have-more-questions-how-do-i-get-them-answered}

Please reach out on the [community](https://nation.marketo.com/){target="_blank"}. You can also contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}. They'll be happy to answer your questions.
