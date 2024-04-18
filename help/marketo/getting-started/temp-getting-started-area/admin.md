---
description: NEW AREA - Marketo Docs - Product Documentation
title: NEW AREA
hide: yes
hidefromtoc: yes
feature: Getting Started
exl-id: c7b068fc-a038-4f9c-a037-72440a1a864e
---
# NEW AREA: Admin Checklist {#new-area-admin-checklist}

Intro text.

## Roles {#roles}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Roles</td>
    <td><li>Review the prebuilt roles and confirm what permissions/access each role has.<br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#create-a-new-role" target="_blank">Create a new role</a> or <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#edit-a-role" target="_blank">edit the roles</a> based on your organization's needs and how often users log in.<br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html%22%20/l%20%22assign-roles-to-a-user" target="_blank">Assign users to the appropriate roles</a>. The users must be added to the subscription in Adobe Admin Console before granting their roles in Roles. Refer to the "Users' section in the 'Initial Setup' checklist [LINK]. <br>After assigning the roles for users, review the # of users per role.<br>Implement a unique role for each API user for easy troubleshooting.</td>
  </tr>
  <tr>
    <td>Documentation</td>
    <td>Define users and roles for your organization.<br>Define your process for adding a new user/admin.</td>
  </tr>
  <tr>
    <td>Sandbox (if applicable)</td>
    <td>Review the categories above for your sandbox if you have one.</td>
  </tr>
</tbody>
</table>

## Workspaces & Partitions {#workspaces-partitions}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Workspaces &amp; Partitions (if applicable)</td>
    <td>Determine the number of<a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html" target="_blank"> workspaces</a> and/or partitions that your organization needs to have and <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html" target="_blank">how many users have access to each workspace.</a><br>Define the primary purpose of each workspace and partition.<br>Define the relationship between your workspaces and partitions.</td>
  </tr>
  <tr>
    <td>Documentation</td>
    <td>Document how workspaces are defined, and how does that relate to database partitions (i.e. a Global workspace that sees everyone, vs. business sectors). <br>Import new records to appropriate partition.<br>Define the value in CRM that place users in the appropriate partition.</td>
  </tr>
</tbody>
</table>

## Smart Campaign Settings {#smart-campaign-settings}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Smart Campaign Settings</td>
    <td>Add a <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html" target="_blank">restriction on Smart Campaign size</a>, preventing accidentally emailing the whole database.</td>
  </tr>
  <tr>
    <td>Documentation</td>
    <td>Document how workspaces are defined, and how does that relate to database partitions (i.e. a Global workspace that sees everyone, vs. business sectors).  <br>Import new records to appropriate partition.<br>Define the value in CRM that place users in the appropriate partition.</td>
  </tr>
</tbody>
</table>

## Email Settings {#email-settings}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Email Defaults</td>
    <td>Under Branding Domain, select your domain and add your Email CNAME. This should be in the form: [EmailTrackingCNAME].[CompanyDomain].com.  <br><a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#create-a-support-ticket-with-admin-console" target="_blank">Contact Marketo Support</a> to secure it with an SSL Certificate provision. This process can take up to 3 business days to complete.</td>
  </tr>
  <tr>
    <td>SPF/DKIM</td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.html" target="_blank">Set up SPF &amp; DKIM</a> for email deliverability.</td>
  </tr>
  <tr>
  </tr>
  <tr>
  </tr>
</tbody>
</table>

## Communication Limits {#communication-limits}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Communication Limits</td>
    <td>Place <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html" target="_blank" rel="noopener noreferrer">Communication Limits</a>.<br>Determine if your business requires a policy on Communication Limits </td>
  </tr>
</tbody>
</table>

## Tags {#tags}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Channels</td>
    <td>Define how to use <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html" target="_blank" rel="noopener noreferrer">channels</a>.</td>
  </tr>
  <tr>
    <td>Tags</td>
    <td>Define how to use <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html" target="_blank" rel="noopener noreferrer">tags</a>.</td>
  </tr>
  <tr>
    <td>Calendar (if applicable)</td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html" target="_blank" rel="noopener noreferrer">Issue Marketing Calendar seats</a> to those who need access. <br>Set up <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.html" target="_blank" rel="noopener noreferrer">Calendar.</a></td>
  </tr>
</tbody>
</table>

## Database Management {#database-management}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Field Management</td>
    <td>Implement naming convention for <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html" target="_blank" rel="noopener noreferrer">custom fields.</a> For example, begin with "MKTO".<br>Be selective about the fields you sync. The more fields that you sync, the slower the sync cycle will be.<br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html" target="_blank" rel="noopener noreferrer">Block updates to fields</a> you want written to once (i.e., original lead source, original lead source detail, first touch UTM fields, etc.)</td>
  </tr>
  <tr>
  </tr>
  <tr>
    <td>Custom Activities</td>
    <td>Define <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html">Custom Activities</a> that are specific to your business.  </td>
  </tr>
  <tr>
    <td>Custom Objects</td>
    <td>Review how many <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html">Custom Objects</a> you need. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html">Sync those Custom Objects to your CRM</a>. </td>
  </tr>
</tbody>
</table>

