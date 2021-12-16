---
description: Release Notes - October 2021 - Marketo Docs - Product Documentation
title: Release Notes - October 2021
exl-id: 6b363c9b-7abe-4576-a362-0ad5cf515c02
---
# Release Notes: October 2021 {#release-notes-oct-21}

The following features are included in the October '21 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

**_Quarterly Releases_**

The following features will start to be released on **October 22, 2021**, with a phased rollout of every feature over the following week (unless specified otherwise).

## AI-Driven Innovation {#ai-driven-innovation}

* **Predictive Audiences Enhancements**: You now have more visibility into top behaviors that are influencing AI predictions for the AI-powered predictive models used in event and email programs. You can review the campaign member behaviors that result in higher event registrations and attendance, as well as what leads to unsubscribes. AI-powered lookalike models can now be used in all program types in Marketo Engage.

## Next-generation Experience {#next-gen-experience}

* **Choose Your Own Experience**: Easily switch to your preferred experience with the new toggle while working on Marketo Engage form details or landing page list view without losing context, asset changes, or preferences. Additionally, the new landing page list view enhances your experience with new filters and the ability to perform mass actions.

* **Search Efficiently**: Accessibility improvements to global search include updated keyboard navigation and label descriptions, a new scroll feature for results, and more visible applied filters.

* **Monitor Tasks**: Monitor the status of tasks running in the background of the new experience via the new task notification tray in the global navigation bar. The tray captures notifications for tasks initiated from the new experience view of form details and landing page list, including changing status on landing pages and general mass actions using the new experience.

## Experience Automation {#experience-automation}

* **Submit Form API Program Member Custom Field Support**: The Submit Form API endpoint has been upgraded to support Program Member Custom Fields, allowing custom form integrations to collect program-specific data.

**_Releasing Throughout the Quarter_**

The following features are on a non-quarterly cycle and will be released throughout the coming months.

* **Native Adobe Experience Platform Connector for Sharing Audiences to Marketo Engage**: Enable multi-channel campaign orchestration in Marketo Engage for audience segments created in Adobe Experience Platform via a native destination connector. The connector uses email addresses or ECID to match Adobe Experience Platform profiles to Marketo Engage person records resulting in segment sharing between applications. Marketo Engage static lists are automatically populated which enables marketers to reach target audiences with highly personalized messaging or initiate workflows. Activate people audiences leveraging their account and opportunity context, and a more complete real-time unified profile in Experience Platform.

* **Adobe Experience Platform Marketo Data Source Connector**: Users of both Adobe Experience Platform and Marketo Engage will be able to utilize the Marketo Source Connector in bringing data from Marketo to AEP. You'll be able to stream data (and its changes) from Marketo within AEP to keep data consistent between the two products. The Marketo Connector can be seen via the Sources catalog, listed under "Adobe Applications."  

## Sales Insight {#sales-insight}

![(star)](assets/yellow-star.png)

**Sales Insight for Microsoft Dynamics 365 Sales**

* **Best Bets Enhancements**: The Best Bets tab in Sales Insight provides sales with a real-time view of the hottest contacts and leads prioritized by quality and urgency. We added the ability for sales reps to take actions, such as: review a person’s score, send an email, or add prospects to designated Marketo Engage campaigns directly from the Best Bets page, increasing efficiency and speeding up response time.

* **New Email, Web Activity, Anonymous Web Activity Dashboards**: We added the new sales dashboards to inform sellers about their leads and contacts’ most recent email and web activities. With new filtering capability, the dashboards now provide insight into email opens, clicks, and web page visits for the complete list of accounts or a specific account. Marketo Engage tracks all web activity and provides sales with critical information, turning anonymous traffic into leads. Sellers are enabled to personalize engagement and convert leads to sales faster because they're better informed about lead behaviors and are acting based on the relevance of all the touchpoints.

**Sales Insight for Salesforce**

* **Account and Opportunity-level Best Bets**: Sales Insight now offers the ability for sales reps to review Best Bets for all contacts on the account or opportunity they own, even when the contact is assigned to a different team member. This gives account and opportunity owners complete visibility into the activities of relevant contacts and helps them act based on a more holistic view of the account or opportunity.

## Sales Connect {#sales-connect}

![(star)](assets/yellow-star.png)

* **Enhanced Sales Activity Insights**: A new email reply tracking activity, Sales Email Replied, tracks recipients' interactions with an email which is automatically synchronized with Marketo Engage. Additionally, the Source attribute has been updated from “Tout” to “Sales App.” This activity can be exported and reported through the Marketo Engage REST API or Bulk Export and is available on filters and triggers as additional constraints for smart lists, expanding personalization options in Smart Campaigns.

* **Streamlined User Experience**: This update introduces new fonts, colors, buttons, and modals for Sales Connect that are based on the Adobe Spectrum design system. With these updates, we are delivering a more efficient experience, where sellers can focus on what's needed, when it's needed.

## Bizible {#bizible}

![](assets/yellow-star.png)

* **Bizible Integration with Adobe Privacy Service (GA)**: Bizible integration with the Adobe Privacy Service centralizes compliance with critical data privacy regulations, such as GDPR (General Data Privacy Regulation) or CCPA (California Consumer Privacy Act) across Adobe Experience Cloud applications. You can now take advantage of this service and manage all privacy requests centrally through Adobe’s Privacy Service so that change requests coming into Bizible, and other Adobe products, are reflected across applications.

## Announcements {#announcements}

* **Associate Lead Deprecation/Munchkin Beta 161 Update**: On September 7th, 2021, version 161 of Munchkin began rolling out to 10% of subscriptions with Munchkin Beta enabled, followed by 50% on September 16th, and 100% on September 30th. This change affects Marketo Engage landing pages and the version of the file munchkin-beta.js served to external landing pages which are loaded from subscriptions that the recent version has been rolled out to. This version fully deprecates the Munchkin Associate Lead method, which is a feature that allows the submission of a person’s data to a Marketo Engage subscription and associated web browsing history with a known person record. Associate Lead is being removed in favor of more modern and secure alternatives, like the Forms JS API, the Form Submit API, and the Associate Lead REST API. [Learn more about this deprecation here](https://developers.marketo.com/blog/deprecation-of-munchkin-associate-lead-method/).

* **Sales Connect Update**: A recent UI change in Sales Connect has caused some modals in Salesforce to get cut off. To fix this, please perform a [package update](/help/marketo/product-docs/marketo-sales-connect/crm/salesforce-customization/sales-connect-customizations-for-crm.md).

**_Product Release Webinar_**

[October 2021 Marketo Engage Release Webinar](https://engage.marketo.com/October_Release_Webinar_On-Demand.html)
