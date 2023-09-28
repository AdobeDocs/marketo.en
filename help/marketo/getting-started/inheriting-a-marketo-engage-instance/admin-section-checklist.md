---
description: Inherited Instance Admin Checklist - Marketo Docs - Product Documentation
title: Inherited Instance Admin Checklist
feature: Getting Started
exl-id: 4840d1a8-306b-4b53-917d-2262ae903a42
---
# Inherited Instance: Admin Section Checklist {#inherited-instance-admin-section-checklist}

The checklists below (subsequent checklists linked to at the bottom of each article) have been put together by Adobe Professional Services with input from Marketo Champions to help you get up to speed quickly. You can also [download the checklists](/help/marketo/getting-started/inheriting-a-marketo-engage-instance/assets/adobe-marketo-engage-inherited-instance-admin-checklist.xlsx) and track your progress.

>[!TIP]
>
>If you're a new(er) Marketo Engage user and are not familiar with many of the terms, please check out the [Marketo Engage Glossary](/help/marketo/getting-started/marketo-engage-glossary.md){target="_blank"}.

## Adobe Identity Management {#adobe-identity-management}

>[!NOTE] 
>
>This is only applicable to subscriptions onboarded to [Adobe Identity Management System (IMS)](/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md){target="_blank"}. If your Marketo Engage subscription has not onboarded Adobe IMS yet, proceed with the [legacy user roles and permissions experience](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"} in Marketo Engage > Admin > Users & Roles.

<table> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Subscription & Marketo Engage Product Admin</td> 
   <td><li>Has your Marketo Engage subscription been migrated to <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.md" target="_blank">Adobe IMS</a> yet? 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If so, have you been granted an 'Adobe Admin Console Product Admin' role by your 'Adobe Admin Console System Admin'? If you're not sure who in your organization has admin privileges in the console, contact <a href="https://helpx.adobe.com/contact.html" target="_blank">Adobe Customer Care</a>.</li>
<li>Have you accepted the 'Marketo Engage Product Admin' invite? The email is sent when the role is assigned in the Adobe Admin Console.
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If not, look for the <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/admin-setup.md#initial-setup" target="_blank">welcome email</a> in your inbox and accept the invite to activate your Adobe ID.</li></td>
  </tr>
  <tr> 
   <td>Product Profile</td> 
   <td><li>Are all appropriate users assigned to Marketo Engage's product profile in Adobe Admin Console?
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If not, make sure to <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md" target="_blank">add and/or remove users</a> from Marketo Engage product profiles in the Adobe Admin Console. You cannot assign users' roles in Marketo Engage > Admin > Users & Roles if they're added to a Product Profile.</li>
<p><img src="assets/note-icon.png" alt="note icon"> NOTE: If an undesirable user is added to multiple product profiles, you must remove the user from all product profiles. Otherwise, they'll still have access to Marketo Engage.</td>
  </tr>
  <tr> 
   <td>User Management API</td> 
   <td><li>Does your subscription use any Marketo User Management APIs?
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If so, you'll need to use <a href="https://www.adobe.io/apis/experienceplatform/umapi-new.html" target="_blank">Adobe IMS APIs</a> to invite, update, and delete users moving forward.</li>
<p><img src="assets/note-icon.png" alt="note icon"> NOTE: 'Role Management' remains in Marketo Engage, and Marketo User Management APIs can still be used for role management.</td>
  </tr>
 </tbody> 
</table>

## Users & Roles {#users-and-roles}

<table> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Users</td> 
   <td><img src="assets/note-icon.png" alt="note icon"> NOTE: If your subscription is on Adobe IMS already, proceed to the following user management review in Adobe Admin Console. Otherwise, go to Admin > Users & Roles > Users in Marketo Engage.
   <p>
   <li><a href="/help/marketo/product-docs/administration/users-and-roles/managing-marketo-users.md" target="_blank">How many users</a> are there?</li>
<li>Are there any users that should be <a href="/help/marketo/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.md#remove-a-user" target="_blank">removed</a>?</li>
<li>Does your company have policies around deleting users?</li> 
<li>How many users have <a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md" target="_blank">Admin permissions</a>?</li>
<li>Should any of those users be changed to <a href="/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md" target="_blank">other roles?</a></li> 
<li>Who are the <a href="/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user.md" target="_blank">API users</a> in this instance?</li></td>
  </tr>
  <tr> 
   <td>Roles</td> 
   <td><img src="assets/note-icon.png" alt="note icon"> NOTE: Whether you use Marketo with Adobe Identity or not, proceed with reviewing role permissions in Marketo Engage under Admin > Users & Roles > Roles.
   <p><li>How many roles are there?</li>  
<li>What <a href="/help/marketo/product-docs/administration/users-and-roles/descriptions-of-role-permissions.md" target="_blank">permissions/access</a> does each role have? Should any be adjusted?</li>
<li>How many users are there per role?</li>
<li>How often are users <a href="/help/marketo/product-docs/administration/audit-trail/user-login-history.md" target="_blank">logging in</a>?</li>
<li>Does each API user have their <a href="/help/marketo/product-docs/administration/users-and-roles/create-an-api-only-user-role.md" target="_blank">own user role</a>? If not, consider implementing this to make troubleshooting easier.</li> 
<li>Do your user roles and permissions align with your corporate data privacy policies for regulation compliance (e.g., <a href="https://gdpr-info.eu/" target="_blank">GDPR</a>)? Do the corporate data <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/privacy-management.md" target="_blank">privacy policies</a> allow users to download and share Marketo Engage user data? Is the permission business necessary?</li></td>
  </tr>
  <tr> 
   <td>Support Users</td> 
   <td><li>Have you set up the appropriate <a href="/help/marketo/getting-started/setup/setup-steps.md#set-up-your-authorized-support-contacts" target="_blank">authorized contacts</a> in the Support Portal?</li></td>
  </tr>
  <tr> 
   <td>Internal Documentation</td> 
   <td><li>Are users and roles clearly defined in your organization?</li>
<li>What is your process for adding a new user/admin?</li></td>
  </tr>
  <tr> 
   <td>Sandbox (if applicable)</td> 
   <td><li>Do you have a <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/marketo-sandbox.md" target="_blank">sandbox instance</a>?
   <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If so, review the categories above for your sandbox.</li>
<li>Is <a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.md" target="_blank">Program Import</a> linked with your sandbox?</li></td>
  </tr>
 </tbody> 
</table>

## Audit Trail {#audit-trail}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Audit Trail</td> 
   <td><li><a href="/help/marketo/product-docs/administration/audit-trail/audit-trail-overview.md" target="_blank">Who's working</a> in the instance?</li></td>
  </tr>
 </tbody> 
</table>

## Workspaces & Partitions {#workspaces-and-partitions}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Workspaces & Partitions</td> 
   <td><li>How many <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.md" target="_blank">Workspaces and/or Partitions</a> do you have?</li>
<li>What is the primary purpose of each Workspace and Partition?</li>
<li>Do either your <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/edit-a-workspace.md" target="_blank">Workspaces</a> or <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/edit-an-existing-person-partition.md" target="_blank">Partitions</a> need to be audited/changed?</li>
<li>What is the relationship between your Workspaces and Partitions?</li>
<li>How many users <a href="/help/marketo/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.md" target="_blank">have access</a> to each Workspace?</li></td>
  </tr>
  <tr> 
   <td>Internal Documentation</td> 
   <td><li>How are Workspaces and Partitions defined?</li>
<li>What is your process to add Workspaces to your instance or add users to a Workspace?</li></td>
  </tr>
 </tbody> 
</table>

## Smart Campaigns {#smart-campaigns}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Smart Campaigns</td> 
   <td><li><a href="/help/marketo/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.md" target="_blank">Do you have a restriction</a> on Smart Campaign size? 
   <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If not, consider adding one. We recommend limiting the Smart Campaign limits to 25% of your database to avoid overcommunication or processing your entire database in workflows; this not only protects your brand, but helps protect the performance of your instance.</li></td>
  </tr>
 </tbody> 
</table>

## Communication Limits {#communication-limits}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Communication Limits</td> 
   <td><li>Are there <a href="/help/marketo/product-docs/administration/email-setup/enable-communication-limits.md" target="_blank">communication limits</a> in place? Does your business have policies where communication limits might be necessary?</li>
<p><img src="assets/note-icon.png" alt="note icon"> NOTE: We recommend limiting your communication to 1 per day and 3 per 7 days, with <b>non</b>-<a href="/help/marketo/product-docs/email-marketing/general/functions-in-the-editor/make-an-email-operational.md" target="_blank">operational</a> emails blocked.</td>
  </tr>
 </tbody> 
</table>

## Tags {#tags}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Tags</td> 
   <td><li><a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-tags.md" target="_blank">How many tags</a> are there? How many tags are in use? Do any need to be added?</li>
<li>Are tags required within your programs?</li></td>
  </tr>
  <tr> 
   <td>Channels</td> 
   <td><li><a href="/help/marketo/product-docs/administration/tags/create-a-program-channel.md" target="_blank">How many channels</a> are there? How many are in use?</li>
<li>Are all <a href="/help/marketo/product-docs/administration/tags/hide-unhide-a-program-channel.md" target="_blank">channel program statuses appropriate</a>? Do they show progression within the program?</li>
<li>Are your channels related to specific program types?</li>
<li>Which statuses are considered a success for each channel? Do those align with your marketing goals?</li>
<li>Is the Operational channel being used appropriately?</li>
<li>For Advanced Report Builder (Revenue Cycle Explorer/RCE), is your channel analytics behavior set to align with your program practices incorporating period cost?</li></td>
  </tr>
  <tr> 
   <td>Marketing Calendar (if applicable)</td> 
   <td><li>How many <a href="/help/marketo/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.md" target="_blank">calendar entry types</a> are there? Are they all still relevant?</li></td>
  </tr>
 </tbody> 
</table>

## Database Management {#database-management}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Field Management</td> 
   <td><li>How many fields are there? 
   <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Click <a href="/help/marketo/product-docs/administration/field-management/export-a-list-of-all-marketo-api-field-names.md" target="_blank">Export Field Names</a> to review a list of your fields, custom fields, and their API names.</li>
<li>How many <a href="/help/marketo/product-docs/administration/field-management/create-a-custom-field-in-marketo.md" target="_blank">custom fields</a> are there?</li>
<li>How many fields are being used? 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Select <a href="/help/marketo/product-docs/administration/field-management/export-used-by-data-for-a-field.md" target="_blank">Export Used By</a> in the Field Actions drop-down to review related assets of a field.</li>
<li>How many fields are synced between Marketo Engage and your CRM?</li>
<li>Are CRM fields synced to the appropriate objects?</li>
<li>Is there a <a href="/help/marketo/product-docs/administration/settings/creating-a-custom-tab-for-the-person-detail-page.md" target="_blank">custom view set</a> for person detail? Should there be?</li>
<li>Do you have a naming convention for your fields based on source? 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If not, consider implementing this.</li>
<li>Are there any fields <a href="/help/marketo/product-docs/administration/field-management/block-updates-to-a-field.md" target="_blank">blocked</a>? 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If so, be sure to understand why they are.</li></td>
  </tr>
  <tr> 
   <td>Custom Activities</td> 
   <td><li>Are there any <a href="/help/marketo/product-docs/administration/marketo-custom-activities/understanding-custom-activities.md" target="_blank">custom activities</a>?
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If so, click through them to understand what activities aren't related to a Marketo form, email, or landing page.</li></td>
  </tr>
  <tr> 
   <td>Custom Objects</td> 
   <td><li>How many <a href="/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md" target="_blank">custom objects</a> are there? How are they synced to your CRM?</li>
<li>How are these custom objects being utilized by your programs and list queries?</li></td>
  </tr>
 </tbody> 
</table>

## Email {#email}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Email Default Settings</td> 
   <td><li>In Admin > Email, are all of your default settings up-to-date (e.g., <a href="/help/marketo/product-docs/administration/email-setup/change-the-default-from-email-and-from-label.md" target="_blank">"from" email/label</a>, <a href="/help/marketo/product-docs/administration/email-setup/add-multiple-branding-domains/edit-your-default-branding-domain.md" target="_blank">branding domain</a>, <a href="/help/marketo/product-docs/administration/email-setup/edit-the-unsubscribe-message.md" target="_blank">unsubscribe message</a>, etc.)?</li></td>
  </tr>
 </tbody> 
</table>

## Integrations {#integrations}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>CRM</td> 
   <td><li>Which CRM are you syncing to? Salesforce? MS Dynamics? Veeva?</li>
<li>Are you utilizing a <a href="https://nation.marketo.com/t5/product-blogs/instructions-for-creating-a-custom-sync-rule/ba-p/242758" target="_blank">custom sync</a>?</li>
<li>[Salesforce Only] Does your instance have Custom Sync Filters implemented? 
<p><img src="assets/note-icon.png" alt="note icon"> NOTE: Contact Marketo Support to identify Custom Sync Filters or request a Custom Sync Rule be implemented.</li></td>
  </tr>
  <tr> 
   <td>Landing Pages</td> 
   <td><li>What is the <a href="/help/marketo/product-docs/administration/settings/edit-landing-page-settings.md" target="_blank">domain set as</a>?</li>
   <li>What is the homepage set as?</li>
<li>What is the <a href="/help/marketo/product-docs/administration/settings/set-a-fallback-page.md" target="_blank">fallback set as</a>?</li>
<li>Is form prefill enabled?</li>
<li>Are <a href="/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/enable-personalized-urls-for-your-account.md" target="_blank">personalized URLs</a> enabled?</li>
<li>Are there rules set up for <a href="/help/marketo/product-docs/demand-generation/landing-pages/landing-page-actions/redirect-a-marketo-landing-page-to-another-page.md" target="_blank">redirects</a>?</li>
<li>Do you have domain aliases in place? Are you tracking how you're utilizing your domain aliases?</li>
<li>Is <a href="https://nation.marketo.com/t5/knowledgebase/setting-up-secured-domains-for-marketo-landing-pages-first-time/ta-p/250370" target="_blank">Secured Domains for Landing Pages</a> enabled? 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Confirm if your landing page assets contain a 'http' URL.</li></td>
  </tr>
  <tr> 
   <td>Munchkin</td> 
   <td><li>Is your <a href="/help/marketo/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.md" target="_blank">Munchkin tracking code</a> on your website (not a Marketo Engage Landing Page)?</li>
<li>Is a <a href="/help/marketo/product-docs/administration/settings/edit-do-not-track-browser-support-settings.md" target="_blank">Do Not Track</a> Browser Request enabled?</li>
<li>Is your <a href="https://developers.marketo.com/javascript-api/lead-tracking/" target="_blank">Munchkin API</a> configured? 
<p><img src="assets/tip-icon.png" alt="tip icon">TIP: If you're missing documentation on where the munchkin code is on your website, you can view all URLs by creating a <a href="/help/marketo/product-docs/reporting/basic-reporting/report-types/web-page-activity-report.md" target="_blank">Web Page Activity Report</a>.</li></td>
  </tr>
  <tr> 
   <td>Web Services</td> 
   <td><li>Are <a href="/help/marketo/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.md" target="_blank">IP Restrictions</a> enabled? Should they be?</li>
<li>Which users/apps are making API calls in your instance?</li>
<li>Are you hitting or close to hitting your API limit? 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If so, consider increasing it or auditing your instance to bring those API calls down.</li></td>
  </tr>
  <tr> 
   <td>Marketo Sales Insight (if applicable)</td> 
   <td><li>Has the <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/installation/install-marketo-sales-insight-package-in-salesforce-appexchange.md" target="_blank">MSI package been installed</a>?</li>
<li>Have you <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/upgrading/upgrading-your-msi-package.md" target="_blank">upgraded to the latest version of Sales Insight</a>?</li>
<li>Have you completed the Sales Insight configuration? <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Enterprise/Unlimited users <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-enterprise-unlimited.md" target="_blank">click here</a>, Professional users <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/configure-marketo-sales-insight-in-salesforce-professional-edition.md" target="_blank">click here</a>.</li>
<li>Have you <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/add-sales-insight-permission-set.md" target="_blank">given access to your users</a> based on the number of seats you've purchased?</li>
<li>Are <a href="/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/customize-stars-and-flames.md" target="_blank">Stars and Flames</a> customized?</li></td>
  </tr>
  <tr> 
   <td>Launchpoint (if applicable)</td> 
   <td><li>Which services have you configured (e.g., <a href="/help/marketo/product-docs/administration/additional-integrations/add-webex-as-a-launchpoint-service.md" target="_blank">BrightTALK</a>, <a href="/help/marketo/product-docs/administration/additional-integrations/connect-brighttalk-to-marketo.md" target="_blank">Zoom</a>, etc.)? Are any near their expiration?</li>
<li><a href="https://nation.marketo.com/t5/knowledgebase/viewing-your-number-of-api-calls-to-marketo/ta-p/254256" target="_blank">How many API calls</a> are your integrations using?</li>
<li>Do you have the right integrations in place for your use cases?</li></td>
  </tr>
  <tr> 
   <td>Webhooks (if applicable)</td> 
   <td><li><a href="/help/marketo/product-docs/administration/additional-integrations/create-a-webhook.md" target="_blank">What connections</a> have you set up?</li>
<li>Are any no longer in use?</li></td>
  </tr>
  <tr> 
   <td>Mobile Apps (if applicable)</td> 
   <td><li>Which <a href="/help/marketo/product-docs/mobile-marketing/admin/add-a-mobile-app.md" target="_blank">mobile apps</a> do you have?</li>
<li>Have any <a href="/help/marketo/product-docs/mobile-marketing/push-notifications/adding-a-new-test-device.md" target="_blank">test devices</a>  been added?</li></td>
  </tr>
 </tbody> 
</table>

## Treasure Chest {#treasure-chest}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Treasure Chest</td> 
   <td><li>What's turned on in the <a href="/help/marketo/product-docs/administration/settings/enable-or-disable-treasure-chest-features.md" target="_blank">Treasure Chest</a>?</li>
<li>Are there features that should be turned on or off?</li></td>
  </tr>
  <tr> 
   <td>Campaign Inspector</td> 
   <td><li>Is <a href="/help/marketo/product-docs/administration/settings/campaign-inspector.md" target="_blank">Campaign Inspector</a> turned on?
<br/>If not, consider turning it on to easily identify which campaigns are: active, syncing with your CRM, and/or deleting records.</li></td>
  </tr>
 </tbody> 
</table>

## Alerts and Updates {#alerts-and-updates}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th>
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Marketo Engage Status Updates</td> 
   <td><li>Is your instance subscribed to <a href="https://nation.marketo.com/t5/knowledgebase/how-to-subscribe-to-status-page-notifications/ta-p/296749" target="_blank">Marketo Engage Status Updates</a>?</li></td>
  </tr>
  <tr> 
   <td>Alerts</td> 
   <td><li>Are there any <a href="/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/send-alert.md" target="_blank">active alerts</a> being sent out to internal teams from Marketo Engage?</li>
<li>If yes, are those alerts functioning appropriately?</li></td>
  </tr>
  <tr> 
   <td>Notifications</td> 
   <td><li>Are you subscribed to appropriate admin <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md" target="_blank">notifications</a>?</li></td>
  </tr>
 </tbody> 
</table>

<br>&nbsp;

[Audit an Inherited Instance: Database ►](/help/marketo/getting-started/inheriting-a-marketo-engage-instance/database-checklist.md)
