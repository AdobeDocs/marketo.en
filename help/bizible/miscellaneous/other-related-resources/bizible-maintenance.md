---
unique-page-id: 18874556
description: Bizible Maintenance - Bizible - Product Documentation
title: Bizible Maintenance
---

# Bizible Maintenance {#bizible-maintenance}

Bizible Maintenance - Bizible - Product Documentation

Bizible pulls almost everything it needs from your CRM on a daily basis, but there are a few maintenance tasks you’ll want to schedule regularly to keep Bizible humming along and outputting the most accurate information possible.

##### Sync Bizible Touchpoints for new offline campaigns (2x/month) {#sync-bizible-touchpoints-for-new-offline-campaigns-x-month}

As you learned during onboarding, Bizible gets information about your offline marketing efforts by syncing with your CRM’s campaigns. As your organization kicks off new campaigns, be sure to enable Bizible Touchpoints for each campaign as appropriate. Check out [this article](http://docs.marketo.com/x/6AAgAQ)for more information.

##### Upload spend for all channels (1x/month) {#upload-spend-for-all-channels-x-month}

To take advantage of Bizible’s full revenue and ROI reporting capabilities, you need to tell Bizible how much you’re spending on each of your marketing channels and subchannels. We recommend designating the owner of each channel/subchannel and having those people report spend to a single party responsible for uploading new cost information on a monthly basis.

Refresh your memory on how to upload cost information by reading [this article](http://docs.marketo.com/x/6gAgAQ).

##### Update list of domains to track (1x/month) {#update-list-of-domains-to-track-x-month}

Bizible tracks all pages and subdomains where our Javascript is active, but only for domains that we know about. If you’ve recently debuted a new domain, expanded internationally, or changed your primary domain, send a message to [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#364543464659444276545f4c5f545a531855595b) to make sure we update your account accordingly.

##### Review custom channel mapping for accuracy (1x/month) {#review-custom-channel-mapping-for-accuracy-x-month}

During onboarding, you set up custom channel mapping for your online and offline marketing efforts. As your marketing strategy and use of Bizible evolve, you’ll want to keep an eye on that mapping logic to ensure that all your Touchpoints are being categorized appropriately.

Remember, Bizible reprocesses your data when you edit mapping logic, so you won’t be able to change these rules more than once every 7 days.

Reference [this article](http://docs.marketo.com/x/5AAgAQ) for Online setup, [this article](http://docs.marketo.com/x/5gAgAQ) for Offline setup, and this list of best practices curated from our customers:

* Review Touchpoints that are currently falling into any “Other” or “NULL” channels you may have set up. If appropriate, update your mapping logic to re-categorize those Touchpoints into more accurate channels.
* Review Touchpoints that are currently falling into your Direct channels. If some of your email marketing campaigns or other efforts are missing UTM parameters, there’s a good chance that traffic is being inappropriately bucketed into a Direct channel. Consider updating your UTM parameters to capture the referring source.

##### Evaluate touchpoint suppression settings (1x/quarter) {#evaluate-touchpoint-suppression-settings-x-quarter}

If you’re seeing a lot of touchpoints that you’d prefer not be considered in your attribution story (from a Login or Unsubscribe forms, a Careers page, or an internal app, for example), you may want to evaluate your existing touchpoint suppression settings. Once a quarter, pinpoint any groups of touchpoints that are creating unnecessary noise and update your suppression logic appropriately. [Here’s a helpful article](http://docs.marketo.com/x/VgEgAQ)  with the how-to.

##### Review custom stage mapping for accuracy (1x/quarter) (if applicable) {#review-custom-stage-mapping-for-accuracy-x-quarter-if-applicable}

If you’re using any custom Lead, Contact, or Opportunities stages, you may have also customized what part of the pipeline those stages map to and whether or not those stages are included in a custom attribution model. Once a quarter, visit [this article](http://docs.marketo.com/x/mwEgAQ) to refresh your memory on custom stage mapping and ensure that you’re accurately tracking your custom stages.

##### Compare Machine Learning Model to Custom Model weighting (1x/quarter) (if applicable) {#compare-machine-learning-model-to-custom-model-weighting-x-quarter-if-applicable}

If you’re licensed for Bizible’s Custom Model, you also have data available from our Machine Learning Model (MLM) in Settings > Attribution Settings. The MLM calculates the importance of each stage using touchpoint data from your account, and may help you decide how to allocate attribution weight in your Custom Model. We recommend comparing the MLM to your Custom Model once a quarter, and discussing the implications of potential changes to your Custom Model with your SM.

For more information about Bizible’s Machine Learning Model, check out [this article](http://docs.marketo.com/x/lwEgAQ).

