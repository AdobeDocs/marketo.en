---
description: Adobe IMS Troubleshooting Guide - Marketo Docs - Product Documentation
title: Adobe IMS Troubleshooting Guide
hide: yes
hidefromtoc: yes
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
---
# Adobe IMS Troubleshooting Guide {#adobe-ims-troubleshooting-guide}

During the IMS user migration process, an Adobe user is created for each Marketo Engage user being migrated. Sometimes, it doesn't get created (for various reasons, related to the user's record in the Active Directory or issues with the email address). When this happens, the Marketo Engage admin will see the reasons in the user's migration status field on the self-migration console. See how to resolve various Adobe User Creation issues below.

## Error Messages {#error-messages}

* <a href="#not-in-directory">Not in Directory</a>
* <a href="#gmail-invalid-character">Gmail Invalid Character</a>
* <a href="#inactive-user">Inactive User</a>
* <a href="#not-in-domain">Not in Domain</a>
* <a href="#create-failure">Create Failure</a>
* <a href="#type2e-user-failure">Type2e User Failure</a>



<table>
<thead>
  <tr>
    <th style="width:20%">Error Message</th>
    <th style="width:40%">Root Cause</th>
    <th style="width:40%">Resolutions</th>
  </tr>
  </thead>
<tbody>
  <tr>
    <td><i><a id="not-in-directory">Not in Directory</a></i></td>
    <td>The user does not exist in Active Directory (AD). For any orgs with SSO that have AD sync enabled, user creation is allowed only through Identity Provider (IdP). Therefore, the user couldn't be added through Admin Console during the user migration.</td>
    <td>Migrate - the user needs to be added to the Active Directory with proper permissions. Marketo admin to re-run the user migration for this user from the Migration Console. 
    <br>Not migrate - Marketo admin to skip the user in the Migration Console. "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click it to conclude the user migration process.</td>
  </tr>
  <tr>
    <td><i><a id="gmail-invalid-character">Gmail Invalid Character</a></i></td>
    <td>Per Adobe's security policy, '.' and '+' sign are not allowed in an email address of Gmail domain only  
    <br>Both special characters are allowed in a non-Gmail domain email address. </td>
    <td>Migrate - The email address needs to be updated in Marketo Engage to comply with the Adobe's security policy. Marketo admin to re-run the user migration for this user from Migration Console.<br>Not migrate - Marketo admin to skip the user in the Migration Console. "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click it to conclude the user migration process.</td>
  </tr>
  <tr>
    <td><i><a id="inactive-user">Inactive User</a></i></td>
    <td>AD Sync is enabled, and the user's federated account exists but in inactive/disabled status.</td>
    <td>Migrate - The user's status and proper permissions need to be restored. Marketo admin to re-run the user migration for this user from the Migration Console.
    <br>Not migrate - Marketo admin to skip the user in the Migration Console. "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click it to conclude the user migration process.</td>
  </tr>
  <tr>
    <td><i><a id="not-in-domain">Not in Domain</a></i></td>
    <td>Domain enforcement is enabled in Admin Console, but the domain of the email address for the user is not one of the allowed domains. 
    <br>Domain enforcement policies are set at the directory level.</td>
    <td>Migrate - The email address needs to be updated in Marketo Engage to comply with the domain enforcement policy, or the system admin can either <a href="https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories"> 
    move the domain to another Domain Enforcement (DE) disabled directory </a>or <a href="https://helpx.adobe.com/enterprise/using/set-up-identity.html">create a new directory</a>, that isn't under DE policy. Marketo admin to re-run the user migration for this user from Migration Console. <br>Not migrate - Marketo admin to skip the user in the Migration Console. "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click it to conclude the user migration process.</td>
  </tr>
  <tr>
    <td><i><a id="create-failure">Create Failure</a></i></td>
    <td>Various reasons in the backend.</td>
    <td>Please submit a support case.</td>
  </tr>
  <tr>
    <td><i><a id="type2e-user-failure">Type2e User Failure</a></i></td>
    <td>Various reasons in the backend.</td>
    <td>Please submit a support case.</td>
  </tr>
</tbody>
</table>
