---
unique-page-id: 18874592
description: Call Tracking Integration - Bizible - Product Documentation
title: Call Tracking Integration
---

# Call Tracking Integration {#call-tracking-integration}

Call Tracking Integration - Bizible - Product Documentation

Our integration with CallTrackingMetrics is intended to merge a web session with a phone call. A phone call gets treated as a form submission in Bizible's eyes. It gives credit to a web session that would have otherwise only been considered a web visit because there was no actual form submission.

### What's in this article? {#what-s-in-this-article}

[Call Tracking Explained](#calltrackingintegration-calltrackingexplained)  
[Before and After](#calltrackingintegration-beforeandafter)  
[How It Works](#calltrackingintegration-howitworks)  
[The Touchpoint](#calltrackingintegration-thetouchpoint)  
[Reporting](#calltrackingintegration-reporting)  
[FAQ](#calltrackingintegration-faq)  
[Partnerships](#calltrackingintegration-partnerships)

#### Call Tracking Explained {#calltrackingintegration-calltrackingexplained}

“Call Tracking” in the general sense is a product from companies such as CallTrackingMetrics, DiaglogTech, Invoca, or CallRail, to name a few. Unique phone numbers are shown to users based on the different marketing channels or campaigns they’re coming from. This allows marketers to see how those channels or campaigns are performing.

![](assets/1-1.png)

#### Before and After {#calltrackingintegration-beforeandafter}

Take a look at the flowchart below to see how Bizible used to handle phone calls without an integration with CallTrackingMetrics. The phone call that took place went untracked, so it was seen as a web session and no touchpoint was created for it. It wasn’t until the next visit where the user completed a form that a touchpoint was finally populated.  
  
With the integration, you can see that the web session was actually tied to a phone call. The next form fill ends up being a PostLC touch and is still tracked as part of the journey.

![](assets/2-1.png)

#### How It Works {#calltrackingintegration-howitworks}

CallTrackingMetrics has to do a little bit of development work on their end in order for this to work. With the javascript that they place on your site, CallTrackingMetrics can grab the _biz_uid from the Bizible cookie. This “BizibleId” is then stored by CallTrackingMetrics.  
  
When a visitor comes to your site and makes a phone call, it is the job of CallTrackingMetrics to push that data into Salesforce. Typically, a Salesforce Task is created that populates data such as phone number, subject, type, and now, the BizibleId.  
  
The BizibleId is a field that is installed with version 6.7+ of the Bizible Marketing Attribution package.  
  
Below is an example of a Task record with the BizibleId populated.

![](assets/3-1.png)

When Bizible finds a Task record with a known BizibleId value filled in, Bizible can map that user to a web session with the same BizibleId and attribute that session to a phone call instead of a web visit.

#### The Touchpoint {#calltrackingintegration-thetouchpoint}

When Bizible can import/download the task, we process that detail along with the web session. In most cases, it can be merged with a referrer or ad. In the example below, a visitor found the business through an Paid Google ad and made a phone call.  
  
The Touchpoint Type “Call” is pulled from the Task, from the screenshot above, which is also populated by CallTrackingMetrics when the Task is created.

![](assets/4-1.png)

#### Reporting {#calltrackingintegration-reporting}

Touchpoint Type values that Bizible typically pushes are Web Visit, Web Form, or Web Chat, but in the case of CallTrackingMetrics touchpoints, the touchpoint type will be Phone Call. This helps marketers see which channels draw in the most phone calls and generate revenue for their organization.

![](assets/5-1.png)

#### FAQ {#calltrackingintegration-faq}

**Why is my touchpoint type web visit?**

The Touchpoint Type is populated from the Task.Type field. If the Task.Type field is blank then Bizible will automatically set the Touchpoint Type as Web Visit. Once the Task.Type field is populated Bizible will read that value and populate the Touchpoint Type accordingly.

##### What other fields does the Touchpoint populate from the phone call? {#calltrackingintegration-whatotherfieldsdoesthetouchpointpopulatefromthephonecall}

Both the Touchpoint Type and Medium will contain the data that is pulled from the Task.Type. All other data points are pulled from the web tracking and javascript data.

##### How come this phone call isn't tied to a web session? {#calltrackingintegration-howcomethisphonecallisn'ttiedtoawebsession}

First, check the Task to make sure there is a BizibleId populated. If there is no value, then we will not and cannot create a touchpoint for it. This will need to be escalated with CallTrackingMetrics.

If there is a value, note that we only consider all web sessions to be 30 minutes. If a Google Ad was clicked on at 12:17pm (start of the session on the website), but the phone call did not occur until 1:05pm, we will not merge the web session and phone call. Rather, Bizible will create a separate Salesforce Task touchpoint to track the phone call, but will not have any web session data.  
  
![](assets/6-1.png)

#### Partnerships {#calltrackingintegration-partnerships}

Bizible currently has one official Call Tracking partner that has gone through the “official” integration process with us, which included co-marketing and product training. This one partner is CallTrackingMetrics.  
  
If you are interested in your Call Tracking vendor working with Bizible, please have them reach out to [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#58282a373c2d3b2c183a3122313a343d763b3735).
