---
unique-page-id: 37356030
description: Email Tracking Parameter - Bizible - Product Documentation
title: Email Tracking Parameter
---

# Email Tracking Parameter {#email-tracking-parameter}

Email Tracking Parameter - Bizible - Product Documentation

Bizible’s Email Tracking Parameter allows marketers to treat email clicks as form submissions so that touchpoints get generated for those actions. Without using an email tracking parameter, click-throughs from an email are only treated as “web visits” until the user actually engages with the site through a form submission or a web chat.

### What's in this article? {#what-s-in-this-article}

[Use Cases](#emailtrackingparameter-usecases)  
[How It Works](#emailtrackingparameter-howitworks)  
[Tag Examples](#emailtrackingparameter-tagexamples)

#### Use Cases  {#emailtrackingparameter-usecases}

**Webinar Registration**: The Marketing team sends out an email invite with a single button to register for a webinar. Because the email already has the person’s information, the single click will auto-register them. The landing page contains the email tracking parameter so when they click through and land on the confirmation page, Bizible can capture the email address and treat the click-through as a form fill, which will generate a touchpoint.

**Content Download**: The Content Marketing team wants to promote a recent eBook that they’ve published with a direct download link from an email. When the email template is built, the download confirmation page will contain the email tracking parameter so that when they click through, Bizible can capture the email address. Without having to fill out a form on the site, Bizible can generate a touchpoint for the content download that occured via the email because it landed them on the confirmation page with the email tracking parameter.

#### How It Works {#emailtrackingparameter-howitworks}

When a visitor arrives on your site, Bizible expects to find a landing page with either an email address or Salesforce Id so we can associate that visit with a “form submission” and generate a touchpoint for that activity.

As the customer, you will build out an email template as you normally would. Once it’s time to add in the landing page for the action that you want to track, you'll need to determine either the token, or variable tag, or macro that your Marketing Automation platform accepts to dynamically display the value for each individual.

Bizible accepts the following values: Email Address, Salesforce Lead Id, or Salesforce Contact Id.

#### Tag Examples {#emailtrackingparameter-tagexamples}

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><p>Marketing Automation</p></th> 
   <th><p>Token / Tag / Macro </p></th> 
   <th><p>Example</p></th> 
   <th><p>Supporting Material</p></th> 
  </tr> 
  <tr> 
   <td><p>Marketo</p></td> 
   <td><p>{{lead.Email Address}} </p></td> 
   <td><p>https://engage.marketo.com/rs/460-TDH-945/images/BZ-B2B-Marketing-Attribution-101-ebook.pdf?mailId={{lead.EmailAddress}}</p></td> 
   <td><p>https://docs.marketo.com/display/public/DOCS/Tokens+Overview#TokensOverview-PersonTokens</p></td> 
  </tr> 
  <tr> 
   <td><p>Pardot</p></td> 
   <td><p>%%email%% </p><p>or</p><p>%%user_crm_id%%</p></td> 
   <td><p>https://engage.marketo.com/rs/460-TDH-945/images/BZ-B2B-Marketing-Attribution-101-ebook.pdf?mailId=%%email%%</p></td> 
   <td><p>https://help.salesforce.com/articleView?id=pardot_variable_tags_reference.htm&amp;type=5</p></td> 
  </tr> 
  <tr> 
   <td><p>Hubspot</p></td> 
   <td><p>(inserted via Editor)</p></td> 
   <td><p>n/a</p></td> 
   <td><p>https://knowledge.hubspot.com/cos-general/how-to-use-personalization-with-your-content</p></td> 
  </tr> 
  <tr> 
   <td><p>Act-On</p></td> 
   <td><p>(inserted via Message Composer)</p></td> 
   <td><p>n/a</p></td> 
   <td><p>https://connect.act-on.com/hc/en-us/articles/360033436074-How-to-Personalize-Email-Content-with-CRM-Data</p></td> 
  </tr> 
 </tbody> 
</table>

And finally, within Bizible, you will need to specify the tracking parameter so that Bizible can locate the email or Id value. The default is “mailId” as shown in the examples above and the screenshot below. Enter the value into your Settings in Bizible, then click **Save**.

![](assets/one-2.png)

