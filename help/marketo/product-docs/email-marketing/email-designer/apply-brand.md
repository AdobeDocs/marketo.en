---
solution: Marketo Engage
product: marketo
title: TITLE
description: Learn how to streamline email creation with reusable themes and modules, ensuring design consistency and efficiency.
feature: Email Designer
role: User
level: Beginner, Intermediate
hide: yes
hidefromtoc: yes
exl-id: 349ee021-7341-40e0-8d8c-d041f1a8f343
---
# Apply themes to your email content {#apply-email-themes}

>[!AVAILABILITY]
>
>This capability is currently in beta version and only available to beta customers. To join the beta program, contact your Adobe representative.

With themes, non-technical users have the ability to create reusable content that fits a specific brand and design language by adding custom styling on top of the standard templates<!-- to achieve brand specific results-->.

This feature empowers marketers to leverage visually appealing, brand-consistent emails faster and with less effort, while providing advanced customization options for unique design needs.

<!--What is the Enhanced Email Authoring Experience?

This feature introduces two key components to simplify and enhance email creation:

* **Theme Management System**: A centralized system for creating, customizing, and applying reusable themes to emails. Themes ensure consistent styling across campaigns and eliminate the need for repetitive manual styling.

* **Modules**: Pre-designed, reusable content blocks that abstract common email elements (e.g., titles, descriptions, images, and links). Modules are built using customizable low-level components, offering flexibility while maintaining design standards.

Key Benefits:

- **Consistency**: Ensure all emails align with your brand's design guidelines.
- **Efficiency**: Save time by reusing themes and modules across campaigns.
- **Customization**: Add custom CSS and mobile-specific styles for advanced designs.
- **Scalability**: Eliminate repetitive styling tasks, enabling faster email creation.-->

## Guardrails and limitations {#themes-guardrails}

* When creating an email from scratch, you can choose to start building your content using a theme to quickly apply a specific styling that fits your brand and design.

   If you choose the _Manual Styling_ mode, you won't be able to apply any themes unless you reset your email.

* [Fragments](/help/marketo/product-docs/email-marketing/email-designer/fragments.md) are not cross-compatible between the _Use Themes_ and _Manual Styling_ modes.

   To be able to use a fragment in a content where a theme is applied, this fragment must be created in _Use Themes_ mode.

* If using content created in HTML, you will be in [compatibility mode](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#import-html) and cannot apply themes to this content.

   To fully leverage all the capabilities of the Email Designer, including themes, you must either create new content in _Use Themes_ mode, or convert your [imported HTML content](/help/marketo/product-docs/email-marketing/email-designer/email-authoring.md#import-html).

<!--If using a content created in Manual Styling mode or HTML, you cannot apply themes to this content. You must create a new content in Use Themes mode.

If you apply a theme to a content using a [fragment](../content-management/fragments.md) created in Manual Styling mode, the rendering may not be optimal.-->

## Create a theme {#create-and-edit-themes}

To define a theme that you can leverage in your future email contents, follow the steps below.

1. To get started, create a new [email template](/help/marketo/product-docs/email-marketing/email-designer/email-template-authoring.md#create-an-email-template).

1. Select the **[!UICONTROL Create or edit themes]** option.

   `![](assets/theme-create.png)`

1. You can either select the default theme, or use an Adobe or custom template. In this example, select the default theme and click **[!UICONTROL Create]**.

   `![](assets/theme-select.png)`

1. In the **[!UICONTROL General settings]** tab, start defining your theme by giving it a specific name for your brand. You can adjust the default width for your emails and also export the current theme to share it across sandboxes.

   `<!--![](assets/theme-general-settings.png)-->`

1. Use the rail on the right to navigate through the different tabs and update your design settings.

   `![](assets/theme-right-pane.png)`

1. From the **[!UICONTROL Colors]** tab:

   * Use the **[!UICONTROL Edit]** button to set up a **[!UICONTROL Color palette]** with default colors for your brand. Select a **[!UICONTROL Preset]** to quickly create a color scheme, or adjust each color of your theme individually. You can also use a combination of both.
   
      `![](assets/theme-colors.gif)`

   * Click **[!UICONTROL Add variant]** to create multiple color variants, such as light and dark mode, where each variant has its own color palette and nuance controls.

      `![](assets/theme-colors-variant.png)`

   * For each variant, click the Edit icon to edit any individual element. You can use the default palette that you have created, or any custom colors.
   
      `![](assets/theme-colors-edit-variant.gif)`

1. In the **[!UICONTROL Text settings]**, you can set the global font that you want to use for your entire theme. For a more granular control, you also can edit each heading and paragraph type to adjust the font, size, style, and so on.

   `![](assets/theme-text.png)`

1. In the **[!UICONTROL Spacing]** tab, select an individual element from the list to properly space it between the different components.

   `<!--![](assets/theme-spacing.png)-->`

1. Using the other tabs on the right, you can manage separately each button element, divider, additional image formatting, and grid layout spacing for this theme.

   `<!--![](assets/theme-buttons.png)-->`

1. Click **[!UICONTROL Save]** to store this theme for future use.

## Apply themes to an email {#apply-themes}

To apply default or custom styling themes to an email, follow the steps below.

1. `In [!DNL Marketo Engage], [add an email](create-email.md) action to a journey or campaign, and [edit your email body](get-started-email-design.md#key-steps).`

1. You can either select one of the following actions:

   * `Select a built-in [email template](use-email-templates.md) to open the Email Designer. A default theme specific to each template is automatically applied.`

   * `Design a [new content from scratch](content-from-scratch.md) and select **[!UICONTROL Use Themes]** to start with a predefined styling theme.`

      `![](assets/theme-from-scratch.png)`

      >[!CAUTION]
      >
      >If you choose the _Manual Styling_ mode, you won't be able to apply any themes unless you reset your email.
      >
      >To use a [fragment](/help/marketo/product-docs/email-marketing/email-designer/fragments.md) in _Use Themes_ mode, this fragment must have been created itself using the _Use Themes_ mode.

1. Once in the Email Designer, click the **[!UICONTROL Themes]** button on the right rail. The default theme or the template's theme is displayed. You can switch between the two color variants for this theme.

   `![](assets/theme-default-hero.png)`

1. Click the arrow next to the theme currently used. The list of available custom and Adobe themes displays.

   `![](assets/theme-hero-change.png)`

1. Click **[!UICONTROL Custom themes]** and select the theme that you created.

   `![](assets/theme-select-custom.png)`

1. Click outside of the drop-down list. The newly selected custom theme automatically applies its styles to all email components. You can toggle between the two color variants.

1. When a component is selected, you can still unlock its style using the dedicated icon.

   `![](assets/theme-unlock-style.png)`

You can switch themes at any time. The email content remains unchanged, but the styles are updated to reflect the new theme.

<!--
>[!NOTE]
> - Themes apply styles globally. Ensure your theme is finalized before applying it to multiple emails.
> - Switching themes may override custom styles applied to individual components.

>[!CAUTION]
> - When using fragments, the email's theme will override the fragment's styles. A warning will be displayed in the editor if there is a conflict.

## Example Use Cases {#example-use-cases}

### 1. Creating a New Theme
- A marketer creates a theme with their brand's colors, fonts, and button styles.
- The theme is saved and reused across multiple email campaigns.

### 2. Switching Themes
- A marketer applies a holiday-themed design to an existing email by switching to a pre-designed holiday theme.-->
