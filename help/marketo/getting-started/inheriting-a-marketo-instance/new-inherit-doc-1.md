---
description: Inherit Doc 1 - Marketo Docs - Product Documentation
title: Inherit Doc 1
hide: yes
hidefromtoc: yes
---
# Inherit Doc 1 {#inherit-doc-1}

Auditing an inherited instance can seem like a...

Did you inherit an existing Marketo Engage instance from another Admin? If so, this article is for you...

The checklist below has been put togther with input from Marketo Champions to help you get up to speed quickly in your inherited instance...

>[!TIP]
>
>If you're a new(er) Marketo Engage user and are not familiar with many of the terms, please check out the [Marketo Glossary](/help/marketo/getting-started/marketo-glossary.md){target="_blank"}.

## Users & Roles {#users-and-roles}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>Users</td> 
   <td><li>How many users are there?</li>
<li>Are there any users that should be expired?</li>
<li>Does your company have policies around deleting users?</li> 
<li>How many users have Admin permissions?</li>
<li>Should any of those users be changed to other roles?</li> 
<li>Who are the API users in this instance?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Roles</td> 
   <td><li>How many roles are there?</li>  
<li>What permissions/access does each role have? Should any be adjusted?</li>
<li>How many users are there per role?</li>
<li>How often are users logging in?</li>
<li>Does each API user have their own user role? If not, consider implementing this to make troubleshooting easier.</li> 
<li>Do your user roles and permissions align with your corporate data privacy policies?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Internal Documentation</td> 
   <td><li>Are users and roles clearly defined in your organization?</li>
<li>What is your process for adding a new user/admin?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Sandbox (if applicable)</td> 
   <td><li>Do you have a sandbox instance? If so, review the categories above for your sandbox.</li>
