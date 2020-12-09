---
unique-page-id: 1146999
description: Tokens for Interesting Moments - Marketo Docs - Product Documentation
title: Tokens for Interesting Moments
---

# Tokens for Interesting Moments {#tokens-for-interesting-moments}

>[!PREREQUISITES]
>
>* Learn to use the [Interesting Moment flow step](../../../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md).
>* Learn more about [tokens](http://docs.marketo.com/display/docs/tokens).
>

## Available Tokens {#available-tokens}

Check out [Tokens Overview](../../../../../../product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) to see all the tokens you can put into an interesting moment.

## Trigger Tokens {#trigger-tokens}

Based on the trigger used in a smart campaign, additional Trigger Tokens are made available.

* `{{trigger.Trigger Name}}` which is always the actual trigger itself. For example: Clicks Link in Email.
* `{{trigger.Name}}` is the name of the asset that triggered the campaign. For example: Clicks Link on Webpage is the URL itself, subject for Salesforce triggers, etc.
* Additional triggers are available based on constraints, which are listed below:

<table> 
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
  </tr> 
  <tr> 
   <td>Clicks Link in Email</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Email Bounces Hard</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Email Bounces Soft</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Email Is Delivered</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Opens Email</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Unsubscribes from Email</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Clicks Link in Sales Email</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Sent Sales Email</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Opens Sales Email</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
  </tr> 
  <tr> 
   <td>Sales Email Received</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
  </tr> 
  <tr> 
   <td colspan="1">Sales Email Bounced</td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tick)"></td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tick)"></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
  <tr> 
   <td>Fills Out Form</td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><br></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><img src="assets/check.svg" alt="(tick)"></td> 
   <td><br></td> 
   <td><p><br></p></td> 
  </tr> 
  <tr> 
   <td colspan="1">Visits Web Page*</td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tick)"></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><img src="assets/check.svg" alt="(tick)"></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
   <td colspan="1"><br></td> 
  </tr> 
 </tbody> 
</table>

>[!NOTE]
>
>If it doesn't have a check ![(tick)](assets/check.svg) then it would return an empty string (nothing) in the interesting moment.

&#42;The Trigger **Visits Web Page** has a few additional tokens:

* `{{trigger.Referrer}}`
* `{{trigger.Search Engine}}` 
* `{{trigger.Search Query}}`

>[!TIP]
>
>Always test out your interesting moments to ensure they render the way you intend.
>
>Also, make sure it's interesting to the Sales person, not just to you. ![(wink)](assets/wink.svg)>

