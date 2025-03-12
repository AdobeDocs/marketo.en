---
description: Adobe IMS User Migration Troubleshooting Guide - Marketo Docs - Product Documentation
title: Adobe IMS User Migration Troubleshooting Guide
hide: yes
hidefromtoc: yes
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
---
# Adobe IMS User Migration Troubleshooting Guide {#adobe-ims-user-migration-troubleshooting-guide}

During the IMS user migration process, an Adobe user is created for each Marketo Engage user being migrated (unless it already exists with the same email address). Sometimes, it doesn't get created, which can be attributed to the user's record in the Active Directory or issues with the email address. When this happens, the Marketo Engage admin will see the reason in the user's migration status field in the self-migration console. 

## Error Messages {#error-messages}

First, determine if the user needs to be migrated or not, as that will affect which resolution steps to follow.

Use the "On This Page" section on the right to jump straight to a specific error.

### Not in Directory {#not-in-directory}

**Root cause**: The user does not exist in Active Directory (AD). For any orgs with SSO that have the AD sync enabled, user creation is allowed only through Identity Provider (IdP). As such, the user couldn't be added through Admin Console during user migration.

**Resolutions**:

_If the user does not need to be migrated_ - Marketo Engage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

_If the user does need to be migrated_ - The user must be added to the Active Directory with proper permissions by a system administrator. Marketo Engage admin to then rerun the user migration for this user from the Migration Console.

### Gmail Invalid Character {#gmail-invalid-character}

**Root cause**: Per the Adobe security policy, the characters `.` and `+` are not allowed in a Gmail email address. Both characters are allowed in non-Gmail email addresses.

**Resolutions**:

_If the user does not need to be migrated_ - Marketo Engage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

_If the user does need to be migrated_ - The email address must be updated in Marketo Engage to comply with the Adobe's security policy and reverified. Marketo admin to then rerun the user migration for this user from the Migration Console.

### Inactive User {#inactive-user}

**Root cause**: AD Sync is enabled, and the user's federated account exists but in inactive/disabled status.

**Resolutions**:

_If the user does not need to be migrated_ - Marketo Engage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

_If the user does need to be migrated_ - The user's status and proper permissions must be restored. Marketo Engage admin to then rerun the user migration for this user from the Migration Console.

### Not in Domain {#not-in-domain}

**Root cause**: Domain enforcement is enabled in the Admin Console, but the domain of the email address for the user is not one of the allowed domains.

**Resolutions**:

_If the user does not need to be migrated_ - Marketo Engage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

_If the user does need to be migrated_ - The email address must be updated in Marketo Engage to comply with the Domain Enforcement (DE) policy. Alternatively, the System Admin can either [move the domain](https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories){target="_blank"} to another Domain Enforcement (DE) disabled directory, or [create a new directory](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"} that isn't under DE policy. Marketo Engage admin to then rerun the user migration for this user from the Migration Console.

### Create Failure {#create-failure}

**Root cause**: This error can be caused by various reasons in the backend.

**Resolutions**:

Submit a support case with relevant details for [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

### Type2e User Failure {#type2e-user-failure}

**Root cause**: This error can be caused by various reasons in the backend.

**Resolutions**:

Submit a support case with relevant details for [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.
