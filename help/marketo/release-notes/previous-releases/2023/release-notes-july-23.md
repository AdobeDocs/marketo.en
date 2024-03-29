---
description: Release Notes - July 2023 - Marketo Docs - Product Documentation
title: Release Notes - July 2023
feature: Release Information
exl-id: 4056353c-4125-4849-8350-59c58afb9e66
---
# Release Notes: July 2023 {#release-notes-july-23}

Below you'll find all the features included in the July '23 release. Check your Adobe Marketo Engage edition for feature availability.

>[!AVAILABILITY]
>
>Features denoted by a star (![star](assets/yellow-star.png)) are paid add-ons. Please contact your Marketo Engage representative to learn more.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **July 21, 2023**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check below each feature for its status.

</br>

* **Engagement Map**: The Engagement Map is a visual tool that allows you to build and organize reusable campaigns. It's completely backwards compatible, so all existing campaigns can be viewed in this new structure with the click of a button. Maps can be downloaded and shared.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/engagement-map/engagement-map-overview.md" target="_blank">Engagement Map Overview</a></td>
  </tr>
  </tbody>
</table>

* **Notifications - Web Services Error**: The Web Services Error notification now includes the subscription name, which makes it easier for those managing multiple Marketo Engage instances. We have also added a "User" column to table that contains Error Codes and Counts, so you can easily identify which API User was responsible for generating a specific error when calling the Marketo REST API.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
  </tbody>
</table>

## Agile Release Features

The following features follow an Agile format and are released on various dates before or after the standard release date. Please check below each feature for its status.

### Dynamic Chat {#dynamic-chat}

</br>

* **Chat Source for Dynamic Chat**: "Chat" is now offered as a source of new person records and activities. This source can be used to help users filter activities in Smart Lists/Campaigns. The source can also be blocked from updates on fields.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
  </tbody>
</table>

* **Enhanced Dynamic Chat Activities**: Dynamic Chat activities, filters, and triggers have been enhanced with additional attributes and standardized naming conventions.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td>Shipped</td>
   <td>n/a</td>
  </tr>
  </tbody>
</table>

### Marketo Sales Insight {#marketo-sales-insight}

</br>

* **Unsubscribe Append Settings for Sales Insight Actions**: You now have more control over your unsubscribe messages with new configuration options to Unsubscribe Appending. New capabilities give Admins control over when, where, and what unsubscribe messaging will appear in your sales emails.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/auto-append-unsubscribe-message-setting.md" target="_blank">Auto-Append Unsubscribe Message Setting</a></td>
  </tr>
  </tbody>
</table>

* **Dynamic Field Prompts for Sales Insight Actions**: You can now prompt your Sales Team to personalize specific parts of an email even further with new Field Prompts available to be added to email templates in Sales Insight Actions.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/marketo-sales-insight/actions/templates/field-prompts.md" target="_blank">Field Prompts</a></td>
  </tr>
  </tbody>
</table>

* **Default Dynamic Fields for Sales Insight Actions**: Default Dynamic Fields allow you to configure a fallback value that a Dynamic Field can resolve to if there's no value available to be populated. This helps ensure emails go out with all of the personalization filled in.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/marketo-sales-insight/actions/templates/dynamic-fields.md" target="_blank">Dynamic Fields</a></td>
  </tr>
  </tbody>
</table>

* **Dynamic Chat Support for Sales Insight**: Updates have been made to support new Dynamic Chat attributes introduced in this release for all Dynamic Chat users.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  </tbody>
</table>

* **Dynamic Chat Support for Sales Insight Actions**: We now support Dynamic Chat activities in the Lead Feed as well as notifications when a Live Chat is routed to an agent.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td><i>Coming Soon</i></td>
   <td><i>Coming Soon</i></td>
  </tr>
  </tbody>
</table>

* **Dynamic Chat Trigger Tokens**: Introducing new Trigger Tokens for Dynamic Chat activities to be used in Interesting Moments.

<table> 
  <tr> 
   <td><b>Status</b></td>
   <td><b>Documentation Updates</b></td>
  </tr>
  <tr> 
   <td>Shipped</td>
   <td><a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/tabs-in-the-msi-panel/interesting-moments/trigger-tokens-for-interesting-moments.md" target="_blank">Dynamic Chat Trigger Tokens</a></td>
  </tr>
  </tbody>
</table>

## Announcements {#announcements}
 
* **Upgrade to Google Analytics 4**: Marketo previously supported Universal Analytics, which will stop recording data by July 1, 2023. RTP users will need to follow the migration process in their Google Analytics dashboard to complete support for the Google Analytics 4 integration in RTP. Going forward, users will have a unique alphanumeric tag (located within the `<head>` section of the html) in their landing pages that allows Marketo to send data to Google Analytics.

* **_Product Release Webinar_**: [July and September 2023 Marketo Engage Release Webinar](https://engage.marketo.com/2023_July_September_Release_Webinar_OnDemandPage.html){target="_blank"}
