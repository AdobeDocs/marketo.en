---
description: Adobe IMS User Migration Troubleshooting Guide - Marketo Docs - Product Documentation
title: Adobe IMS User Migration Troubleshooting Guide
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
---
# Adobe IMS User Migration Troubleshooting Guide {#adobe-ims-user-migration-troubleshooting-guide}

During the IMS user migration process, an Adobe user is created for each Marketo Engage user being migrated (unless it already exists with the same email address). Sometimes, it doesn't get created, which can be attributed to the user's record in the Active Directory or issues with the email address. 

This article, for users who perform self migrations, lists each error message you may see in the status field of the self-migration console.

>[!NOTE]
>
>The directory/domain-related errors can be triggered by another org/Admin Console where a directory trust is set up, or the domain has been claimed.  

## Error Messages {#error-messages}

First, determine if the user needs to be migrated or not, as that will affect which resolution steps to follow.

Use the "On This Page" section on the right to jump straight to a specific error.

### Gmail Invalid Character {#gmail-invalid-character}

**Root cause**: Per the Adobe security policy, the characters `.` and `+` are not allowed in a Gmail email address. Both characters are allowed in non-Gmail email addresses.

**Resolutions**:

_If the user needs to be migrated_ - The email address must be updated in Marketo Engage to comply with the Adobe security policy and reverified. Marketo admin to then rerun the user migration for this user from the Migration Console.

_If the user does **not** need to be migrated_ - Marketo Engage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

### User Not in Directory {#user-not-in-directory}

**Root cause**: The user does not exist in Active Directory (AD). For any orgs with SSO that have the AD sync enabled, user creation is allowed only through Identity Provider (IdP). As such, the user couldn't be added through Admin Console during user migration.

**Resolutions**:

_If the user needs to be migrated_ - The user must be added to the Active Directory with proper permissions by a system administrator. Marketo Engage admin to then rerun the user migration for this user from the Migration Console.

_If the user does **not** need to be migrated_ - Marketo Engage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

### Inactive User {#inactive-user}

**Root cause**: AD Sync is enabled, and the user's federated account exists but in inactive/disabled status.

**Resolutions**:

_If the user needs to be migrated_ - The user's status and proper permissions must be restored by a system administrator. Marketo Engage admin to then rerun the user migration for this user from the Migration Console.

_If the user does **not** need to be migrated_ - Marketo Engage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

### Invalid Domain {#invalid-domain}

**Root cause**: Domain enforcement is enabled in the Admin Console. However, the domain of the email address for the user is not one of the allowed domains, or the domain has been claimed in another org/Admin Console.

**Resolutions**:

_If the user needs to be migrated_ (and the domain enforcement is enabled in the migrating org) - The email address must be updated in Marketo Engage to comply with the Domain Enforcement (DE) policy. Alternatively, the System Admin can either [move the domain](https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories){target="_blank"} to another Domain Enforcement (DE) disabled directory, or [create a new directory](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"} that isn't under DE policy. Marketo Engage admin to then rerun the user migration for this user from the Migration Console.

_If the user needs to be migrated_ (and the domain enforcement is enabled in another org) - a system administrator of the org where the domain has been claimed needs to add the user's email address to the exception list. Marketo Engage admin to then rerun the user migration for this user from the Migration Console. 

_If the user does **not** need to be migrated_ - Marketo Engage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

### Type2E Failure {#type2e-failure}

**Root cause**: Creation of a federated user account (for Single Sign-On) failed during user migration because an Adobe ID already exists for the same email address as an individual user.

**Resolutions**:

1. Remove the individual user from the Adobe org. Please note: the user will lose access to all products and will need to be re-entitled again later.
1. Re-run the user migration so a federated user account gets created for this user. 
1. Add the user back to the products they previously had access to.

### User Creation Failed {#user-creation-failed}

[See below](#failed)

### Marketo Entitlement Failed {#marketo-entitlement-failed}

[See below](#failed)

### Pendo Migration Failed {#pendo-migration-failed}

[See below](#failed)

### User Data Migration Failed {#user-data-migration-failed} 

[See below](#failed)

### Product Data Sync Failed {#product-data-sync-failed}

[See below](#failed)

### Adobe Entitlement Failed {#adobe-entitlement-failed}

[See below](#failed)

### User Sign Out Failed {#user-sign-out-failed}

[See below](#failed)

### Adobe ID Creation Failed {#adobe-id-creation-failed}

[See below](#failed)

### Failed {#failed}

**Root cause**: These errors can be caused by various reasons in the backend.

**Resolutions**:

Submit a support case with relevant details for [Marketo Support](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.
