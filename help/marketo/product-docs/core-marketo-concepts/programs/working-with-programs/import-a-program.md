---
unique-page-id: 1147108
description: Learn how to import a program into Marketo. Bring in a program from the library or from another instance.
title: Import a Program
exl-id: 15e23e38-a24b-45b3-89a9-ffec85649f4a
feature: Programs
TQID: https://experienceleague.adobe.com/uQNr3WjiGA4EIjRwxQ4nZqXG6CxuMRQj2Hz5aGX6hb8
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
    internal-label: Design Studio
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
  - id: f82558ea-6af5-44eb-a424-5b3389abb0a3
    internal-label: Templates
subfeature_v2:
  - id: a1d50dda-6d94-4e16-8c30-5eb7181c4650
    internal-label: Segmentation
  - id: cdd4e0f6-e87e-453f-88ee-2ee54a7de272
    internal-label: Dynamic content
  - id: df8eb12b-4f82-491f-acbb-d74012ca5654
    internal-label: Snippets
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Import a Program {#import-a-program}

A program can be imported from one Marketo Engage subscription to another. For instance, you can create a program in a sandbox and then import it into your live subscription. Also, you can import a pre-built program from the [Marketo Program Library](/help/marketo/product-docs/core-marketo-concepts/programs/program-library/program-import-library-overview.md){target="_blank"}.

>[!CAUTION]
>
>
>* When importing a program, emails/Landing Pages that contain snippets or [dynamic content](/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md){target="_blank"} will be skipped.
>
>* Programs that have Smart Lists containing a "Custom Object is Updated" trigger will cause the import to fail. Please remove this trigger from all Smart Lists prior to following the steps outlined below.

## Importing a Program {#importing-a-program}

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/import-a-program-1.png)

1. Click the **[!UICONTROL New]** drop-down and select **[!UICONTROL Import Program]**.

   ![](assets/import-a-program-2.png)

   >[!NOTE]
   >
   >* Program Import is only available for users that have roles with Import Program permission enabled. Learn more about [managing user roles and permissions](/help/marketo/product-docs/administration/users-and-roles/managing-user-roles-and-permissions.md){target="_blank"}.
   >
   >* To connect a sandbox account to your live subscription, contact [Marketo Support](https://nation.marketo.com/t5/Support/ct-p/Support){target="_blank"}.

1. Select a Marketo **[!UICONTROL Subscription]** and a program to import. Click **[!UICONTROL Next]**.

   ![](assets/import-a-program-3.png)

1. Specify a **[!UICONTROL Campaign Folder]** for the imported program. Click **[!UICONTROL Next]**.

   ![](assets/import-a-program-4.png)

   >[!NOTE]
   >
   >Make sure **[!UICONTROL Use default conflict]** rules is selected. Conflict rules are needed when you import programs into an instance that have assets of the same name.

1. Choose your desired Conflict Details and click **[!UICONTROL Next]**.

   ![](assets/import-a-program-5.png)

   >[!NOTE]
   >
   >Importing a program that uses Custom Flow Steps, or Smart List rules that are derived from a Flow Step Service into a destination instance where there is more than one compatible service provider, the importing user will be prompted to assign steps or rules to the correct service provider in the destination instance.

1. Preview details and **[!UICONTROL Import]** the program.

   ![](assets/import-a-program-6.png)

An email confirmation is sent once the import has finished.

   >[!NOTE]
   >
   >You'll need to reschedule imported batch campaigns and activate trigger campaigns. The system automatically deactivates campaign schedules and trigger campaigns in the imported program.

## Impact on External Assets During Program Imports {#impact-on-external-assets-during-program-imports}

Programs use external assets like email templates, Landing Page templates, images, forms, tokens, and program tags. You have the ability to configure how Landing Page templates and program tags are handled, and Marketo automatically manages the rest.

**Email/Landing Page Templates:** Email/Landing Page templates are imported into the Design Studio. You can use conflict rules to configure behavior when a template with the same name exists. Using the default rule, a number will be appended to a template if one with the same name exists. For example, if you already have a template named "Standard Template," the new one will be named "Standard Template - 1."

**Landing Pages/Forms:** If a form or Landing Page with the same name exists in Design Studio, they will still be imported, but with a number appended to their name (ex: Landing Page - 1).

**Images:** Images used by Landing Pages are imported into the design studio unless one with the same name exists.

**Tokens:** Tokens that live outside of a program will be converted to local tokens during the import process.

>[!CAUTION]
>
>Image type my tokens are not supported for program imports. If a program that has image type my tokens is imported, _no_ tokens will come through.

**Program Tags:** You can use conflict rules to control how program tags that do not exist in the destination account will be treated. Using the default rule will create the program tags, or you can choose to ignore the tags.
