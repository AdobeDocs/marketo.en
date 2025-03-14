---
description: Document the setup of your new Marketo Engage instance.
title: New Instance Best Practices - Document Your Setup
feature: Getting Started
exl-id: c64d25e8-564b-487d-824e-7fcbfbf5d8bb
---
# New Instance Best Practices: Document Your Setup {#new-instance-best-practices-document-your-setup}

Now that you've learned the key product areas to set up for a new Marketo Engage instance, the next step is to create documentation for your instance configuration and tech stack. Whether creating it via spreadsheet or a project management application, your documentation will be a great resource to track progress and record details, as well as keep your instance structured and sustainable for future marketers within your organization.

## Data {#data}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>List Import</td>
    <td><li>Gather a list of data sources that records will be pulled from to <a href="https://experienceleague.adobe.com/en/docs/marketo/using/getting-started/quick-wins/import-a-list-of-people" target="_blank">import into Marketo Engage</a>.</li>
    <li>If you are importing from multiple data sources, consider using Master Lists or <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/field-management/create-a-custom-field-in-marketo" target="_blank">creating a custom field</a> on the person record to denote the data source.</li></td>
  </tr>
  <tr>
    <td>Database Integration</td>
    <td><li>If leveraging the native sync between Marketo Engage and your CRM, carefully consider what fields you want to sync between systems. Not every field needs to be synced, so be strategic about your data flows.</li></td>
  </tr>
</tbody>
</table>

## Documentation {#documentation}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Users</td>
    <td><li>Document the <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user#add-a-user" target="_blank">current users</a> in your instance for safety reasons. The following details should be included at a minimum (and are all visible by going to Admin > Users & Roles):</li>
    <ul>
    <li>Name</li>
    <li>Email</li>
    <li>Login</li>
    <li>Role</li>
    <li>Access Expiration Date</li>
    <li>User Created Date</li>
    <li>Most Recent Log In Date</li></ul>
    <p><img src="assets/note-icon.png" alt="note icon"> NOTE: You can also expand on this to include documentation around roles/permissions.
    <p>
    <li>As a Marketo Engage Product Admin, develop an internal process to audit and update the Marketo Engage user list at a regular cadency. To make changes to the list of users in Adobe Admin Console, consider <a href="https://helpx.adobe.com/enterprise/using/users.html" target="_blank">bulk actions</a>, such as uploading a .CSV, using the User Management REST API, etc.</li></td>
  </tr>
  <tr>
    <td>Organization</td>
    <td><li>Document the agreed folder structure, standard naming conventions for programs, assets, etc., and the why behind the decisions made. <a href="https://experienceleague.adobe.com/en/docs/marketo-learn/tutorials/fundamentals/best-practices-to-organize-a-new-instance" target="_blank">Learn more about the best practices here.</a></li></td>
  </tr>
  <tr>
    <td>Changelog</td>
    <td><li>Create a changelog where you can document what's changing in your instance and the why of the modifications. <a href="https://experienceleague.adobe.com/en/docs/marketo-learn/auditing-an-inherited-instance/develop-an-instance-governance-guide" target="_blank">Learn more about the best practices here.</a></li></td>
  </tr>
  <tr>
    <td>Playbooks</td>
    <td><li>Create a User Playbook or Admin Playbook for internal users onboarding to the instance.</li></td>
  </tr>
  <tr>
    <td>Conversations with internal teams</td>
    <td><li>Align the internal marketing team's expectations of Marketo Engage with Marketo Engage's capabilities.</li>
    <li>Identify the teams that will be your stakeholders in the Marketo Engage instance and document their goals to achieve using Marketo Engage as a technology.</li></td>
  </tr>
  <tr>
    <td>Workspaces & Partitions (if applicable)</td>
    <td><li>Document how workspaces are defined, and how that relates to database partitions (e.g., a Global workspace that shows everyone vs. business sectors).</li>
    <li>Import new records to the appropriate partition.</li>
    <li>Define the value in your CRM that places users in the appropriate partition.</li></td>
  </tr>
</tbody>
</table>
