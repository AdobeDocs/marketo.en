---
unique-page-id: 1147108
description: Import a Program - Marketo Docs - Product Documentation
title: Import a Program
exl-id: 15e23e38-a24b-45b3-89a9-ffec85649f4a
---
# Import a Program {#import-a-program}

A program can be imported from one Marketo subscription to another. For instance, you can create a program in a sandbox and then import it into your live subscription. Also, you can import a pre-built program from the Marketo Program Library.

## Importing a Program {#importing-a-program}

1. Go to **Marketing Activities.**

   ![](assets/import-a-program-1.png)

1. Click **New** drop down. Select **Import Program**.

   ![](assets/import-a-program-2.png)

   >[!NOTE]
   >
   >Program Import is only available for users that have roles with Import Program permission enabled. Learn more about [managing user roles and permissions](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md).
   >
   >To connect a sandbox account to your live subscription, contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support).

1. Select a Marketo **Subscription** and a program to import. Click **Next**.

   ![](assets/import-a-program-3.png)

1. Specify a **Campaign Folder** for the imported program. Click **Next.**

   ![](assets/import-a-program-4.png)

   >[!NOTE]
   >
   >Make sure **Use default conflict** rules is selected. Conflict rules are needed when you import programs into an instance that have assets of the same name.

1. Choose your desired Conflict Details and click **Next**.

   ![](assets/import-a-program-5.png)

   >[!NOTE]
   >
   >Importing a program that uses Custom Flow Steps, or Smart List rules that are derived from a Flow Step Service into a destination instance where there is more than one compatible service provider, the importing user will be prompted to assign steps or rules to the correct service provider in the destination instance.

1. Preview details and **Import** the program.

   ![](assets/import-a-program-6.png)

You'll receive an email confirmation once the import has finished.

   >[!NOTE]
   >
   >You'll need to reschedule imported batch campaigns and activate trigger campaigns. The system automatically deactivates campaign schedules and trigger campaigns in the imported program.

## Impact on External Assets During Program Imports {#impact-on-external-assets-during-program-imports}

Programs use external assets like email templates, landing page templates, images, forms, tokens, and program tags. You have the ability to configure how landing page templates and program tags are handled, and Marketo automatically manages the rest.

**Email/Landing Page Templates:** Email/Landing Page templates are imported into the Design Studio. You can use conflict rules to configure behavior when a template with the same name exists. Using the default rule, a number will be appended to a template if one with the same name exists. For example, if you already have a template named "Standard Template," the new one will be named "Standard Template - 1."

**Landing Pages/Forms:** If a form or landing page with the same name exists in Design Studio, they will still be imported, but with a number appended to their name (ex: Landing Page - 1).

**Images:** Images used by landing pages are imported into the design studio unless one with the same name exists.

**Tokens:** Tokens that live outside of a program will be converted to local tokens during the import process.

>[!CAUTION]
>
>Image type my tokens are not supported for program imports. If a program that has image type my tokens is imported, **no** tokens will come through.

**Program Tags:** You can use conflict rules to control how program tags that do not exist in the destination account will be treated. Using the default rule will create the program tags, or you can choose to ignore the tags.

>[!CAUTION]
>
>When importing a program, emails/landing pages that contain [dynamic content](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md) will be skipped.
