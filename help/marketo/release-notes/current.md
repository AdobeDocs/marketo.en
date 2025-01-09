---
description: Current Release Notes - Marketo Docs - Product Documentation
title: Current Release Notes
exl-id: a2eccad5-73ad-48f9-8091-51cee23824e1
feature: Release Information
---
# Release Notes: January 2025 {#release-notes-jan-25}

Below you'll find all the features included in the January '25 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **January 17, 2025**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:65%">Feature</th> 
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
    <tr> 
   <td><strong>New Email Designer</strong>: Create modern and efficient emails using the new native Email Designer in Marketo Engage. Access one of the pre-designed out-of-the-box email templates, or easily create your own. Use dynamic content and access images from Adobe Experience Manager cloud services.</td> 
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr> 
   <td><strong>Unregister Registrants from an Event in Interactive Webinars</strong>: Now if you don't want a registrant in your webinar for any reason, you can unregister them. The workflow removes the registrant from both the Marketo Event Program as well as Adobe Connect.</td> 
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  <tr> 
   <td>&nbsp;</td> 
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr> 
   <td><strong>Disable Campaigns on Archive</strong>: Disable active trigger campaigns and cancel any scheduled batch runs of campaigns in a folder when it's archived. Since there is an additional permissions check for archiving folders that contain active campaigns (Activate Trigger Campaign and Schedule Batch Campaign), this feature becomes disabled by default with this release and can be enabled by navigating to <b>Admin</b> > <b>Treasure Chest</b> in your Marketo Engage subscription.</td> 
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
 </tbody> 
</table>
<br/> 

## Announcements {#announcements}

* **Get Program Members API Update**: We have enhanced the [Get Program Members](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/program-members#query){target="_blank"} API to support the ability to retrieve program members' identifier. This is done by adding id to the list of fields specified in the fields parameter of the API request.

* **Rest API 'access_token' Parameter Deprecation**: The `access_token` query parameter used to authenticate Marketo REST API calls is being deprecated and will not be available after June 30, 2025. All new and existing integrations should authenticate REST API calls using the 'Authorization' header, [as described here](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/authentication){target="_blank"}.

* **SOAP API Deprecation**: Support for the Marketo SOAP API will end on Oct 31, 2025. Services which use SOAP API capabilities should be migrated to the [REST API](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/rest-api){target="_blank"}.
