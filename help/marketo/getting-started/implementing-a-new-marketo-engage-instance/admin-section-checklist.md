---
description: Set up the Admin section for your new Marketo Engage instance.
title: New Instance Best Practices - Admin Section Checklist
feature: Getting Started
exl-id: 4fa90a32-7e97-404c-90b1-90d05c2561d0
---
# New Instance Best Practices: Admin Section Checklist {#new-instance-best-practices-admin-section-checklist}

As a new admin navigating a fresh Marketo Engage instance, apply the checklist below to help guide you through the implementation process. As with all of these guides, you can also [download the checklists](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) and track your progress.

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
    <td><li>Review the prebuilt roles and confirm what permissions/access each role has.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#create-a-new-role" target="_blank">Create a new role</a> or <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#edit-a-role" target="_blank">edit the roles</a> based on your organization's needs.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions#assign-roles-to-a-user" target="_blank">Assign users to the appropriate roles</a>. The users must be added to the subscription in Adobe Admin Console before granting their roles in 'Roles.' Refer to the Users section in the <a href="/help/marketo/getting-started/initial-setup/user-setup.md">Initial Setup checklist</a>.</li>
    <li>After assigning the roles for users, review the number of users per role.</li>
    <li>Implement a unique role for each API user for easy troubleshooting.</li></td>
  </tr>
  <tr>
    <td>Sandbox (if applicable)</td>
    <td><li>Review the categories above for your <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/marketo-sandbox.md" target="_blank">sandbox</a>.</li></td>
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
    <td>Workspaces & Partitions (if applicable)</td>
    <td><li>Determine the number of<a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html" target="_blank"> workspaces</a> and/or partitions that your organization needs to have and <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html" target="_blank">how many users have access to each workspace.</a></li>
    <li>Define the primary purpose of each workspace and partition.</li>
    <li>Define the relationship between your workspaces and partitions.</li></td>
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
<tbody>
  <tr>
    <td>Smart Campaign Settings</td>
    <td><li>Add a <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html" target="_blank">restriction on Smart Campaign size</a>, preventing accidentally emailing your entire database.</li></td>
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
    <td><li>Implement <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html" target="_blank">communication limits</a>.</li>
    <li>Determine if your business requires a policy on communication limits.</li></td>
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
    <td><li>Define how to use <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html" target="_blank">channels</a>.</li></td>
  </tr>
  <tr>
    <td>Tags</td>
    <td><li>Define how to use <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html" target="_blank">tags</a>.</li></td>
  </tr>
  <tr>
    <td>Calendar<br> 
    (if applicable)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html" target="_blank">Issue Marketing Calendar seats</a> to those who need access.</li>
    <li>Set up the <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/navigating-the-marketing-calendar.html" target="_blank">Calendar</a>.</li></td>
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
    <td><li>Implement a naming convention for <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html" target="_blank">custom fields</a> (for example, beginning with "MKTO").</li>
    <li>Be selective about the fields you sync. The more fields you sync, the slower the sync cycle will be.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html" target="_blank">Block updates to fields</a> you want written to one time (e.g., original lead source, original lead source detail, first touch UTM fields, etc.).</li></td>
  </tr>
  <tr>
    <td>Custom Activities</td>
    <td><li>Define <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html" target="_blank">Custom Activities</a> that are specific to your business.</li></td>
  </tr>
  <tr>
    <td>Custom Objects</td>
    <td><li>Review how many <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html" target="_blank">Custom Objects</a> you need.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html" target="_blank">Sync those Custom Objects</a> to your CRM.</li></td>
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
    <td><li>Identify the permissions you need to access your CRM.</li>
    <li>Identify your CRM admin for troubleshooting.</li></td>
  </tr>
  <tr>
    <td>Web Services</td>
    <td><li>Determine the users/apps that can make <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/create-an-api-only-user.html" target="_blank">API calls</a> in your instance.</li>
    <li>Review all apps that will make API calls and determine if an increase or decrease in API calls is needed.</li></td>
  </tr>
  <tr>
    <td>LaunchPoint</td>
    <td><li>Set up <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/add-adobe-connect-as-a-launchpoint-service.html" target="_blank">LaunchPoint</a> services for your business. Each LaunchPoint should be paired with a unique API user to aid with troubleshooting.</li></td>
  </tr>
  <tr>
    <td>Interactive Webinars (if applicable)</td>
    <td><li>For creating Interactive Webinars, the Marketo Engage built-in webinar feature, <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/events/interactive-webinars/user-and-license-management" target="_blank">add users to the 'User' section</a> on the Interactive Webinar tab.</li>
    <p><img src="assets/note-icon.png" alt="note icon"> NOTE: Interactive Webinars is only provisioned to Production instances.</td>
  </tr>
  <tr>
    <td>Adobe Dynamic Chat (if applicable)</td>
    <td><li>Assign users to <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-dynamic-chat-access-to-marketo-role" target="_blank">'Access Dynamic Chat' roles</a> in Marketo Engage > Admin > Users & Roles.</li></td>
  </tr>
  <tr>
    <td>Sales Insight (if applicable)</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide#set-up-marketo-sales-account" target="_blank">Set up Sales Insight Action</a> in Sales Insight > Actions Config.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html#invite-individual-users-to-msi-actions" target="_blank">Issue seats</a> to appropriate users.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html" target="_blank">Configure the API</a>.</li>
    <li>Customize the <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html" target="_blank">lead scores</a>.</li></td>
  </tr>
  <tr>
    <td>Sales Connect (if applicable)</td>
    <td><li>Invite the appropriate Marketo Engage admins to the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/accessing-your-new-sales-connect-instance" target="_blank">Sales Connect instance</a>.</li>
    <li>Complete the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/marketo-sales-connect/getting-started/getting-started-guide-for-sales-connect-admins" target="_blank">additional Sales Connect admin setup</a> in Sales Connect and Salesforce.</li></td>
  </tr>
  <tr>
    <td>Webhooks (if applicable)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/additional-integrations/create-a-webhook.html" target="_blank">Create any required Webhooks</a> for your business.</li>
    </td>
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
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/enable-or-disable-treasure-chest-features.html" target="_blank">Enable Treasure Chest</a> to experiment with piloting features.</li>
    <li>Determine the features you want to turn on or off.</li></td>
  </tr>
  <tr>
    <td>Campaign Inspector </td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/settings/campaign-inspector.html" target="_blank">Turn on Campaign Inspector</a> to view all your Smart Campaigns in one place.</li></td>
  </tr>
</tbody>
</table>