## Integrations {#integrations}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CRM </td>
    <td>Initiate CRM Sync. Choose from the following, depending on the CRM your company uses: <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/salesforce-sync-setup.html">Salesforce</a> | <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/microsoft-dynamics-sync-setup.html">Microsoft Dynamics</a>. <br>Identify the type of access you need to access your CRM. <br>Identify your CRM admin for troubleshooting. </td>
  </tr>
  <tr>
    <td>Landing Pages</td>
    <td>NOTE: Are you a Launch Pack customer? You can skip this step. Your consultant will provide you with an IT setup instructions document during your kickoff call. <br>Set up your landing page domain with a <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/edit-landing-page-settings.html">CNAME</a> and <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/edit-landing-page-settings.html">enter domain and page information</a>. This should be in the form: [LandingPageCNAME].[CompanyDomain].com <br>Choose a CNAME for your landing pages. Some examples: <br>* **go**.[CompanyDomain].com <br>* **www2**.[CompanyDomain].com <br>* **lp**.[CompanyDomain].com <br><a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#create-a-support-ticket-with-admin-console">Contact Marketo Support</a> to start the process of provisioning an SSL Certificate. This process can take up to 3 business days to complete. <br>TIP: Keep it short! Shorter URLs are easier to remember. We suggest "go" as the domain. <br>Add analytics tracking code (e.g. Google Analytics or Adobe Analytics) to your landing page templates. </td>
  </tr>
  <tr>
    <td>Munchkin</td>
    <td>NOTE: If you are a Launch Pack customer, please skip this step. Your consultant will provide you with Munchkin code instructions in your IT setup instructions document. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-munchkin-tracking-code-to-your-website.html">Add Munchkin tracking code</a> to your website. Munchkin code can be <a href="https://developers.marketo.com/javascript-api/lead-tracking/">hard-coded</a> or deployed via Google Tag Manager.  </td>
  </tr>
  <tr>
    <td>Web Services</td>
    <td>Enable <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-an-allowlist-for-ip-based-api-access.html">the IP Restrictions</a> if applicable. <br>Determine the users/apps that can make <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user.html">API calls</a> in your instance. <br>Review all the apps that will make API calls and determine if an increase or a cut is needed for the API calls.  </td>
  </tr>
  <tr>
    <td>LaunchPoint</td>
    <td>Set up required <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html">LaunchPoint</a> services for your business. Each LaunchPoint should be paired with a unique API user to aid with troubleshooting.  </td>
  </tr>
  <tr>
    <td>Interactive Webinars (if applicable)</td>
    <td>NOTE: Interactive Webinars is only provisioned to Production instances. <br>For creating Interactive Webinars, the built-in webinar feature, <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/user-and-license-management">add users to the 'User' section</a> on the Interactive Webinar tab. </td>
  </tr>
  <tr>
    <td>Adobe Dynamic Chat (if applicable)</td>
    <td>For using <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.html">Dynamic Chat</a>, the native conversation automation channel in Marketo Engage, you will proceed with the user permission setup following the steps below on <a href="https://adminconsole.adobe.com/">Adobe Admin Console</a>. <br>Confirm if you have been granted an Adobe Product Admin role by your Adobe Org System Admin. Contact <a href="https://helpx.adobe.com/contact.html">Adobe Customer Care</a> to find out who at your organization has admin privileges in the console. <br>Accept <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">the 'Dynamic Chat Product Admin' invite</a>. The <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">welcome email</a> is sent when Dynamic Chat is enabled in your Marketo Engage instance and you are designated as a System Admin.  <br>Assign all appropriate users to Dynamic Chat's Product Profile in Adobe Admin Console. <br>If an undesirable user is added to multiple Product Profiles, you must delete the user from all product profiles. Otherwise, they will still have access to Dynamic Chat. <br>You can <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#edit-existing-permissions">edit Product Profiles in Dynamic Chat</a> and create a custom profile with a custom set of <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#list-of-permissions">permissions available within your subscription</a>. <br>Assign users to <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-dynamic-chat-access-to-marketo-role">'Access Dynamic Chat' roles</a> in Marketo Engage/Admin/Users &amp; Roles. </td>
  </tr>
  <tr>
    <td>Sales Insight (if applicable)</td>
    <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide#set-up-marketo-sales-account">Set up Sales Insight Action</a> in Sales Insight&gt;Actions Config.  <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html#invite-individual-users-to-msi-actions">Issue seats to appropriate users.</a>  <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html">Configure the API</a>. <br><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html">Customize the lead scores.</a> </td>
  </tr>
  <tr>
    <td>Sales Connect (if applicable)</td>
    <td><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/accessing-your-new-sales-connect-instance">Invite the appropriate Marketo Engage admins to the Sales Connect instance</a>. <br>Complete the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/getting-started-guide-for-sales-connect-admins">additional Sales Connect admin setup</a> in Sales Connect and Salesforce. </td>
  </tr>
</tbody>
</table>

## Treasure Chest {#treasure-chest}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Treasure Chest </td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/enable-or-disable-treasure-chest-features.html">Enable Treasure Chest</a> to experiment with piloting features.  <br>Determine the features that you want to turn on or off. </td>
  </tr>
  <tr>
    <td>Campaign Inspector </td>
    <td><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/campaign-inspector.html">Turn on Campaign Inspector</a> to view all your Smart Campaigns at once. </td>
  </tr>
</tbody>
</table>
