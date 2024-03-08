---
description: NEW AREA - Marketo Docs - Product Documentation
title: NEW AREA
hide: yes
hidefromtoc: yes
feature: Getting Started
---
# NEW AREA: Admin Checklist {#new-area-admin-checklist}

Intro text.

## Roles {#roles}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Roles</td>
    <td><li>Review the prebuilt roles and confirm what permissions/access each role has.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#create-a-new-role">Create a new role</a> or <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#edit-a-role">edit the roles</a> based on your organization's needs and how often users log in.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#assign-roles-to-a-user">Assign users to the appropriate roles</a>.</li>
    <li>After assigning the roles for users, review the # of users per role.</li>  <li>Implement a unique role for each API user for easy troubleshooting.</li></td>
    <td></td>
  </tr>
  <tr>
    <td>Documentation</td>
    <td>Define users and roles for your organization. <br>Define your process for adding a new user/admin.</td>
    <td></td>
  </tr>
  <tr>
    <td>Sandbox (if applicable)</td>
    <td>Review the categories above for your sandbox if you have one.</td>
    <td></td>
  </tr>
</tbody>
</table>

## Workspaces & Partitions {#workspaces-partitions}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Workspaces &amp; Partitions </td>
    <td><li>Determine the number of<a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html"> workspaces</a> and/or partitions that your organization needs to have and <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html">how many users have access to each workspace.</a></li>
    <li>Define the primary purpose of each workspace and partition.</li>
    <li>Define the relationship between your workspaces and partitions.</li></td>
    <td></td>
  </tr>
  <tr>
    <td>Documentation</td>
    <td><li>Document how workspaces are defined, and how does that relate to database partitions (i.e. a Global workspace that sees everyone, vs. business sectors).</li>
    <li>Import new records to appropriate partition.</li>
    <li>Define the value in CRM that place users in the appropriate partition.</li></td>
    <td></td>
  </tr>
</tbody>
</table>

## Smart Campaign Settings {#smart-campaign-settings}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Smart Campaign Settings </td>
    <td><li>Add a <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html">restriction on Smart Campaign size</a>, preventing accidentally emailing the whole database.</li>
    <li>Enable person restrictions for Smart Campaigns</li></td>
    <td></td>
  </tr>
</tbody>
</table>

## Email Settings {#email-settings}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Email Defaults</td>
    <td><li>Under Branding Domain, select your domain and add your Email CNAME. This should be in the form: [EmailTrackingCNAME].[CompanyDomain].com.</li></td>
    <td></td>
  </tr>
  <tr>
    <td>SPF/DKIM</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.html">Set up SPF &amp; DKIM</a> for email deliverability.</li></td>
    <td></td>
  </tr>
</tbody>
</table>

## Communication Limits {#communication-limits}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Communication Limits</td>
    <td><li>Place <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html">Communication Limits</a>.</li>
    <li>Determine if your business requires a policy on Communication Limits.</li></td>
    <td></td>
  </tr>
</tbody>
</table>

## Tags {#tags}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Channels</td>
    <td><li>Define how to use <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html">channels</a>.</li></td>
    <td></td>
  </tr>
  <tr>
    <td>Tags </td>
    <td><li>Define how to use <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html">tags</a>.</li></td>
    <td></td>
  </tr>
  <tr>
    <td>Calendar (if applicable) </td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html">Issue Marketing Calendar seats</a> to those who need access.</li> 
    <li>Set up <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html">Calendar</a>.</li></td>
    <td></td>
  </tr>
</tbody>
</table>

## Database Management {#database-management}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Field Management</td>
    <td><li>Implement naming convention for <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html" target="_blank">custom fields.</a> For example, begin with "MKTO".</li>
    <li>Be selective about the fields you sync. The more fields that you sync, the slower the sync cycle will be.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html" target="_blank">Block updates to fields</a> you want written to once (i.e., original lead source, original lead source detail, first touch UTM fields, etc.).</li></td>
    <td></td>
  </tr>
  <tr>
    <td>Custom Activities </td>
    <td><li>Define <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html" target="_blank">Custom Activities</a> that are specific to your business.</li></td>
    <td></td>
  </tr>
  <tr>
    <td>Custom Objects </td>
    <td><li>Review how many <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html" target="_blank">Custom Objects</a> you need.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html" target="_blank">Sync those Custom Objects to your CRM</a>.</li></td>
    <td></td>
  </tr>
</tbody>
</table>

