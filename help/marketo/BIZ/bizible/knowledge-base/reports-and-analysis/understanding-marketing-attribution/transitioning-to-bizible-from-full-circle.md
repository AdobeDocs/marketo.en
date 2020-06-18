---
unique-page-id: 18874535
description: Transitioning to Bizible from Full Circle - Bizible - Product Documentation
title: Transitioning to Bizible from Full Circle
---

# Transitioning to Bizible from Full Circle {#transitioning-to-bizible-from-full-circle}

Transitioning to Bizible from Full Circle - Bizible - Product Documentation

Making the move from Full Circle to Bizible? You’re not alone. Here are the biggest considerations to keep in mind and the lessons we’ve learned from other customers who’ve made the switch.

#### Campaign-Based Tracking vs. Multi-Source Tracking {#transitioningtobiziblefromfullcircle-campaign-basedtrackingvs-multi-sourcetracking}

All interactions in Full Circle are tracked through CRM campaign membership. With Bizible, the purchasing journey is compiled through a combination of our JavaScript, CRM campaign membership, and CRM activity records. Making the mental shift away from “all interaction must be tracked in a CRM campaign in order for our attribution reporting to function” to “only this subset of interactions needs to be tracked in a CRM campaign for our attribution reporting to function” can be tricky.

Generally speaking, here’s how Bizible creates touchpoint records for the major types of interactions:

* Form fills on your site(s): Bizible Javascript
* Page views on your site(s): Created by Bizible Javascript only if this page view drove a designated CRM milestone (such as Lead or Opportunity Creation)
* Offline interactions such as conferences or tradeshows: CRM campaign membership
* Digital interactions that happen anywhere on the internet that isn’t your site (such as a webinar hosted on a third-party site that generates a list upload): CRM campaign membership
* Interactions with your Sales team: CRM Activity records

If you’re comfortable with your CRM campaign management and prefer to keep existing processes in place, that’s fine. It doesn’t hurt Bizible to continue tracking all interactions in CRM campaigns. You can design logic that only creates touchpoints from a desired subset of campaigns to avoid touchpoint duplication.

#### Visibility vs. Attribution {#transitioningtobiziblefromfullcircle-visibilityvs-attribution}

With most Full Circle setups, you see every single interaction a person has with your marketing or sales efforts. Page views, repeated page visits, membership in duplicate and triplicate campaigns—Full Circle surfaces all of those. If you view a page 300 times, Full Circle creates 300 duplicate campaigns and gives you a membership in each of them. Bizible does not, and that was a conscious design decision on our part.

Bizible’s goal is to provide you with an attribution story that surfaces meaningful interactions and distributes weight among the most impactful touchpoints appropriately. For example, the Bizible framework won’t surface page views (without form fills) as routine touchpoints. A standalone page view isn’t likely to have an impact on driving a purchasing journey forward, but we will create a touchpoint if it’s the most recent interaction before a designated CRM milestone (such as Lead or Opportunity Creation). We don’t want to show you everything. We want to show you the stuff that matters, from an attribution standpoint.

Work with your Bizible rep to set appropriate expectations around what data will no longer be available to your team.

#### Pre-Bizible Data {#transitioningtobiziblefromfullcircle-pre-bizibledata}

Bizible’s standard recommendation is to start reporting and data gathering from the day you deployed the Bizible JavaScript forward, and that goes double for former Full Circle customers. Think about the two sections above: You’re used to seeing a higher quantity of data, and you’re used to all of that data coming from CRM campaign membership. If you choose to include some or all of that data from prior to your Bizible implementation, you won’t be comparing apples to apples across the JavaScript implementation date.

That said, we certainly understand that many customers need this historic data; especially if you have a longer sales cycle (greater than 90 days), you may want to give Bizible visibility into pre-Bizible data. Discuss this carefully with your Bizible rep, and always keep in mind that skew across the implementation date can lead to the appearance of improvements or declines in channel performance or engagement, as well as other potentially incorrect inferences.

#### In Summary {#transitioningtobiziblefromfullcircle-insummary}

You’re in good company, and we’ve helped numerous other customers handle these changes. Work with your Bizible rep to understand the impacts above, as well as any other concerns you may have.

