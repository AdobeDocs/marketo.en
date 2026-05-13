---
unique-page-id: 11386358
description: Learn about the Marketo Engage sandbox for testing before production. Use a sandbox instance to test without affecting production.
title: Marketo Sandbox
exl-id: c040fac6-2290-4de5-b27d-2c7cb28f6e30
TQID: https://experienceleague.adobe.com/Cb1H0PKG-G0c4FkIcjI-erNzR0dwRtj7TwfqtwhFFMI
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: e2290edd-b061-4880-9d79-dee306cf5aa9
    internal-label: Implementation
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
topic_v2:
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
    internal-label: Implementation
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
  - id: f4e6943a-c91a-4134-a2c7-f4f20cfff2f0
    internal-label: Privacy
---
# Marketo Sandbox {#marketo-sandbox}

A Marketo Engage sandbox is an additional instance used for testing purposes before implementation in the production environment.

>[!AVAILABILITY]
>
>Not everyone has purchased this feature. Contact the Adobe Account Team (your Account Manager) for details.

A Marketo sandbox cannot be synced to your regular CRM if it is already synced to your production instance. Use your CRM's sandbox for the sync, and follow all the same steps as the original sync.

## Things to Know About Sandboxes {#things-to-know-about-sandboxes}

* If you wish to add users, the process is the same as [adding users in production](/help/marketo/product-docs/administration/users-and-roles/add-or-remove-a-user.md#add-a-user). Again, they must use a different email address if they already have a Marketo login.
* Your Marketo sandbox will start out empty, but have the same features available as your production instance.
* If you create a program in your sandbox and want to move it to production, you can perform a [program import](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/import-a-program.md).
* Sandboxes are throttled so production instances are not adversely affected by testing environments. You can send up to 20 emails per campaign run.

>[!CAUTION]
>
>Sandbox refresh for the Marketo Dynamics _or_ Salesforce Sync is not supported at this time. If you need to refresh your CRM sandbox, a new Marketo sandbox is required. Contact the Adobe Account Team (your Account Manager) for details.

## Instance Copy {#instance-copy}

You can submit a Support case requesting a one-time instance copy to fill your sandbox. The instance copy will not bring over _everything_, however. Contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support) for details.

>[!NOTE]
>
>If you are changing your native CRM, a new Marketo instance would be needed, and an instance copy to the new Marketo instance would not be possible. Instead, work with Marketo Support to explore the Import Program functionality.
