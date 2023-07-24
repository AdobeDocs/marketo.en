---
unique-page-id: 1146999
description: Trigger Tokens for Interesting Moments - Marketo Docs - Product Documentation
title: Trigger Tokens for Interesting Moments
exl-id: 666a6eed-c432-4088-b4f1-54c996eca64c
feature: Marketo Sales Insights
---
# Trigger Tokens for Interesting Moments {#trigger-tokens-for-interesting-moments}

>[!PREREQUISITES]
>
>Learn to use the [Interesting Moment flow step](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md).

## Available Tokens {#available-tokens}

Check out [Tokens Overview](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) to see all the tokens you can put into an interesting moment.

## Trigger Tokens {#trigger-tokens}

Based on the trigger used in a smart campaign, additional Trigger Tokens are made available.

* `{{trigger.Trigger Name}}` which is always the actual trigger itself. For example: Clicks Link in Email.
* `{{trigger.Name}}` is the name of the asset that triggered the campaign. For example: Clicks Link on Webpage is the URL itself, subject for Salesforce triggers, etc.
* Additional triggers are available based on constraints, which are listed below.

**Email Triggers**

<table style="table-layout:auto"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col>
  <col>
  <col>
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><br></th> 
   <th><code>{{trigger.Trigger Name}}</code></th> 
   <th><code>{{trigger.Name}}</code></th> 
   <th><code>{{trigger.Link}}</code></th> 
   <th><code>{{trigger.Subject}}</code></th> 
   <th><code>{{trigger.Category}}</code></th> 
   <th><code>{{trigger.Details}}</code></th> 
   <th><code>{{trigger.Web Page}}</code></th> 
   <th><code>{{trigger.Client IP Address}}</code></th> 
   <th><code>{{trigger.Sent By}}</code></th> 
   <th><code>{{trigger.Received By}}</code></th> 
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr> 
  <tr> 
   <td>Clicks Link in Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Email Bounces Hard</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Email Bounces Soft</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Email Is Delivered</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Opens Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
    <tr> 
   <td>Received Forward to Friend Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
    <tr> 
   <td>Sent Forward to Friend Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td>
  </tr> 
  <tr> 
   <td>Unsubscribes from Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

**Salesforce Triggers**

<table style="table-layout:auto"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col>
  <col>
  <col>
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><br></th> 
   <th><code>{{trigger.Trigger Name}}</code></th> 
   <th><code>{{trigger.Name}}</code></th> 
   <th><code>{{trigger.Link}}</code></th> 
   <th><code>{{trigger.Subject}}</code></th> 
   <th><code>{{trigger.Category}}</code></th> 
   <th><code>{{trigger.Details}}</code></th> 
   <th><code>{{trigger.Web Page}}</code></th> 
   <th><code>{{trigger.Client IP Address}}</code></th> 
   <th><code>{{trigger.Sent By}}</code></th> 
   <th><code>{{trigger.Received By}}</code></th> 
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr> 
  <tr> 
   <td>Clicks Link in Sales Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Is Sent Sales Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Opens Sales Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Sales Email Bounces</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Sales Email is Received</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
    <tr> 
   <td>Opportunity is Updated</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
    <tr> 
   <td>Owner Changes</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Person is Converted</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Person is Deleted from SFDC</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Person is Synced to SFDC</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Removed from Opportunity</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Removed from SFDC Campaign</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Activity is Logged</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Activity is Updated</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Added to Opportunity</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Added to SFDC Campaign</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Status is Changed in SFDC Campaign</td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

**Sales Connect Triggers**

<table style="table-layout:auto"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col>
  <col>
  <col>
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><br></th> 
   <th><code>{{trigger.Trigger Name}}</code></th> 
   <th><code>{{trigger.Name}}</code></th> 
   <th><code>{{trigger.Link}}</code></th> 
   <th><code>{{trigger.Subject}}</code></th> 
   <th><code>{{trigger.Category}}</code></th> 
   <th><code>{{trigger.Details}}</code></th> 
   <th><code>{{trigger.Web Page}}</code></th> 
   <th><code>{{trigger.Client IP Address}}</code></th> 
   <th><code>{{trigger.Sent By}}</code></th> 
   <th><code>{{trigger.Received By}}</code></th> 
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr> 
  <tr> 
   <td>Clicks Link in Sales Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Is Sent Sales Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Opens Sales Email</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Sales Email Bounces</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Sales Email is Received</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Is Added to Sales Campaign</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr>
   <td>Owner Changes</td> 
   <td>Is Removed From Sales Campaign</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Received Sales Call</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

**Miscellaneous**

<table style="table-layout:auto"> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col> 
  <col>
  <col>
  <col>
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <th><br></th> 
   <th><code>{{trigger.Trigger Name}}</code></th> 
   <th><code>{{trigger.Name}}</code></th> 
   <th><code>{{trigger.Link}}</code></th> 
   <th><code>{{trigger.Subject}}</code></th> 
   <th><code>{{trigger.Category}}</code></th> 
   <th><code>{{trigger.Details}}</code></th> 
   <th><code>{{trigger.Web Page}}</code></th> 
   <th><code>{{trigger.Client IP Address}}</code></th> 
   <th><code>{{trigger.Sent By}}</code></th> 
   <th><code>{{trigger.Received By}}</code></th> 
   <th><code>{{trigger.Referrer}}</code></th>
   <th><code>{{trigger.Search Engine}}</code></th>
   <th><code>{{trigger.Search Query}}</code></th>
   <th><code>{{trigger.Browser}}</code></th>
  </tr> 
  <tr> 
   <td>Fills Out Form</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Visits Web Page</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td>
  </tr> 
  <tr> 
   <td>Clicks Link on Web Page</td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.png" alt="check"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td>
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>If it doesn't have a check ![(tick)](assets/check.png) then it would return an empty string (nothing) in the interesting moment.

&#42;The Trigger **Visits Web Page** has a few additional tokens:

* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}`
* `{{trigger.Search Query}}`

>[!TIP]
>
>Always test out your interesting moments to ensure they render the way you intend.
>
>Also, make sure it's interesting to the Sales person, not just to you!
