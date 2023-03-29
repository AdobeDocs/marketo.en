---
unique-page-id: 11386358
description: Marketo Sandbox - Marketo Docs - Product Documentation
title: Marketo Sandbox
exl-id: c040fac6-2290-4de5-b27d-2c7cb28f6e30
---
# Marketo Sandbox {#marketo-sandbox}

A Marketo sandbox is an additional instance used for testing purposes before implementation in the production environment.

>[!AVAILABILITY]
>
>Not everyone has purchased this feature. Please contact the Adobe Account Team (your Account Manager) for details.

A Marketo sandbox cannot be synced to your regular CRM if it's already synced to your production instance. Use your CRM's sandbox for the sync, and follow all the same steps as the original sync.  

## Things to Know About Sandboxes {#things-to-know-about-sandboxes}

* Once the Adobe Account Team has your sandbox set up and sends you the invite, you must use a different email address to log-in than your Marketo production instance.
* If you wish to add users, the process is the same as [adding users in production](/help/marketo/product-docs/administration/users-and-roles/managing-marketo-users.md#create-users). Again, they must use a different email address if they already have a Marketo login.
* Your Marketo sandbox will start out empty, but have the same features available as your production instance.
* If you create a program in your sandbox and want to move it to production, you can perform a [program import](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.md).
* Sandboxes are throttled so production instances aren't adversely affected by testing environments. You can send up to 20 emails per campaign run.  

>[!CAUTION]
>
>We do not currently support sandbox refresh for Marketo Dynamics Sync. If you need to refresh your Dynamics CRM sandbox, a new Marketo sandbox will be required. Please contact your the Adobe Account Team (your Account Manager) for additional details.

## Instance Copy {#instance-copy}

You can submit a Support case requesting a one-time instance copy to fill your sandbox. The instance copy will not bring over _everything_, however. Please consult [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support) for details.

>[!NOTE]
>
>If you're changing your native CRM, a new Marketo instance would be needed, and an instance copy to the new Marketo instance would not be possible. Instead, please work with Marketo Support to explore the Import Program functionality.
