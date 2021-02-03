---
unique-page-id: 11383945
description: Understanding Facebook Offline Conversions - Marketo Docs - Product Documentation
title: Understanding Facebook Offline Conversions
---

# Understanding Facebook Offline Conversions {#understanding-facebook-offline-conversions}

Facebook Lead Ads campaigns generate leads and send them to Marketo for use in marketing campaigns. However, without visibility into offline conversions, the Facebook advertiser can't know which ads are most effective. Here's an example.

>[!NOTE]
>
>**Example**
>
>Facebook Lead Ads runs three ads.
>
>* Ad 1 generates 20 leads
>* Ad 2 generates 30 leads
>* Ad 3 generates 50 leads
>
>Based on these numbers alone, Ad 3 seems the most effective.
>
>However, when looking at data on the Marketo side, a different story develops.
>
>* Ad 1 generates 10 sales
>* Ad 3 generates 2 sales
>
>That means that Ad 1, despite generating fewer leads, had a 50 percent success rate, while Ad 3 was hardly effective at all.
>
>Without offline conversions, the advertiser would probably invest more money in Ad 3. With offline conversion data, the advertiser will more likely invest in Ad 1.

You can [set up Facebook Offline Conversions](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md) to send offline ad performance to Facebook.

1. Make sure your [Facebook LaunchPoint integration](/help/marketo/product-docs/demand-generation/ad-network-integrations/add-facebook-custom-audiences-as-a-launchpoint-service.md) is up-to-date.
1. Map stages in your Revenue Cycle Model to offline conversion stages on Facebook.
1. When a Facebook Lead is generated from a Facebook Lead Ad and reaches a mapped stage, Marketo sends offline conversion data back to Facebook several times a day via a secure, automated API. The data appears in the Facebook Ads Manager Report.

>[!MORELIKETHIS]
>
>[Set Up Facebook Offline Conversions](/help/marketo/product-docs/demand-generation/facebook/set-up-facebook-offline-conversions.md)
