---
description: "Release Notes - March 2024 - Marketo Docs - Product Documentation"
title: Release Notes - March 2024
feature: Release Information
exl-id: d8bc7f88-a77b-4b49-aed5-aceab9e639f0
---
# Release Notes: March 2024 {#release-notes-mar-24}

Below you'll find all the features included in the March '24 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **March 8, 2024**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
  <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documention</th>
  </tr>
  <tr>
   <td><strong>Advanced Conversational Flow Logic</strong>: Add additional fields for evaluation in a single choice for Conversational Flow follow-up.</td>
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">Conversational Flow Settings for Marketo Engage Forms</a></td>
  </tr>
   <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
   </tr>
    <tr>
   <td><strong>Reorder Conversational Flow Logic</strong>: In Marketo Engage Forms, you can now reorder the Conversational Flow choices, instead of having to delete and add back.</td>
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/demand-generation/dynamic-chat/automated-chat/conversational-flow-settings-for-marketo-engage-forms.md" target="_blank">Conversational Flow Settings for Marketo Engage Forms</a></td>
   </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
    <tr>
   <td><strong>API Activity Metadata</strong>:
   Metadata such as User Agent, Platform, and Device are now included in web and email activities, helping to provide consistent insights into these activities via the Marketo REST API.</td>
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
 </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Get Program Member API Fix**: A change was made recently to correct the behavior of the [Get Program Members](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Program-Members/operation/getProgramMembersUsingGET){target="_blank"} endpoint. Previously, when utilizing the `updatedAt` filter type to specify a date range, there was a chance that program membership records updated within that range were not included in the response. Additionally, there was a chance that program membership records updated outside of the specified date range being incorrectly included in the response. Both issues have been resolved.

* **Account Insight Browser Plug-in Deprecation**: Adobe is removing the Target Account Management [Account Insight browser plug-in](/help/marketo/product-docs/target-account-management/setup-tam/account-insight-plug-in-overview.md){target="_blank"} from the Chrome Web Store on April 8, 2024. Existing users: you can continue to use the plug-in until you migrate your Marketo Engage instance to Adobe Identity and Admin Console. This change **will not impact** any other TAM features/data within Marketo Engage or the Chrome and Outlook email plug-ins that work with Sales Insight. [Learn more](https://nation.marketo.com/t5/product-blogs/marketo-engage-account-insights-browser-plug-in-end-of-life/ba-p/344834){target="_blank"}.
