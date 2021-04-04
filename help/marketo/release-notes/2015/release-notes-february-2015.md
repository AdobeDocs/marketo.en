---
unique-page-id: 6094890
description: Release Notes -February 2015 - Marketo Docs - Product Documentation
title: Release Notes -February 2015
exl-id: a7ce88dc-a4d2-4ccb-9fe5-61130334d24d
---
# Release Notes: February 2015 {#release-notes-february}

The following features are included in the February 2015 release. Please check your Marketo Edition for feature availability. After the release, be sure to come back to find links to detailed articles for each feature. Drum roll...

## Marketing Automation Enhancements {#marketing-automation-enhancements}

**[Move Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/move-a-smart-campaign.md)**

Rejoice! Now you can move smart campaigns in and out of programs using drag and drop or the Move feature in the tree.

**[Dynamics 2015 (Online)](https://docs.marketo.com/display/docs/microsoft+dynamics+2013+on-premises)** - supported!

**HTTPS Certificate Changes**

To protect confidentiality and integrity of customer data and SaaS services, Marketo follows SaaS industry best practices

and will replace currently used security protocols (SHA-1 and SSL) with more secure versions (SHA-2 (a.k.a. SHA-256) and TLS) for the following domains:

* [marketo.net](https://marketo.net) (encrypted Munchkin traffic)

* [marketo.com](https://marketo.com) (main SaaS applications)

This will happen shortly after this release. SHA-1 protocol will be temporally supported on [mktoapi.com](https://mktoapi.com) domain until December, 2015 to allow owners of legacy systems and applications to update their systems with SHA-2 compatibility.

**Secure Munchkin**

We are removing our support for SSL3. We have maintained SSL3 up until now to maintain support for old web browsers, but in 2015 we are no longer seeing significant web traffic from those browsers. This would only affect Munchkin when used on secure pages, and will roll out slowly after the February release.

## Real-Time Personalization Enhancements {#real-time-personalization-enhancements}

**[Target URL for Campaigns](/help/marketo/product-docs/web-personalization/working-with-web-campaigns/adding-a-target-url-to-a-web-campaign.md)**

Select the pages you would like your real-time campaign to display on using 'Add a Target URL'. This feature works with all campaign types (Dialog, In Zone, Widgets), but is especially valuable for In Zone campaigns where a campaign will render in the Zone ID for only the target URL selected. It supports adding multiple URLs to target different web pages.

![](assets/image2015-2-19-11-3a0-3a30.png)

**Country and State Added to Account-Based Targeting**

Country and State can now be added to your Named Account Lists. Target key account prospects from specific locations.
