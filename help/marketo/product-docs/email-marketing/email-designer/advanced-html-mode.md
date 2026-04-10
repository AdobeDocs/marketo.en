---
solution: Marketo Engage
product: marketo
title: Add custom CSS to your email content
description: Learn how to add custom CSS to email content in the Email Designer. Style your emails with custom code in Marketo Engage.
level: Intermediate
feature: Email Designer
hide: yes
hidefromtoc: yes
exl-id: b030e56a-de70-4b0d-9788-04a01235cffb
---
# Edit email templates with the advanced HTML editor {#advanced-html-mode}

Advanced HTML mode lets you view and edit the raw source code of email templates directly from the [!DNL Marketo Engage] Email Designer interface.

This capability lets you insert advanced expressions directly in the source. When you switch back to the visual (Desktop) view, the content is re-rendered so you can check how it looks and continue editing in either view.

## Guardrails {#guardrails}

When you use the advanced HTML editor, the following guardrails protect content compatibility and set expectations.

* The advanced HTML editor **does not validate** your code. It does not check syntax errors or broken layouts. Review your content carefully before saving.

* Future system updates may overwrite changes you make to default markup. **Your changes may not persist**.

* [!DNL Adobe] support **cannot troubleshoot or resolve** issues caused by custom code and manual changes. Keep a backup of your content in case you need to revert.

* You cannot simulate content in advanced HTML view. Switch to Desktop view to preview your content.

* To ensure content compatibility, **you cannot save** in advanced HTML view. Switch back to Desktop view when you are ready to save your changes.

## Access advanced HTML mode {#access-html-mode}

To open the advanced HTML editor and edit your template source, follow these steps.

1. Open or [create an email template](/help/marketo/product-docs/email-marketing/email-designer/email-template-authoring.md#create-an-email-template) in the Email Designer.

1. In the _Edit email template_ screen, click the HTML button in the top-right corner.

   ![](assets/advanced-html-mode-1.png){width="800" zoomable="yes"}

1. The first time you open the advanced HTML editor, a warning message displays. Review it click **[!UICONTROL OK]** when done.

   ![](assets/advanced-html-mode-2.png)

    >[!NOTE]
    >
    >This warning appears the first time you open the advanced HTML editor and resets each month.

1. The advanced HTML editor displays.

   ![](assets/advanced-html-mode-3.png){width="800" zoomable="yes"}

1. Add the desired changes to your email content.

    >[!WARNING]
    >
    >Make sure to enter correct HTML and CSS code as there is no syntax validation process and Adobe Support cannot assist with HTML edits.

1. Content simulation and saving are not available in advanced HTML view for compatibility reasons. Switch back to Desktop view to preview your content and save your changes.

   ![](assets/advanced-html-mode-4.png){width="800" zoomable="yes"}

    >[!NOTE]
    >
    >Your edits are preserved when you switch views.
