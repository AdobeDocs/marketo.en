---
unique-page-id: 35586080
description: LinkedIn Integration - Bizible - Product Documentation
title: LinkedIn Integration
---

# LinkedIn Integration {#linkedin-integration}

LinkedIn Integration - Bizible - Product Documentation

The LinkedIn integration allows Bizible to tag destination URLs on LinkedIn ads, which ultimately allows Bizible to follow a user through their entire touchpoint journey and map the activity back to the specific LinkedIn Campaign and Creative. This provides insights to customers about the ROI of their LinkedIn activity.

### What's in this article? {#whats-in-this-article}

[Requirements](#requirements)  
[LinkedIn Ad Types](#linkedin-ad-types)  
[LinkedIn’s Unique Auto-Tagging Requirements](#linkedin-s-unique-auto-tagging-requirements)  
[Copying Shares](#copying-shares)  
[Shortened URLs](#shortened-urls)  
[The Process](#the-process)  
[Touchpoint Details](#touchpoint-details)  
[Costs](#costs)  
[FAQ](#faq)

#### Requirements {#requirements}

In order to be able to get Ads Data & Ads cost data, the user needs permission to be in certain roles of an account. These roles are:

ACCOUNT_BILLING_ADMIN

ACCOUNT_MANAGER

CAMPAIGN_MANAGER

In addition, in order to be able to create/update Sponsored Creative and dark share, the user needs permission to be in certain roles of an organization. These roles are:

ADMINISTRATOR

DIRECT_SPONSORED_CONTENT_POSTER

#### LinkedIn Ad Types {#linkedin-ad-types}

Bizible will support:

**Sponsored Content:** Sponsored Content allows you to deliver content to the LinkedIn feed of members beyond those who are following your company. Sponsored Content can be targeted to a specific audience, and can help advertisers reach LinkedIn members wherever and whenever they are engaging on the LinkedIn platform across desktop, mobile, and tablet.

![](assets/one.png)

>[!TIP]
>
>For any of your Campaigns/Spend that originate from a non-Sponsored Content source (such as Campaign Type of "Text Ad" or "Sponsored InMail"), Bizible does **not** inherently support the tracking of these Campaign Types. If you want to track Spend for Campaigns such as these alongside your "Sponsored Contect" Spend, be sure to make use of our Marketing Spend CSV to manually log said Spend.

#### LinkedIn’s Unique Auto-Tagging Requirements {#linkedin-s-unique-auto-tagging-requirements}

Bizible can help track your LinkedIn campaign performance by auto-tagging your landing pages.

Bizible will search for creatives with a unique LinkedIn Share and add a **?_bl={creativeId}** parameter to the end of it.

#### Copying Shares {#copying-shares}

With this Bizible/LinkedIn Integration, we ask that customers do not copy/clone/duplicate existing Creatives. If Shares are found and are detected to only be used on one Creative, Bizible can tag the Share as is without having to recreate any Creatives or Shares and all ads history (impressions, clicks, shares) will remain.

As soon as a Share is found to be shared across multiple Creatives, Bizible will have to run through a process of pausing, copying, and re-tagging in order to make a unique set. Bizible will pause and archive live creatives and therefore erase Ad History including impressions, clicks, and social shares in order to auto-tag everything properly.

Moving forward, Bizible recommends that you do not duplicate any LinkedIn Shares and keep all creatives and shares as unique as possible so that we can simply add our tracking without having to erase Ad History.

#### Shortened URLs {#shortened-urls}

The reason for the extra step is because LinkedIn allows destination URLs to be a shortened URL (bit.ly, goog.le, etc.,), which means Bizible doesn’t see the long, resolved URL and Bizible needs to add tracking parameters to a resolved URL. In order to get around that issue, Bizible looks for shortened URLs prior to re-creating an ad, expands the URL, then creates the new ad with the resolved URL and all of its parameters, allowing Bizible to add tags. Creating a new ad will erase ads history (impressions, clicks, shares), hence the need for permission to tag shortened URLs.  
  
If you heavily use shortened URLs, this could severely impact your creatives. We recommend that you no longer use shortened URLs so that Bizible can tag the landing pages without having to create new ads and erase Ad History.

#### The Process {#the-process}

Let's start with some examples. Let's say we have....

Creative A : Share 123  
Creative B : Share 234  
Creative C : Share 234  
Creative D : Share 234

![](assets/two.png)

1) Bizible will first look through all Campaigns, Creatives and Shares with an "Active" status. Bizible will not tag paused, archived, or cancelled ads. If an ad was paused, then set to active, we will tag it once it's active again. If we can find a unique Share, meaning it's not used across multiple Creatives or Campaigns (e.g., Creative A : Share 123), Bizible will add our custom parameter >> ?_bl={creativeId} to the share URL.

2) Now if the Share has been shared and lost its uniqueness (for instance, Creative B : Share 234 and Creative C : Share 234 and Creative D : Share 234), Bizible will pause and archive all similar creatives (which would be Creative B, Creative C, and Creative D).

3) Bizible will create 3 new creatives, Creative E, Creative F, and Creative G, that copies the content of Creative B, which is archived.

5) Bizible will also create 3 new shares, Share 345, Share 456, and Share 567, that copies the content of Share 234, except it will have its own unique ?_bl tagging.

6) Bizible will have to regularly check that Shares do not get shared and if they do, we will restart the process at step 2 above.

>[!NOTE]
>
>Implementing this will mean that our customers will lose the ads history of the Creative B : Share 234, Creative C : Share 234 and Creative D : Share 234 because it now gets recreated with Creative E : Share 345, Share F : Share 456, and Creative G : Share 567 respectively.

![](assets/three.png)

#### Touchpoint Details {#touchpoint-details}

Once Bizible has successfully tagged your landing page on the LinkedIn creative, you’ll be able to view the resolved ads data on the touchpoint. Here's the mapping of data values that you should expect to see:

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th>Touchpoint Field</th> 
   <th>Sample Value</th> 
  </tr> 
  <tr> 
   <td><p>Ad Id </p></td> 
   <td><p>84186224 </p></td> 
  </tr> 
  <tr> 
   <td><p>Ad Content </p></td> 
   <td><p>copy-1-image-2-man 95% of #B2B marketers consider demand creation strategy to be successful. Learn more: https://lnkd.in/jgdi50vKrgv</p></td> 
  </tr> 
  <tr> 
   <td><p>Ad Group Id </p></td> 
   <td><p>(blank) </p></td> 
  </tr> 
  <tr> 
   <td><p>Ad Group Name </p></td> 
   <td><p>(blank) </p></td> 
  </tr> 
  <tr> 
   <td><p>Ad Campaign Id </p></td> 
   <td><p>138949954 </p></td> 
  </tr> 
  <tr> 
   <td><p>Ad Campaign Name </p></td> 
   <td><p>SU – COM Accounts – Demand Skills </p></td> 
  </tr> 
  <tr> 
   <td><p>Ad Destination URL </p></td> 
   <td><p>https://www.bizible.com/marketing-attribution-for-demand-generation-leaders?_bl=84186217 </p></td> 
  </tr> 
  <tr> 
   <td><p>Form URL </p></td> 
   <td><p>info.bizible.com/demo </p></td> 
  </tr> 
  <tr> 
   <td><p>Form URL - Raw </p></td> 
   <td><p>info.bizible.com/demo </p></td> 
  </tr> 
  <tr> 
   <td><p>Keyword Id </p></td> 
   <td><p>(blank) </p></td> 
  </tr> 
  <tr> 
   <td><p>Keyword Match Type </p></td> 
   <td><p>(blank) </p></td> 
  </tr> 
  <tr> 
   <td><p>Landing Page </p></td> 
   <td><p>https://www.bizible.com/marketing-attribution-for-demand-generation-leaders </p></td> 
  </tr> 
  <tr> 
   <td><p>Landing Page - Raw </p></td> 
   <td><p>https://www.bizible.com/marketing-attribution-for-demand-generation-leaders?_bl=84186217 </p></td> 
  </tr> 
  <tr> 
   <td><p>Marketing Channel </p></td> 
   <td><p>Paid Social </p></td> 
  </tr> 
  <tr> 
   <td><p>Marketing Channel - Path </p></td> 
   <td><p>Paid Social.LinkedIn </p></td> 
  </tr> 
  <tr> 
   <td><p>Medium </p></td> 
   <td><p>cpc </p></td> 
  </tr> 
  <tr> 
   <td><p>Referrer Page </p></td> 
   <td><p>www.linkedin.com/ </p></td> 
  </tr> 
  <tr> 
   <td><p>Referrer Page - Raw </p></td> 
   <td><p>www.linkedin.com/ </p></td> 
  </tr> 
  <tr> 
   <td><p>Serach Phrase </p></td> 
   <td><p>(blank) </p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>Touchpoint Type </p></td> 
   <td colspan="1"><p>Web Form </p></td> 
  </tr> 
  <tr> 
   <td colspan="1"><p>Touchpoint Source </p></td> 
   <td colspan="1"><p>LinkedIn </p></td> 
  </tr> 
 </tbody> 
</table>

#### Costs {#costs}

Because Bizible has a direct integration with LinkedIn, we download the recorded spend for each Campaign and Creative each day. There is no need for a customer to report on LinkedIn spend within the Bizible application anymore.

As with other ad integrations, Bizible has defined a marketing channel rule to place all LinkedIn campaigns, creatives, and cost. To use the rule, the customer will want to insert a new row for their Paid LinkedIn efforts. It can be a new or existing channel. In the Referrer column, use the definition “[LinkedIn Paid]” which Bizible has defined as any touchpoint with a Bizible tag.

![](assets/four.png)

#### FAQ {#faq}

##### What is a Dark Share? {#what-is-a-dark-share}

A dark share is a post where it is never posted on the company page and immediately gets created and directly added as a Creative. So that Bizible-created Creatives don’t appear at the top of a company’s page and get promoted again, dark shares are used so that it can launch behind the scenes.

##### What Statuses does Bizible actually tag? {#what-statuses-does-bizible-actually-tag}

There are four different statuses on a LinkedIn Campaign and Creative: Active, Paused, Archived, and Cancelled. We only tag Campaigns and Creatives that are Active. Tagging other statuses set them to Active again. Bizible will not tag Paused, Archived or Cancelled Campaigns or Creatives, but will resume tagging if the status changes to Active.

##### What is the value that Bizible is using to tag? {#what-is-the-value-that-bizible-is-using-to-tag}

At the end of the destination URL, Bizible is adding the parameter &_bl={creativeId}, where the {creativeId} is the Creative Id from LinkedIn. With the Creative Id, Bizible can also determine the Campaign Id since LinkedIn has a pretty basic ads structure since each Creative can only belong to one Campaign.

##### What happens with my old creative once Bizible creates a new version of it? {#what-happens-with-my-old-creative-once-bizible-creates-a-new-version-of-it}

When Bizible recreates a Share and places it in a new Creative, the old Creative get archived. This is also why Bizible will not tag archived Campaigns or Creatives - it would otherwise loop with Bizible trying to tag it indefinitely.

##### The destination URL of the ad you created doesn’t match with my original ad. {#the-destination-url-of-the-ad-you-created-doesn-t-match-with-my-original-ad}

Bizible needs to add the tracking parameters to a resolved URL, but the URL that is presented in the API can potentially be a shortened URL without all parameters present. In order to get around that issue, Bizible looks for shortened URLs prior to re-creating an add, resolves it, then creates the new ad with the resolved URL and all of its parameters, allowing Bizible to add tags.

##### Are you tagging all of my ads? I don’t see the bl parameter on all of my landing pages? {#are-you-tagging-all-of-my-ads-i-don-t-see-the-bl-parameter-on-all-of-my-landing-pages}

We have observed that some marketers will put an image link into the destination URL, which Bizible cannot tag, so we search for the URL within the ad content. If Bizible has permissions to tag shortened URLs, we will expand the URL and tag that, but due to LinkedIn’s copy structure, it automatically gets shortened within the text. The tag will live within the LinkedIn shortened URL, which will appear in the touchpoint’s Ad Content field rather than in the Landing Page - Raw field.

##### Oh no, someone on my team accidentally cloned a share. Can I pause it? {#oh-no-someone-on-my-team-accidentally-cloned-a-share-can-i-pause-it}

No worries. Bizible will programmatically check for shares that are no longer unique, meaning that it had since been copied into a different Creative. Once that copy has been detected, Bizible will follow the usual flow to tag and create new ads.

##### My ad was pending review earlier. Why is it pending review again after Bizible tagged it? {#my-ad-was-pending-review-earlier-why-is-it-pending-review-again-after-bizible-tagged-it}

LinkedIn requires that all ads that are created or modified go through the normal security process before it is posted. Bizible tries to intercept the ad as quickly as possible, as it scans for new ads every 6 hours but with LinkedIn’s additional step, it can delay the launch by a few hours.

##### There are 2 URLs on my ad. Which one gets tagged? {#there-are-urls-on-my-ad-which-one-gets-tagged}

Both. Bizible’s integration allows us to tag the destination URL from the click through image in the ad, but also automatically updates the shortened URL in the ad description.  
  
![](assets/five.png)

##### I’ve connected my LinkedIn ads account. Why isn’t Bizible tagging my links? {#i-ve-connected-my-linkedin-ads-account-why-isn-t-bizible-tagging-my-links}

The connected LinkedIn user needs to have proper editing access, which means the user needs to be an Account Manager, Campaign Manager, or Creative Manager.

##### How do I know if my creative will be copied? Can I see if my creatives are using the same share? {#how-do-i-know-if-my-creative-will-be-copied-can-i-see-if-my-creatives-are-using-the-same-share}

The share Id isn't provided in a LinkedIn report, so there isn't a clear and obvious way to check for creative-to-share mappings. If you suspect a creative might be a copy, you can manually check by opening the ad from within your LinkedIn Campaign manager--this will open the ad in a new tab and you'll find the share Id in the URL.

![](assets/six.png)