## Integrations {#integrations}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CRM</td>
    <td><li>Initiate CRM Sync. Choose from the following, depending on the CRM your company uses: <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/salesforce-sync-setup.html" target="_blank">Salesforce</a> | <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/microsoft-dynamics-sync-setup.html" target="_blank">Microsoft Dynamics</a>.</li>
    <li>Identify the type of access you need to access your CRM.</li>
    <li>Identify your CRM admin for troubleshooting.</li></td>
    <td></td>
  </tr>
  <tr>
    <td>Sales Insight (if applicable)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html" target="_blank">Set up Sales Insight.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html#invite-individual-users-to-msi-actions" target="_blank">Issue seats to appropriate users.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html" target="_blank">Configure the API</a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html" target="_blank">Customize the lead scores.</a></li></td>
    <td></td>
  </tr>
  <tr>
    <td>Landing Pages </td>
    <td>NOTE: Are you a Launch Pack customer? You can skip this step. Your consultant will provide you with an IT setup instructions document during your kickoff call. <br>Set up your landing page domain with a <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/edit-landing-page-settings.html" target="_blank">CNAME</a> and <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/edit-landing-page-settings.html" target="_blank">enter domain and page information</a>. This should be in the form: [LandingPageCNAME].[CompanyDomain].com <br>Choose a CNAME for your landing pages. Some examples: <br>* **go**.[CompanyDomain].com <br>* **www2**.[CompanyDomain].com <br>* **lp**.[CompanyDomain].com <br>TIP: Keep it short! Shorter URLs are easier to remember. We suggest "go" as the domain. <br>Add analytics tracking code (e.g. Google Analytics or Adobe Analytics) to your landing page templates. </td>
    <td><a href="https://docs.marketo.com/display/public/DOCS/Edit+Landing+Page+Settings">Edit Landing Page Settings</a></td>
  </tr>
  <tr>
    <td rowspan="2">Munchkin </td>
    <td rowspan="2">NOTE: If you are a Launch Pack customer, please skip this step. Your consultant will provide you with Munchkin code instructions in your IT setup instructions document. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.html" target="_blank">Add Munchkin tracking code</a> to your website. Munchkin code can be <a href="https://developers.marketo.com/javascript-api/lead-tracking/" target="_blank">hard-coded</a> or deployed via Google Tag Manager.</td>
    <td><a href="https://docs.marketo.com/display/public/DOCS/Add+Munchkin+Tracking+Code+to+Your+Website">Add Munchkin Track Code to Your Website</a> </td>
  </tr>
  <tr>
    <td><a href="https://developers.marketo.com/javascript-api/lead-tracking/">Lead Tracking</a> </td>
  </tr>
  <tr>
    <td>Web Services </td>
    <td>Enable <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.html" target="_blank">the IP Restrictions</a> if applicable. <br>Determine the users/apps that can make <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user.html" target="_blank">API calls</a> in your instance. <br>Review all the apps that will make API calls and determine if an increase or a cut is needed for the API calls.</td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.html#product-docs">Create an Allowlist for IP-Based API Access </a> </td>
  </tr>
  <tr>
    <td>Adobe Dynamic Chat(if applicable) </td>
    <td>For using <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.html" target="_blank">Dynamic Chat</a>, the native conversational engagement channel in Marketo Engage, you will proceed with the user permission setup following the steps below on <a href="https://adminconsole.adobe.com/" target="_blank">Adobe Admin Console</a>. <br> <br>Confirm if you have been granted an Adobe Product Admin role by your Adobe Org System Admin. Contact <a href="https://helpx.adobe.com/contact.html" target="_blank">Adobe Customer Care</a><a href="https://helpx.adobe.com/contact.html)." target="_blank">https://helpx.adobe.com/contact.html</a> to find out who at your organization has admin privileges in the console. <br>Accept <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html" target="_blank">the 'Dynamic Chat Product Admin' invite</a>. The <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html" target="_blank">welcome email</a> is sent when Dynamic Chat is enabled in your Marketo Engage instance and you are designated as a System Admin.  <br>Assign all appropriate users to Marketo Engage's product profile in Adobe Admin Console. <br>You cannot assign users' roles in Marketo Engage/Admin/Users &amp; Roles before adding them to a Product Profile.  <br>If an undesirable user is added to multiple product profiles, you must delete the user from all product profiles. Otherwise, they will still have access to Dynamic Chat. </td>
    <td> </td>
  </tr>
  <tr>
    <td>Launchpoint (if applicable) </td>
    <td>Set up any required <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html" target="_blank">LaunchPoint</a> services for your business.  <br>NOTE: Interactive Webinars is a built-in webinar feature with native integration to Adobe Connect. No additional integration is needed but your instance will need to <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html" target="_blank">sync to Adobe Connect as a LaunchPoint Service.</a>  </td>
    <td><a href="https://docs.marketo.com/display/public/DOCS/Additional+Integrations">Additional Integrations</a> </td>
  </tr>
  <tr>
    <td>Webhooks (if applicable)</td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-a-webhook.html" target="_blank">Create any required Webhooks</a> for your business.  </td>
    <td><a href="https://docs.marketo.com/display/public/DOCS/Create+a+Webhook">Create a Webhook</a> </td>
  </tr>
</tbody>
</table>

## Treasure Chest {#treasure-chest}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Item</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Treasure Chest</td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/enable-or-disable-treasure-chest-features.html" target="_blank">Enable Treasure Chest</a> to experiment with piloting features.  <br>Determine the features that you want to turn on or off.</td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Campaign Inspector </td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/campaign-inspector.html" target="_blank">Turn on Campaign Inspector</a> to view all your Smart Campaigns at once.</td>
    <td>Text</td>
  </tr>
</tbody>
</table>
