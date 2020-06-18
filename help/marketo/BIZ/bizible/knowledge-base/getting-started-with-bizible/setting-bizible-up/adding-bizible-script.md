---
unique-page-id: 18874795
description: Adding Bizible Script - Bizible - Product Documentation
title: Adding Bizible Script
---

# Adding Bizible Script {#adding-bizible-script}

Adding Bizible Script - Bizible - Product Documentation

Bizible JavaScript that you'd like tracked by Bizible should be added to all web properties as soon as possible. Once the JavaScript is deployed, Bizible will start collecting your digital data. This article outlines the methods for deploying Bizible JavaScript and additional considerations to take into account.

When getting started with Bizible, there are two ways you can add the Bizible JavaScript to your website:

* `Hard-Coding`
* `Tag Management Systems  
  
  `

### What's in this article? {#what-s-in-this-article}

[Hard-Coding](#addingbiziblescript-hard-coding)  
[Tag Management Systems](#addingbiziblescript-tagmanagementsystems)  
[Additional Considerations](#addingbiziblescript-additionalconsiderations)  
[Forms to Pay Extra Attention To](#addingbiziblescript-formstopayextraattentionto)  
[Testing Bizible JavaScript](#addingbiziblescript-testingbiziblejavascript)

#### Hard-Coding {#addingbiziblescript-hard-coding}

As a best practice, we strongly recommend hardcoding Bizible JavaScript to your web properties. To hardcode the script, you'll need to place the script before the closing </head> on every page of your site.

**<script type="text/javascript" src="//cdn.bizible.com/scripts/bizible.js" async=""></script>**

Hardcoding the JavaScript into the <head> of your pages ensures the Bizible script will load first and referral information isn't missed. The Bizible JavaScript loads asynchronously. If hardcoding, the JavaScript must be manually added to Marketing Automation. Click [here](http://docs.marketo.com/x/kwAgAQ) to check out the related articles.

>[!TIP]
>
>Learn how to make sure your script is [GDPR compliant](http://docs.marketo.com/x/FQAfAg).

#### Tag Management Systems {#addingbiziblescript-tagmanagementsystems}

If adding Bizible JavaScript via hardcoding isn't possible, another option is to add the Bizible script using a Tag Management System such as Google Tag Manager (GTM) or Tealium.

Please note that using tag management systems to deploy Bizible JS can result in a potential 5-10% data loss due to script load time latency. Essentially, if the tag management tool does not load quickly enough, Bizible JS also cannot load quickly enough and could lose first referrer information.

A common practice is to deploy Bizible JS via a tag management tool until timing/resourcing is better to move to hardcoding.

To add Bizible script through a tag management solution, you'll need to create a new tag and add our JavaScript within it. Apply this tag to all pages on your website that you want to be tracked.

Bizible recommends that any page view should cause the tag to fire. Additionally, it's best to give Bizible the highest priority in the firing order and make sure there are no synchronous scripts in front of the Bizible tag in order to ensure the highest data quality.

More information [can be found here](http://docs.marketo.com/x/rQEgAQ).

#### Additional Considerations {#addingbiziblescript-additionalconsiderations}

Bizible JavaScript is domain-based so it is automatically able to handle any subdomains as long as the JavaScript is on the pages and the root domain is the same as the domain used to create the Bizible account.

However, if you are using any separate or international domains, be sure to let your Bizible Consultant know. The domain(s) need to be manually added to your account on the Bizible end so that Bizible knows to tie the additional domains’ data to your account. So, please send any separate/international domains to your Bizible Consultant.

If you use any third party pages, have a conversation about your use case with your Bizible Consultant. In general, you’ll want to know if you can add a custom version of Bizible’s JavaScript to track those pages if appropriate. If this isn’t possible, tracking via CRM Campaign touchpoints will be explored with your Bizible Consultant.

Do you have any forms that should NOT be tracked by Bizible since they don't necessarily make sense for attribution (e.g., unsubscribe forms, customer logins, etc.,)? If so, you'll want to add the exclude code [in this article](http://docs.marketo.com/x/nwEgAQ) to each form

Do you have any non-secure pages? If so, you'll want to secure them as navigating between a secure/non-secure page will break the tracking session.

Be sure to have a conversation with your web team so they know Bizible JavaScript should always be on the appropriate web properties. If new pages/forms/sites are introduced, make sure deploying Bizible JavaScript is part of the protocol.

#### Forms to Pay Extra Attention To {#addingbiziblescript-formstopayextraattentionto}

**Multi-form submission**

* Issue: If you have multiple linked forms as part of a single form submission, it’s possible that the first form will generate a touchpoint even if the complete form is not submitted.
* Solution: You'll need to force one of the forms to report the user to Bizible based on cached data and discuss abandonment practices. Generally, [report user code](http://docs.marketo.com/x/eQEgAQ) can solve for this.

**Account login (not creation)**

* Issue: Bizible recommends not creating touchpoints for subsequent account logins, as these tend to dilute the attribution story.
* Solution: Add Exclude Code to the account/customer/partner login form.

>[!NOTE]
>
>We do recommend creating a touchpoint for the creation of an account or trial.

**Download of asset**

* Issue: If your assets are gated, Bizible will track downloads as form fills. If your assets are not gated, there are limitations to what we can report on without customization.
* Solution: Gate the asset if you’d like it to be tracked by Bizible JavaScript. If this is not an option and you’d still like a touchpoint for it, consider syncing a CRM Campaign instead.

**iFrames**

* Issue: iFrames essentially function as pages within pages.
* Solution: The Bizible JS must be deployed directly within the iFrame header in order for us to attach to the form correctly.

**Lightboxes**

* Lightboxes are typically pop-ups that contain iFrames
* Solution: the Bizible JS must be deployed within the header of that hosted iFrame.

**Multiple forms on a page**

* Issue: If there are multiple forms hosted on a page, you might not be able to tell which specific form was filled out with Bizible’s Form URL field.
* Solution: If you need to know which form was filled out, explore setting up dynamic URL hashing with your web team.

**Forms organized in <div> format**

* Issue: Bizible JS has a hard time recognizing forms organized in <div> format so custom code can be needed.
* Solution: These [report user templates](http://docs.marketo.com/x/eQEgAQ) can be used by your web dev team to add the needed code.

**Chat**

* Issue: If you use a chat provider, special handling may be required. 
* Solution: Bizible integrates with Drift, Olark, Livechat, LivePerson, and SnapEngage. All other platforms need to be tracked through CRM campaign membership.

**Second Domain**

* Issue: Bizible JavaScript is domain specific so extra steps need to be taken for any separate or international domains. Note that Bizible JS can handle subdomains on the same root domain.
* Solution: If you own multiple root domains, that you’d like to be tracked by Bizible be sure to add JS to the domains AND let your Bizible Consultant know which domains should be manually associated to your Bizible account.

#### Testing Bizible JavaScript {#addingbiziblescript-testingbiziblejavascript}

Your Bizible Consultant will help you to spot test the website to ensure that Bizible JavaScript is present across all pages. Part of this testing will be submitting a few form fills with clearly indicated test details to ensure that tracking returns properly.   
  
However, your Bizible Consultant is likely not as familiar with your website as your web team is. For this reason, it’s very important that your web team or other appropriate team, thoroughly checks the website especially if there are complex forms in use like the ones mentioned above. Your team will ultimately be responsible for ensuring that all needed web properties are properly tracking but if you are aware of any complex forms or situations, you are welcome to ask your Bizible Consultant for assistance in testing.   
  
To test a form yourself, please follow these steps:

1. Always use an incognito browser or clear your cache between each form submission test AND use a different email address each time.

   a. A best practice is to use a fake email that contains something indicating it is a test and the time of day. For example: [[email protected]](http://docs.marketo.com/cdn-cgi/l/email-protection)

1. Record the URL of the page you are submitting the form and the email used.
1. Locate the record created in your CRM (Lead or Contact) for that form submission and verify that a touchpoint was appropriately created.

   a. You can use a Bizible stock report such as Leads with Bizible Touchpoints or look at the Lead/Contact page layout if you chose to update your page layouts with Bizible details.

   b. Note that this could take some time for the data to process.

