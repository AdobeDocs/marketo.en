---
description: Current Release Notes - Marketo Docs - Product Documentation
title: Current Release Notes
hide: true
feature: Release Information
exl-id: 0ca5e844-c30b-4c86-a23d-d8f2c1bdddf5
TQID: 'https://experienceleague.adobe.com/RZsCx9HAyJuDLO46WfshT30be-rMMDZjnygvU32NGfk'
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: f71e690b-4480-4b67-9ef5-88f42f9cdfdb
    internal-label: Resources
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: c942e9f6-ed06-481a-abdd-1195363d1452
    internal-label: Dynamic Chat
  - id: af97ce94-35fa-4fa9-b85a-46b752ac4028
    internal-label: Release information
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Release Notes: October 2026 {#release-notes-oct-26}

Below you'll find all the features included in the October '26 release. Check your Adobe Marketo Engage edition for feature availability.

The Release Notes specifically for Adobe Dynamic Chat [can be found here](/help/marketo/release-notes/dynamic-chat.md){target="_blank"}.

## Standard Release Cycle Features {#standard-release-cycle-features}

The following features fall under the standard release cycle and will start to be released on **October 23, 2026**, with a phased rollout of remaining features over the subsequent weeks. Release features and dates are subject to change. Please check next to each feature for its status.

<table style="table-layout:auto">
 <tbody>
 <tr>
   <th style="width:65%">Feature</th>
   <th style="width:10%">Status</th>
   <th style="width:25%">Documentation</th>
  </tr>
  <tr>
   <td><strong>Clone to This Program/Folder</strong>: Cloning operations across Marketo Engage now consistently offer a "This Folder" or "This Program" option as a first choice when choosing the destination of the cloned asset. Choosing this option clones the asset to the parent program or folder of the current asset.</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  <tr>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
   <td>&nbsp;</td>
  </tr>
  <tr>
   <tr>
   <td><strong>Instant alert on CRM sync</strong>: Enabling or disabling the native CRM sync for an environment now triggers a notification to users who are subscribed to the CRM notification channel.</td>
   <td><i>Coming soon</i></td>
   <td><i>Coming soon</i></td>
  </tr>
  </tr>
  </tbody>
</table>
<br/>

## Announcements {#announcements}

* **Deprecation of Grab Images from Web**: To conform to modern security and privacy best practices, the [Grab Images from Web](https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/images-and-files/grab-the-images-from-a-web-page){target="_blank"} feature will be deprecated as of the October release.

* **API Name Restrictions for Custom Activity Attributes**: API Names for Custom Activity Attributes created via the API or UI may now only contain alphanumeric characters and underscores, and must begin with an alphanumeric character.

* **Static List Size Limits for Get Lead Activities and Get Lead Changes**: As of September 30, 2026, calls to the Get Lead Activities or Get Lead Changes endpoints which include the `listId` parameter began to fail with a 1003 Error Code (indicating that the target static list has too many records) if the target lists contain 10,000 or more leads. Consult the [Migration Guide](https://experienceleague.adobe.com/en/docs/marketo-developer/marketo/rest/lead-database/migration){target="_blank"} for additional information.
