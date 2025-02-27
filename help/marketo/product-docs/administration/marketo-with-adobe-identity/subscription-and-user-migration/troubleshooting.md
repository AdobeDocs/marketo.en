---
description: Adobe IMS Troubleshooting Guide - Marketo Docs - Product Documentation
title: Adobe IMS Troubleshooting Guide
hide: yes
hidefromtoc: yes
feature: Marketo with Adobe Identity
exl-id: 921d9d45-c5c2-405c-bd3b-be8aa6d11e2f
---
# Adobe IMS Troubleshooting Guide {#adobe-ims-troubleshooting-guide}

During the IMS user migration process, an Adobe user is created for each Marketo Engage user being migrated. Sometimes, it doesn't get created (for various reasons, related to the user's record in the Active Directory or issues with the email address). When this happens, the Marketo Engage admin will see the reason in the user's migration status field on the self-migration console. 

## Error Messages {#error-messages}

Use the "On This Page" section on the right to jump straight to a specific error and learn how to resolve it.

### Not in Directory {#not-in-directory}

_Root cause_: The user does not exist in Active Directory (AD). For any orgs with SSO that have the AD sync enabled, user creation is allowed only through Identity Provider (IdP). As such, the user couldn't be added through Admin Console during user migration.

_Resolutions_:

Pre-migration - Marketo Enage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

Post-migration - The user must be added to the Active Directory with proper permissions. Marketo Engage admin to then re-run the user migration for this user from the Migration Console.

### Gmail Invalid Character {#gmail-invalid-character}

_Root cause_: Per Adobe security policy, the characters `.` and `+` are not allowed in a Gmail email address. Both characters are allowed in non-Gmail email addresses only.

_Resolutions_:

Pre-migration - Marketo Enage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

Post-migration - The email address must be updated in Marketo Engage to comply with the Adobe's security policy. Marketo admin to re-run the user migration for this user from the Migration Console.

### Inactive User {#inactive-user}

_Root cause_: AD Sync is enabled, and the user's federated account exists but in inactive/disabled status.

_Resolutions_:

Pre-migration - Marketo Enage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

Post-migration - The user's status and proper permissions must be restored. Marketo Engage admin to then re-run the user migration for this user from the Migration Console.

### Not in Domain {#not-in-domain}

_Root cause_: Domain enforcement is enabled in the Admin Console, but the domain of the email address for the user is not one of the allowed domains.

_Resolutions_:

Pre-migration - Marketo Enage admin to skip the user in the Migration Console. The "Migration Complete" button appears when all users are accounted for by migrating or skipping. Click the button to conclude the user migration process.

Post-migration - The email address must be updated in Marketo Engage to comply with the Domain Enforcement (DE) policy. Alternatively, the System Admin can either [move the domain](https://helpx.adobe.com/enterprise/using/manage-domains-directories.html#move-domains-across-directories){target="_blank"} to another Domain Enforcement (DE) disabled directory, or [create a new directory](https://helpx.adobe.com/enterprise/using/set-up-identity.html){target="_blank"} that isn't under DE policy. Marketo Engage admin to then re-run the user migration for this user from the Migration Console.

### Create Failure {#create-failure}

_Root cause_: This error can be caused by various reasons in the backend.

_Resolutions_:

Pre-migration - Please submit a support case for those [not yet migrated](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

Post-migration - Please submit a support case for those [already migrated](https://experienceleague.adobe.com/home?support-tab=home#support){target="_blank"}.

### Type2e User Failure {#type2e-user-failure}

_Root cause_: This error can be caused by various reasons in the backend.

_Resolutions_:

Pre-migration - Please submit a support case for those [not yet migrated](https://nation.marketo.com/t5/support/ct-p/Support){target="_blank"}.

Post-migration - Please submit a support case for those [already migrated](https://experienceleague.adobe.com/home?support-tab=home#support){target="_blank"}.