<li>Is Program Import linked with your sandbox?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Audit Trail {#audit-trail}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>Audit Trail</td> 
   <td><li>Who is working in the instance?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Workspaces & Partitions {#workspaces-and-partitions}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>Workspaces & Partitions</td> 
   <td><li>How many workspaces and/or partitions do you have?</li>
<li>What is the primary purpose of each workspace and partition?</li>
<li>Do they need to be audited or changed?</li>
<li>What is the relationship between your workspaces and partitions?</li>
<li>How many users have access to each workspace?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Internal Documentation</td> 
   <td><li>How are workspaces and partitions defined?</li>
<li>What is your process to add workspaces to your instance or add users to a workspace?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Smart Campaigns {#smart-campaigns}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>Smart Campaign Settings</td> 
   <td><li>Do you have a restriction on Smart Campaign size?</li>
<li>If not, consider adding one. We recommend limiting the smart campaign limits to 25% of your database to avoid overcommunication or processing your entire database in workflows this not only protects your brand but helps protect the performance of your instance.</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Communication Limits {#communication-limits}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>Communication Limits</td> 
   <td><li>Are there limits in place? Does your business have policies where communication limits might be necessary?</li>
<li>Adobe recommends limiting your communication to 1 per day and 3 per 7 days, with non-operational emails blocked.</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Tags {#tags}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>Tags</td> 
   <td><li>How many tags are there? How many tags are in use? Do any need to be added?</li>
<li>Are tags required within your programs?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Channels</td> 
   <td><li>How many channels are there? How many are in use?</li>
<li>Are all channel program statuses appropriate? Do they show progression within the program?</li>
<li>Are your channels related to specific program types?</li>
<li>Which statuses are considered a success for each channel? Do those align with your marketing goals?</li>
<li>Is the Operational channel being used appropriately?</li>
<li>For Advanced Report Builder (Revenue Cycle Explorer\RCE), is your channel analytics behavior set to align to your program practices incorporating period cost?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Marketing Calendar (if applicable)</td> 
   <td><li>How many calendar entry types are there? Are they all still relevant?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Database Management {#database-management}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>Field Management</td> 
   <td><li>How many fields are there? Click "Export Field Names" to review a list of your fields, custom fields, and their API names.</li>
<li>How many custom fields are there?</li>
<li>How many fields are being used? Select "Export Used By" in the Field Actions drop-down to review related assets of a field.</li>
<li>How many are synced between Marketo Engage and your CRM?</li>
<li>Are CRM fields synced to the appropriate objects?</li>
<li>Is there a custom view set for person detail? Should there be?</li>
<li>Do you have a naming convention for your fields based on source? If not, consider implementing this.</li>
<li>Are there any fields blocked? Be sure to understand why they are.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Custom Activities</td> 
   <td><li>Are there any custom activities?</li>
<li>If so, click through them to understand what activities aren't related to a Marketo form, email, or landing page.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Custom Objects</td> 
   <td><li>How many custom objects are there? How are they synced to your CRM?</li>
<li>How are these custom objects being utilized by your programs and list queries?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Integrations {#integrations}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>CRM</td> 
   <td><li>Which CRM are you syncing to? Salesforce? MS Dynamics? Veeva?</li>
<li>Is the custom sync or bi-directional? (KG: FIX GRAMMAR AND CHECK IMPORTANCE)</li>
<li>[Salesforce Only] Does your instance have Custom Sync Filters implemented? Contact Marketo Support to identify Custom Sync Filters or request a Custom Sync rule be implemented.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Landing Pages</td> 
   <td><li>What is the domain set as?</li>
<li>What is the fallback set as?</li>
<li>What is the homepage set as?</li>
<li>Is form prefill enabled?</li>
<li>Are personalized URLs enabled?</li>
<li>Are there rules set up for redirects?</li>
<li>Do you have domain aliases in place? Are you tracking through documentation how you're utilizing your domain aliases?</li>
<li>Is Secured Domains for Landing pages enabled? Confirm if your landing page assets contain a 'http' URL.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Munchkin</td> 
   <td><li>Is your Munchkin tracking code on your website (Not in Marketo)?</li>
<li>Is a "Do Not Track" Browser Request enabled?</li>
<li>Is your Munchkin API configured? If you're missing documentation on where the munchkin code is on your website, get started with a quick view by using the 'Web Analytics Report' in basic 'Analytics' to understand where the Munchkin code is placed across your website.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Web Services</td> 
   <td><li>Are IP Restrictions enabled? Should they be?</li>
<li>Which users/apps are making API calls in your instance?</li>
<li>Are you hitting or close to hitting your API limit? If so, consider increasing it or auditing your instance to bring those API calls down.</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Marketo Sales Insight (if applicable)</td> 
   <td><li>Has the <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md" target="_blank">MSI package been installed</a>?</li>
<li>Have you <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md" target="_blank">upgraded to the latest version of Sales Insight</a>?</li>
<li>Have you completed the Sales Insight configuration?</li>
<li>Have you <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-permission-set.md" target="_blank">given access to your users</a> based on the number of seats you've purchased?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Treasure Chest {#treasure-chest}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>Treasure Chest</td> 
   <td><li>What's turned on in the Treasure Chest?</li>
<li>Are there features that should be turned on or off?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Campaign Inspector</td> 
   <td><li>Is Campaign Inspector turned on?</li>
<li>If not, consider turning it on to easily identify which campaigns are active, syncing with your CRM, and/or deleting records.</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>

## Miscellaneous {#miscellaneous}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
   <th>Column 3</th>
  </tr> 
  <tr> 
   <td>Marketo Engage Status Updates</td> 
   <td><li>Is your instance signed up for Marketo Engage Status Updates?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Authorized Contacts</td> 
   <td><li>Have you set up the appropriate authorized contacts in the Support Portal?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Alerts</td> 
   <td><li>Are there any active alerts being sent out to internal teams from Marketo Engage?</li>
<li>If yes, are those alerts functioning appropriately?</li></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Notifications</td> 
   <td><li>Are you subscribed to appropriate admin notifications?</li></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>
