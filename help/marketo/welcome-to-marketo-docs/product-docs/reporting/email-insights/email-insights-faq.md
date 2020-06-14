---
unique-page-id: 10100257
description: Email Insights FAQ - Marketo Docs - Product Documentation
title: Email Insights FAQ
---

# Email Insights FAQ {#email-insights-faq}

Email Insights FAQ - Marketo Docs - Product Documentation

#### Are there any differences between ratio metrics with Email Insights and other Marketo Email reporting? {#emailinsightsfaq-arethereanydifferencesbetweenratiometricswithemailinsightsandothermarketoemailreporting?}

Yes. Email Insights correlates engagement metrics with their corresponding delivery metrics for the same email sent when computing engagement metric ratios (Open Rate, Click-to-Open Rate, Unsubscribe Rate). For example, in Email Insights, when looking at a time-series chart over the past week with daily breakdowns of Click-to-Open-Rate, we now show the true correlated ratio of open/click/unsubscribe events based on the corresponding delivery metrics. This is in contrast to the behavior in Revenue Explorer, which simply sums everything up. Email Insights presents a more accurate view of engagement ratios.

#### Why does Email Insights only support 10 Custom Dimensions? {#emailinsightsfaq-whydoesemailinsightsonlysupport10customdimensions?}

For many use-cases, extending the default system dimensions with 10 additional custom dimensions will be more than adequate, and includes custom dimensions based on Segmentations or Program Tags. In the future, we plan on permitting customers to increase the number of allowed Custom Dimensions.

#### Why can't I re-use Custom Dimensions slots after they've been assigned? {#emailinsightsfaq-whycan'tire-usecustomdimensionsslotsafterthey'vebeenassigned?}

Once a given Custom Dimension slot has been allocated, remapping it would cause previous data to produce an error when blended with a new meaning. Because of that, Custom Dimension slots may not be re-used. This behavior is consistent with that of other metric analysis tools, such as Google Analytics.

#### Does Email Insights support Marketo Sales Insight emails? {#emailinsightsfaq-doesemailinsightssupportmarketosalesinsightemails?}

Yes. All emails sent via Marketo Sales Insights are included in Email Insights.

#### Does Email Insights support Operational emails? {#emailinsightsfaq-doesemailinsightssupportoperationalemails?}

Yes. By default, Operational emails are hidden from view and querying. However, you may change this setting under the Personal Settings panel.

#### Does Email Insights capture recurring scheduled or re-run Smart Campaign email flow steps? {#emailinsightsfaq-doesemailinsightscapturerecurringscheduledorre-runsmartcampaignemailflowsteps?}

Yes and No. With the initial release of Email Insights, all email events are captured and accessible for any recurring scheduled or re-run Smart Campaign. But you won't be able to differentiate between different runs of that Smart Campaign. We are adding support in our next release to capture the Smart Campaign run information for Open, Click, and Unsubscribe events in order to differentiate.

#### Why do many metrics show zero when I filter by Device Type or Device OS? {#emailinsightsfaq-whydomanymetricsshowzerowhenifilterbydevicetypeordeviceos?}

With the exception of Click-to-Open-Rate, Opens, Clicks, and Unsubscribes, all other supported metrics are either delivery events or ratios derived from delivery events. Since Device Type and Device OS only apply to Engagement metrics, we simply do not have the information to display. For example, it's an undefined query to ask for the Delivery Rate when filtered by Device Type = mobile, since Marketo would not have received any Engagement metrics for either the underlying Delivery and Sent events. We are exploring ways to apply the Device Type and Device OS from Engagement metrics for ratios comprised both of Engagement and Delivery metrics.

#### What does Email Insights do when certain Email clients block images? {#emailinsightsfaq-whatdoesemailinsightsdowhencertainemailclientsblockimages?}

A common industry problem is a growing number of email clients are turning images off by default. Loading images is the basis for how Opens are recorded. It is entirely possible that a user may receive an email with images blocked, but with the text and links fully readable. If a user experienced this and clicked on a link in that email, you would end up with a scenario of a Click event, but no corresponding Open event for said email. Marketo Email Insights will automatically generate any events that were missing. The logic is identical to how Marketo does this for the Email Performance report, as well as the Email Analysis area in Revenue Explorer.
