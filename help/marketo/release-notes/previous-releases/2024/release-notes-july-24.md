---
description: Release Notes - July 2024 - Marketo Docs - Product Documentation
title: Release Notes - July 2024
feature: Release Information
exl-id: ff63af41-2d33-40f8-abca-3fd9493e7916
---
# Release Notes: July 2024 {#release-notes-july-24}

Below you'll find all the features included in the July '24 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **July 26, 2024**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Feature</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documention</th>
  </tr>
     <tr> 
   <td><strong>Engagement Dashboard for Interactive Webinars</strong>: Obtain an aggregate webinar performance view as well as a comprehensive view of engagement for each attendee during the webinar so you can decide which leads to target through Marketo Engage orchestration tools.</td> 
    <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/engagement-dashboard.md" target="_blank">Engagement Dashboard</a></td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  </tr>
     <tr> 
   <td><strong>Room Management for Interactive Webinars</strong>: Access individual rooms created (and make modifications if needed) as well as access the content and recording (and clear them if needed to optimize storage).</td> 
    <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/room-management.md" target="_blank">Room Management</a></td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  </tr>
     <tr> 
   <td><strong>Webinar Customization for Interactive Webinars</strong>: Provide a uniform organization-approved branded experience through the use of a common room interface, intermediary screens (such as attendee entry screen backgrounds), as well as custom video backgrounds, so that webinar strategy can more easily align with brand strategy.</td> 
    <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/demand-generation/events/interactive-webinars/customization.md" target="_blank">Interactive Webinars Customization</a></td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  </tr>
     <tr> 
   <td><strong>Marketo REST API Change</strong>: We are introducing a minor change to the <a href="https://developers.marketo.com/rest-api/user-management/">User Management API</a>. Both the <a href="https://developers.marketo.com/rest-api/user-management/#browse_users">Browse Users</a> and <a href="https://developers.marketo.com/rest-api/user-management/#delete_user">Delete User</a> endpoints now support <a href="/help/marketo/product-docs/target-account-management/setup-tam/target-account-management-overview.md">Target Account Management</a> users.</td> 
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
 </tbody> 
</table>
<br/>

## Announcements {#announcements}

* **New Developer Documentation Site**: As part of our continued effort to enhance the Marketo Engage user experience, we will be migrating all developer documentation to the Adobe Experience League and the Adobe Developer website in July 2024. [Learn more](https://nation.marketo.com/t5/employee-blogs/new-developer-documentation-website/ba-p/351055){target="_blank"}

* **Social Features Deprecation**: On Wednesday, July 31, 2024, Marketo Engage will begin the deprecation of the following Social features within the product:

  * Polls
  * Social Button
  * Referral Offer
  * Video Share
  * Sweepstakes

Users will no longer be able to create, clone, or embed any of these Social features in Marketo Engage. Existing Social assets will continue to work through January 31, 2025. [Learn more](https://nation.marketo.com/t5/employee-blogs/marketo-engage-social-features-deprecation/ba-p/351977){target="_blank"}

* **Access Token in Query Parameter Deprecation**: Support for authentication using access tokens in a query parameter of a Marketo Engage REST API call will be removed in a future release (specific date TBD). Existing integrations should migrate to usage of the Authorization header [described here](https://developers.marketo.com/rest-api/authentication/){target="_blank"}. New development should only use the Authorization header for authentication with Marketo Engage.

* **LinkedIn Re-authentication Required**: LinkedIn is upgrading their Marketing APIs used by Marketo Engage LinkedIn integrations. These changes will require re-authentication of all LinkedIn LaunchPoint services in your **Admin** > **LaunchPoint** menu between July 26 and December 15, 2024, to avoid service interruption. You can find instructions on how to accomplish this [here for Lead Gen Forms](/help/marketo/product-docs/demand-generation/social/social-functions/set-up-linkedin-lead-gen-forms.md){target="_blank"} and [here for Matched Audiences](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-linkedin-matched-audiences-as-a-launchpoint-service.md){target="_blank"}. Lead Gen Form service has a type of "LinkedIn Lead Gen" and Matched Audience service has type of "LinkedIn Matched Audiences." For more information, visit the [Migration FAQ](https://nation.marketo.com/t5/employee-blogs/linkedin-re-authentication-required/ba-p/347794){target="_blank"}.
