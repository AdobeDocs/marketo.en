---
description: NEW AREA - Marketo Docs - Product Documentation
title: NEW AREA
hide: yes
hidefromtoc: yes
feature: Getting Started
---
# NEW AREA: Admin Checklist {#new-area-admin-checklist}

Opening blurb

## Roles {#roles}

<table>
<thead>
  <tr>
    <th>Area </th>
    <th>Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Roles </td>
    <td><li>Review the prebuilt roles and confirm what permissions/access each role has.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#create-a-new-role">Create a new role</a> or <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#edit-a-role">edit the roles</a> based on your organization's needs and how often users log in.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.html#assign-roles-to-a-user">Assign users to the appropriate roles</a>.</li>
    <li>After assigning the roles for users, review the # of users per role.</li>  <li>Implement a unique role for each API user for easy troubleshooting.</li></td>
  </tr>
  <tr>
    <td>Documentation </td>
    <td>Define users and roles for your organization. <br>Define your process for adding a new user/admin. </td>
  </tr>
  <tr>
    <td>Sandbox (if applicable) </td>
    <td>Review the categories above for your sandbox if you have one. </td>
  </tr>
</tbody>
</table>

## Workspaces & Partitions {#workspaces-partitions}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Workspaces &amp; Partitions </td>
    <td><li>Determine the number of<a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/understanding-workspaces-and-person-partitions.html"> workspaces</a> and/or partitions that your organization needs to have and <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/workspaces-and-person-partitions/allow-user-access-to-a-workspace.html">how many users have access to each workspace.</a></li>
    <li>Define the primary purpose of each workspace and partition.</li>
    <li>Define the relationship between your workspaces and partitions.</li></td>
  </tr>
  <tr>
    <td>Documentation </td>
    <td><li>Document how workspaces are defined, and how does that relate to database partitions (i.e. a Global workspace that sees everyone, vs. business sectors).</li>
    <li>Import new records to appropriate partition.</li>
    <li>Define the value in CRM that place users in the appropriate partition.</li></td>
  </tr>
</tbody>
</table>

## Smart Campaign Settings {#smart-campaign-settings}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Smart Campaign Settings </td>
    <td><li>Add a <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-person-restrictions-for-smart-campaigns.html">restriction on Smart Campaign size</a>, preventing accidentally emailing the whole database.</li>
    <li>Enable person restrictions for Smart Campaigns</li></td>
  </tr>
</tbody>
</table>

## Email Settings {#email-settings}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Email Defaults</td>
    <td><li>Under Branding Domain, select your domain and add your Email CNAME. This should be in the form: [EmailTrackingCNAME].[CompanyDomain].com.</li></td>
  </tr>
  <tr>
    <td>SPF/DKIM</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/set-up-spf-and-dkim-for-your-email-deliverability.html">Set up SPF &amp; DKIM</a> for email deliverability.</li></td>
  </tr>
</tbody>
</table>

## Communication Limits {#communication-limits}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Communication Limits</td>
    <td><li>Place <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/email-setup/enable-communication-limits.html">Communication Limits</a>.</li>
    <li>Determine if your business requires a policy on Communication Limits.</li></td>
  </tr>
</tbody>
</table>

## Tags {#tags}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Channels</td>
    <td><li>Define how to use <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/create-a-program-channel.html">channels</a>.</li></td>
  </tr>
  <tr>
    <td>Tags </td>
    <td><li>Define how to use <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html">tags</a>.</li></td>
  </tr>
  <tr>
    <td>Calendar (if applicable) </td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/marketing-calendar/understanding-the-calendar/issue-revoke-a-marketing-calendar-license.html">Issue Marketing Calendar seats</a> to those who need access.</li> 
    <li>Set up <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/tags/managing-tag-values.html">Calendar</a>.</li></td>
  </tr>
</tbody>
</table>

## Database Management {#database-management}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Field Management</td>
    <td><li>Implement naming convention for <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo.html" target="_blank" rel="noopener noreferrer">custom fields.</a> For example, begin with "MKTO".</li>
    <li>Be selective about the fields you sync. The more fields that you sync, the slower the sync cycle will be.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/field-management/block-updates-to-a-field.html" target="_blank" rel="noopener noreferrer">Block updates to fields</a> you want written to once (i.e., original lead source, original lead source detail, first touch UTM fields, etc.).</li></td>
  </tr>
  <tr>
    <td>Custom Activities </td>
    <td><li>Define <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-activities/understanding-custom-activities.html" target="_blank" rel="noopener noreferrer">Custom Activities</a> that are specific to your business.</li></td>
  </tr>
  <tr>
    <td>Custom Objects </td>
    <td><li>Review how many <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.html" target="_blank" rel="noopener noreferrer">Custom Objects</a> you need.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/sfdc-sync-custom-object-sync.html" target="_blank" rel="noopener noreferrer">Sync those Custom Objects to your CRM</a>.</li></td>
  </tr>
</tbody>
</table>

## Integrations {#integrations}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CRM</td>
    <td><li>Initiate CRM Sync. Choose from the following, depending on the CRM your company uses: <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/salesforce-sync-setup.html" target="_blank" rel="noopener noreferrer">Salesforce</a> | <a href="https://experienceleague.adobe.com/docs/marketo-learn/tutorials/integrations/microsoft-dynamics-sync-setup.html" target="_blank" rel="noopener noreferrer">Microsoft Dynamics</a>.</li>
    <li>Identify the type of access you need to access your CRM.</li>
    <li>Identify your CRM admin for troubleshooting.</li></td>
  </tr>
  <tr>
    <td>Sales Insight (if applicable)</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html" target="_blank" rel="noopener noreferrer">Set up Sales Insight.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/actions/getting-started/sales-insight-actions-admin-setup-guide.html#invite-individual-users-to-msi-actions" target="_blank" rel="noopener noreferrer">Issue seats to appropriate users.</a></li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.html" target="_blank" rel="noopener noreferrer">Configure the API</a>.</li>
    <li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/marketo-sales-insight/msi-for-salesforce/features/stars-and-flames/priority-urgency-relative-score-and-best-bets.html" target="_blank" rel="noopener noreferrer">Customize the lead scores.</a></li></td>
  </tr>
</tbody>
</table>
