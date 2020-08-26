---
unique-page-id: 5472348
description: Make an Existing Free-form Landing Page Template Mobile Compatible - Marketo Docs - Product Documentation
title: Make an Existing Free-form Landing Page Template Mobile Compatible
---

# Make an Existing Free-form Landing Page Template Mobile Compatible {#make-an-existing-free-form-landing-page-template-mobile-compatible}

>[!NOTE]
>
>Landing pages templates that were created before the [January 2015 release](../../../../release-notes/2015/release-notes-january-2015.md)need to be upgraded to be mobile compatible.

This can be done in two places, the Template Editor and the Landing Page Editor.  

## Upgrade from the Template Editor {#upgrade-from-the-template-editor}

1. Go to the **Design Studio**.

   ![](assets/designstudio-1.png)

1. Select **Templates**.

   ![](assets/image2015-1-22-20-3a20-3a2.png)

1. Select a template where **Mobile Compatible** is **No**.

   ![](assets/image2015-1-22-20-3a22-3a24.png)

1. Click **Edit Draft**.

   ![](assets/image2015-1-22-20-3a25-3a36.png)

1. Click **Make Mobile Compatible**.

   ![](assets/image2015-1-22-20-3a30-3a33.png)

1. Click **Upgrade**.

   ![](assets/image2015-1-22-20-3a32-3a45.png)

   Your landing page template is now mobile compatible!

   >[!NOTE]
   >
   >Upgrading should be harmless, but make sure to check pages for any discrepancies. Upgrading will create drafts of any landing pages using that template.

   ![](assets/image2015-1-22-20-3a36-3a43.png)

   ## What Makes a Template Mobile Compatible? {#what-makes-a-template-mobile-compatible}

   Great questions! Your template must have have the following tags:

   `<pre data-theme="Confluence">Must have <!DOCTYPE HTML> Must have a <HEAD> element Must have a <TITLE> in the <HEAD> element Must have <META CHARSET="UTF-8"> within the <HEAD> element Must have a <BODY> element that contains one (and only one) <DIV class="mktoContent"></DIV></pre>`  If everything looks good, you'll see this message.

   ![](assets/image2015-1-22-20-3a41-3a31.png)

   If something is wrong, an error message will display, click repair to fix the issue and repeat the validation process.

   ![](assets/image2015-1-22-20-3a43-3a20.png)

If you make any changes to the template, Click Template Actions and select Validate Mobile Compatibility. 

## Upgrading a Template from the Free-form Landing Page Editor {#upgrading-a-template-from-the-free-form-landing-page-editor}

When you're editing a landing page and you click on the mobile tab, you'll sometimes notice the template has not been upgraded. Fear not! You can upgrade it right there.

1. Click the **Mobile** tab.

   ![](assets/image2015-1-22-20-3a48-3a19.png)

1. Click the check box and click **Activate**.

   ![](assets/image2015-1-22-20-3a49-3a34.png)

   >[!NOTE]
   >
   >Activating the mobile version of a template will create drafts of any landing pages that use it.

Awesome! You can now [customize the mobile view](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/customize-mobile-view-for-your-free-form-landing-page.md) of all your landing pages that use this template.

>[!NOTE]
>
>**Related Articles**
>
>* [Customize Mobile View for Your Free-Form Landing Page](../../../../product-docs/demand-generation/landing-pages/free-form-landing-pages/customize-mobile-view-for-your-free-form-landing-page.md)
>

