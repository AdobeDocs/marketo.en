---
unique-page-id: 37356194
description: Export a Static List to Adobe Experience Cloud - Marketo Docs - Product Documentation
title: Export a Static List to Adobe Experience Cloud
---

# Export a Static List to Adobe Experience Cloud {#export-a-static-list-to-adobe-experience-cloud}

Export a Static List to Adobe Experience Cloud - Marketo Docs - Product Documentation

>[!NOTE]
>
>A HIPAA-ready deployment of a Marketo instance cannot use this feature.

>[!NOTE]
>
>**Prerequisites**
>
>[Set Up Adobe Experience Cloud Audience Sharing](http://docs.marketo.com/x/D4GMAg)

#### Supported Destination Applications {#exportastaticlisttoadobeexperiencecloud-supporteddestinationapplications}

* Adobe Advertising Cloud
* Adobe Analytics (**only** if you own an Adobe Audience Manager License)
* Adobe Audience Manager
* Adobe Experience Manager
* Adobe Real-Time Customer Data Platform
* Adobe Target

#### How to Export a List {#exportastaticlisttoadobeexperiencecloud-howtoexportalist}

1. In Marketo, find and select the list you want to export.

   ![](assets/one.png)

1. Click the **List Actions** drop-down and select **Send to Experience Cloud**.

   ![](assets/two-1.png)

1. Click the **Audience Manager Folder** drop-down and select the desired destination folder in the Experience Cloud.

   ![](assets/three-1.png)

1. Choose whether to create a new audience or overwrite an existing one (in this example we're creating a new one). Enter the new audience name and click **Send**.

   ![](assets/four.png)

1. Click **OK**.

   ![](assets/five.png)

   >[!NOTE]
   >
   >It can take up to 6-8 hours for audience membership to fully populate in Adobe.

#### Things to Note {#exportastaticlisttoadobeexperiencecloud-thingstonote}

##### Sharing to Adobe Analytics   
{#exportastaticlisttoadobeexperiencecloud-sharingtoadobeanalytics}

For customers that own both Adobe Audience Manager and Adobe Analytics, this integration will enable audiences to be shared from Marketo to your Adobe Analytics Report Suites, however there are some additional configurations steps that need to be taken in Adobe Audience Manager to enable this. Please review Adobe Audience Manager’s documentation for more information on how to set this up: [https://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html](http://docs.adobe.com/content/help/en/analytics/integration/audience-analytics/mc-audiences-aam.html).

##### Trait Usage for Adobe Audience Manager Customers {#exportastaticlisttoadobeexperiencecloud-traitusageforadobeaudiencemanagercustomers}

When you initiate a list export in Marketo, you'll notice the following changes reflected in your Adobe Audience Manager instance:

* For all of the Leads in the exported List, Marketo will write a trait using the Leads’ hashed emails as a Cross-Device Identifier. The name of the trait will match the Destination Audience Name that you specified during the export.
* For all of the ECIDs that Marketo has managed to match to the Leads in the exported List, Marketo will write a trait using the ECID Device Identifier. The name of the trait will match the Destination Audience Name that you specified during the export.
* Marketo will also create a segment in your Audience Manager Instance using the ECID trait as the sole segmentation criterion. The name of the segment will match the Destination Audience Name that you specified during the export.

#### FAQ {#exportastaticlisttoadobeexperiencecloud-faq}

##### Why is the list size in Marketo different than the one in Adobe? {#exportastaticlisttoadobeexperiencecloud-whyisthelistsizeinmarketodifferentthantheoneinadobe}

Under the hood, the audience integration works by syncing Marketo Munchkin cookies with the corresponding Adobe ECID cookie. Marketo can only share membership data for leads that Marketo has synced an ECID for. For the best possible results, it’s recommended that you load Marketo’s munchkin.js tracking script in parallel with Adobe’s visitor.js tracking code on all of the pages you’re interested in tracking for marketing purposes.

##### How does the cookie sync work? {#exportastaticlisttoadobeexperiencecloud-howdoesthecookiesyncwork}

When the cookie sync is enabled for your Marketo Subscription, Marketo’s munchkin.js will attempt to capture and store Adobe ECIDs for the Adobe IMS Org you specified during the integration setup and match these ECIDs to the corresponding Marketo cookie identifier. This enables Marketo’s anonymous user profiles to become enriched with Adobe ECIDs.

A further step is required to associate the anonymous user profile to a Lead Profile, which is identified using a plain text email. Exactly how this works is described here: [https://docs.marketo.com/display/public/DOCS/Tracking+Anonymous+Activity+and+People](http://docs.marketo.com/display/public/DOCS/Tracking+Anonymous+Activity+and+People).
