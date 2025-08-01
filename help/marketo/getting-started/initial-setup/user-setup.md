---
description: Before you dive into your new Marketo Engage instance, you'll need to complete a few foundational steps for ongoing use. These steps include user account setup, support admin setup, and subscribing to ongoing system updates.
short-description: After completing the initial setup steps, learn how to establish foundational elements to ensure smooth ongoing usage.
title: User Setup Checklist
feature: Getting Started
exl-id: c7b068fc-a038-4f9c-a037-72440a1a864e
---
# User Setup Checklist {#user-setup-checklist}

Now that you've completed all of the [initial setup steps](/help/marketo/getting-started/initial-setup/setup-steps.md){target="_blank"}, it's time to establish some foundational elements to ensure smooth ongoing usage. This will lay the groundwork for your journey with Marketo Engage and help you make the most of its features. Let's get started!

>[!NOTE]
>
>You can also download this checklist, [along with a list of best practices](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx) for your new instance, and check off the steps as you go.

## Marketo Engage on Adobe Identity Management {#marketo-engage-on-adobe-identity-management}

Your new Marketo Engage subscriptions are onboarded to [Adobe Identity Management System (IMS)](https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html). Proceed to the following user management review in Adobe Admin Console.

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Subscription & Marketo Engage Product Admin</td>
    <td><li>Confirm you've been granted an Adobe Product Admin role by your Adobe Org System Admin.</li>
    <ul>
    <li>Contact the Adobe Account team (your Account Manager) or send an email to <code>marketocares@marketo.com</code> to find out who at your organization has <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe Admin Console System Admin</a> privileges.</li></ul>
    <li>Accept the 'Marketo Engage Product Admin' invite to activate your Adobe ID. The <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup.html?lang=en#create-a-product-profile">welcome email</a> is sent when the role is assigned in the Adobe Admin Console.</li></td>
  </tr>
  <tr>
    <td>Product Profiles</td>
    <td><li>Assign all desired users to the Marketo Engage <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/admin-setup#create-a-product-profile">Product Profile</a> in Adobe Admin Console.</li>
    <ul>
    <li>You cannot assign users' roles in Marketo Engage > Admin > Users & Roles before adding them to a Product Profile.</li>
    <li>Each subscription will be a standalone Product Profile. If an undesired user is added to multiple Product Profiles (e.g., production and testing sandbox), you must delete the user from all Product Profiles. Otherwise, they will still have access to Marketo Engage.</li></ul></td>
  </tr>
  <tr>
    <td>Users</td>
    <td><li>Create a policy on when to <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user.html">create a user</a>.</li> <li>Create a policy on when to remove users.</li>
    <p><img src="assets/note-icon.png" alt="note icon"> NOTE: You must be a System Admin to remove users.
    <li>Determine who should have <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe System Admin and Marketo Engage Product Admin permissions.</a> <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/add-or-remove-a-user">Add users</a> to the desired Product Profile.</li>
    <li>Create one API user for each API use case.</li></td>
  </tr>
  <tr>
    <td>User Management API (if applicable)</td>
    <td><li>Use the <a href="https://www.adobe.io/apis/experienceplatform/umapi-new.html">Adobe User Management API</a> to invite, update, and delete users.</li>
    <li>Use the <a href="https://developer.adobe.com/umapi/">Adobe User Management API</a> to add or remove roles (e.g., Administrators, Support Admins, Developers).</li>
    </td>
  </tr>
  <tr>
    <td>Product Support Administrator</td>
    <td><li>To <a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html#create-a-support-ticket-with-admin-console">submit a support ticket in the Adobe Admin Console</a>, you need to have the 'Product Support Administrator' role assigned by a System Administrator to the subscriptions you manage. Only a System Administrator in your organization can <a href="https://experienceleague.adobe.com/docs/customer-one/using/home.html#assign-the-support-admin-role">assign you to this role</a>.</li>
    <li>You might have received an email from the System Administrator stating that you are the Support Administrator for your Marketo Engage subscription. If so, click <a href="https://experienceleague.adobe.com/en/docs/customer-one/using/home#assign-the-support-admin-role">'Get Started'</a> in the email to join the organization.</li>
    <li>Determine the appropriate contacts (with at least one backup contact) and have the System Administrator assign the Product Support Admin role accordingly.</li></td>
  </tr>
</tbody>
</table>

## Dynamic Chat on Adobe Identity Management Setup {#dynamic-chat-on-adobe-identity-management}

To use [Dynamic Chat](https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/dynamic-chat-overview.html), the native conversation automation channel in Marketo Engage, proceed with the user permission setup following the steps below in the [Adobe Admin Console](https://adminconsole.adobe.com/){target="_blank"}.

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Subscription & Dynamic Chat Product Admin (if applicable)</td>
    <td><li>Confirm you've been granted an Adobe Product Admin role by your Adobe Org System Admin.</li>
    <ul><li>Contact the Adobe Account team (your Account Manager) or send an email to <code>marketocares@marketo.com</code> to find out who at your organization has <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/administration/marketo-with-adobe-identity/adobe-identity-management-overview.html">Adobe Admin Console System Admin</a> privileges.</li></ul>
    <li>Accept the <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">'Dynamic Chat Product Admin'</a> invite. The <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup.html">welcome email</a> is sent when Dynamic Chat is enabled in your Marketo Engage instance and you are designated as a System Admin.</li></td>
  </tr>
  <tr>
    <td>Product Profiles</td>
    <td><li>Assign all desired users to Dynamic Chat's Product Profile in Adobe Admin Console.</li>
    <ul>
    <li>If an undesired user is added to multiple Product Profiles, you must delete the user from all product profiles. Otherwise, they will still have access to Dynamic Chat.</li>
    <li>You can <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#edit-existing-permissions">edit Product Profiles in Dynamic Chat</a> and create a custom profile with a custom set of <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/permissions#list-of-permissions">permissions available within your subscription</a>.</li></td>
  </tr>
  <tr>
    <td>Users</td>
    <td><li>Create a policy on when to add and remove a chat user.</li>
    <li>Create a policy on who should have <a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/initial-setup#access-admin-console">Adobe Dynamic Chat Product Admin permissions.</a></li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/dynamic-chat/setup-and-configuration/add-or-remove-chat-users#add-a-chat-user">Add users to the desired Product Profile</a>.</li></td>
  </tr>
</tbody>
</table>

## Set up Ongoing System Updates and Communications {#system-updates}

<table>
<thead>
  <tr>
    <th style="width:20%">Area</th>
    <th style="width:80%">Action Items</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Adobe Marketo Status Updates</td>
    <td><li><a href="https://status.adobe.com/cloud/experience_cloud">Subscribe to Adobe Marketo Engage Status updates</a>.</li></td>
  </tr>
  <tr>
    <td>Notifications</td>
    <td><li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications#subscribe-to-notifications">Subscribe to admin notifications</a> for critical issues such as errors in your Smart Campaigns, and critical issues found with the CRM sync.</li></td>
  </tr>
</tbody>
</table>

<p>

Now that your Marketo Engage account is ready to go, please review our [Best Practices for a New Marketo Engage Instance](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/where-to-start.md){target="_blank"} section to get the most out of your investment and set yourself up for long term success.
