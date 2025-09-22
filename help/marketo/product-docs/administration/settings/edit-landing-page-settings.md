---
unique-page-id: 2359918
description: "Edit Landing Page Settings - Marketo Docs - Product Documentation"
title: Edit Landing Page Settings
exl-id: 019b4651-3a66-46f9-8722-66af30194380
feature: Administration, Landing Pages
---
# Edit Landing Page Settings {#edit-landing-page-settings}

You can edit your domain name and fallback page, enable or disable form prefill, prevent misuse of your landing page, and more. Here's how.

>[!NOTE]
>
>**Admin Permissions Required**

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/edit-landing-page-settings-1.png)

1. Click **[!UICONTROL Landing Pages]**.

   ![](assets/edit-landing-page-settings-2.png)

1. In the **[!UICONTROL Landing Pages]** section, click **[!UICONTROL Edit]**.

   ![](assets/edit-landing-page-settings-3.png)

1. Enter your domain and page information.

   ![](assets/edit-landing-page-settings-4.png)

   | Term |Definition |
   |---|---|
   | [!UICONTROL Domain name for landing pages] |This is your CNAME. A CNAME is the first part of the URL you give people for landing pages. For example, in `https://go.yourCompany.com`, the word "go" is the CNAME. You can have multiple, but most people just use the one. |
   | [!UICONTROL Fallback page] |This is where to go if the landing page doesn't exist or is down. Learn more about [fallback pages](/help/marketo/product-docs/administration/settings/set-a-fallback-page.md). |
   | [!UICONTROL Homepage] |Enter your corporate site URL. |

1. Check the **[!UICONTROL Form Prefill]** checkbox to allow forms to prefill information for known (cookied) people. Uncheck to block.

   ![](assets/edit-landing-page-settings-5.png)

   >[!NOTE]
   >
   >If you want the prefill `<script>` tag to appear at the end of the `<head>` tag in the code, check the **[!UICONTROL Inject Prefill Script at End of Head]** box. Leave unchecked if you want it to appear at the beginning.
   >
   >Check **[!UICONTROL Remove default favicon links]** to prevent Marketo from inserting any favicon links into the code.

1. After making your selections, click **[!UICONTROL Save]**.

   ![](assets/edit-landing-page-settings-6.png)

   Great job! Your landing pages now have the right information and should start working right away.
