---
solution: Marketo Engage
product: marketo
title: Content components
description: DESCRIPTION.
level: Beginner, Intermediate
feature: Email Designer
hide: yes
hidefromtoc: yes
---
# Content components {#content-components}

When creating your email content, **[!UICONTROL Content components]** allow you to further personalize your email with raw components that you can edit once placed in an email.

You can add as many content components as you need inside one or more structure components, which define the layout of your email.

## Add content components {#add-content-components}

To add content components to your email and adjust them to your needs, follow the steps below.

1. In the Email Designer, use an existing content or drag and drop **[!UICONTROL Structure components]** into your empty content to define the layout of your email. `[Learn how](content-from-scratch.md)`

1. To access the **[!UICONTROL Content components]** section, select the corresponding button from the Email Designer left pane.

   SCREENSHOT

1. Drag and drop the content components of your choice inside the relevant structure components.

   SCREENSHOT

    >[!NOTE]
    >
    >You can add several components into a single structure component and into each column of a structure component.

1. Adjust the attributes and styling for each component using the **[!UICONTROL Settings]** and **[!UICONTROL Style]** tabs on the right. For example, you can change the text style, padding or margin of each component. `[Learn more about alignment and padding](alignment-and-padding.md)`

   SCREENSHOT

1. From the advanced menu of your **[!UICONTROL Content component]**, you can easily delete or duplicate any content components as needed.

   SCREENSHOT

## Container {#container}

To apply specific styling to a group of content components, you can add a **[!UICONTROL Container]** component and then add your desired content component(s) inside it. This enables you to apply a distinct style to the container, which will differ from the style applied to the content components inside.

For example, add a **[!UICONTROL Container]** component and then add a [Button](#button) component inside that container. You can use a specific background for the container, and another one for the button.

   SCREENSHOT

## Button {#button}

Use the **[!UICONTROL Button]** component to insert one or multiple buttons into your email and redirect your email audience to another page.

1. From **[!UICONTROL Content components]**, drag and drop the **[!UICONTROL Button]** component into a **[!UICONTROL Structure component]**.

1. Click your newly added button to personalize the text and to have access to the **[!UICONTROL Settings]** and **[!UICONTROL Styles]** tabs in the Email Designer right pane.

   SCREENSHOT

1. From the **[!UICONTROL Link]** menu, add the URL you want to redirect to when clicking the button.

1. Choose how your audience will be redirected with the **[!UICONTROL Target]** drop-down list:

    * **[!UICONTROL None]**: opens the link in the same frame as it was clicked (default).
    * **[!UICONTROL Blank]**: opens the link in a new window or tab.
    * **[!UICONTROL Self]**: opens the link in the same frame as it was clicked.
    * **[!UICONTROL Parent]**: opens the link in the parent frame.
    * **[!UICONTROL Top]**: opens the link in the full body of the window.

   SCREENSHOT

1. You can further personalize your button by changing styling attributes such as **[!UICONTROL Border]**, **[!UICONTROL Size]**, **[!UICONTROL Margin]**, etc. from the **[!UICONTROL Component settings]** pane.

## Text {#text}

Use the **[!UICONTROL Text]** component to insert text into your email, and adjust the style (border, size, padding, etc.) using the **[!UICONTROL Styles]** tab.

   SCREENSHOT

1. From **[!UICONTROL Content components]**, drag and drop the **[!UICONTROL Text]** component into a **[!UICONTROL Structure component]**.

1. Click your newly added component to personalize the text and to have access to the **[!UICONTROL Settings]** and **[!UICONTROL Styles]** tabs in the right pane of the Email Designer.

1. Change your text with the following options available in the toolbar:

   SCREENSHOT

    * **[!UICONTROL Change text style]**: apply bold, italic, underline or strike through to your text.
    * **Change alignment**: choose between left, right, center or justified alignment for your text.
    * **[!UICONTROL Create list]**: add bullet or number list to your text.
    * **[!UICONTROL Set heading]**: add up to six heading levels to your text.
    * **Font size**: select the font size of your text in pixels.
    * **[!UICONTROL Change font color]**: choose the color of your font.
    * **[!UICONTROL Insert link]**: add any type of link to your content.
    * **[!UICONTROL Edit image]**: add an image or an asset to your text component. `[Learn more about asset management](../integrations/assets.md)`
    * **[!UICONTROL Change font color]**: choose the color of your font.
    * **[!UICONTROL Add personalization]**: add personalization fields to customize the content from your profiles data. `[Learn more about content personalization](../personalization/personalize.md)`
    * **[!UICONTROL Show the source code]**: display the source code of your text. It cannot be modified.
    * **[!UICONTROL Enable conditional content]**: add conditional content to adapt the content of the component to the targeted profiles. `[Learn more about dynamic content](../personalization/get-started-dynamic-content.md)`
    * **[!UICONTROL Duplicate]**: add a copy of your text component.
    * **[!UICONTROL Delete]**: delete the selected text component from your email.

1. Adjust the other styling attributes such as text color, font family, border, padding, margin, etc. from the **[!UICONTROL Styles]** tab.

   SCREENSHOT

## Divider {#divider}

Use the **[!UICONTROL Divider]** component to insert a dividing line to organize the layout and content of your email.

You can adjust styling attributes such as the line color, style and height from the **[!UICONTROL Settings]** and **[!UICONTROL Styles]** tabs.

   SCREENSHOT

## HTML {#HTML}

Use the **[!UICONTROL HTML]** component to copy-paste the different parts of your existing HTML. This enables you to create free modular HTML components to reuse some external content.

1. From **[!UICONTROL Content Components]**, drag and drop the **[!UICONTROL HTML]** component into a **[!UICONTROL Structure component]**.

1. Click on your newly added component, then select **[!UICONTROL Show the source code]** from the contextual toolbar to add your HTML.

   SCREENSHOT

1. Copy-paste the HTML code you want to add to your email and click **[!UICONTROL Save]**.

   SCREENSHOT

>[!NOTE]
>
>To simply make an external content compliant with the Email Designer, Adobe recommends creating a message from scratch and copy the content from your existing email into components.

## Image {#image}

Use the **[!UICONTROL Image]** component to insert an image file from your computer into your email content.

1. From **[!UICONTROL Content components]**, drag and drop the **[!UICONTROL Image]** component into a **[!UICONTROL Structure component]**.

   SCREENSHOT

1. From the **[!UICONTROL Settings]** tab, click **[!UICONTROL Browse]** to choose an image file from your assets or **[!UICONTROL Import media]** to upload an asset to Adobe Experience Manager Assets.

   To learn more about [!DNL Adobe Experience Manager Assets], refer to [Adobe Experience Manager Assets documentation](https://experienceleague.adobe.com/docs/experience-manager-assets-essentials/help/introduction.html){target="_blank"}.

    >[!NOTE]
    >
    > To ensure your links remain active and avoid any expiration issues, we recommend using Adobe Assets instead of relying on a source URL for your images.

1. You can also directly search in Adobe Stock with the **[!UICONTROL Find Adobe Stock photos]** option.

1. Click your newly added component and set up your image properties:

    * **[!UICONTROL Image title]** lets you define a title to your image.
    * **[!UICONTROL Alt text]** lets you define the caption linked to your image. This corresponds to the alt HTML attribute.

   SCREENSHOT

1. You can also choose to **[!UICONTROL Find similar Stock photos]**. `[Learn more](../integrations/stock.md)`

1. From the **[!UICONTROL Styles]** tab, adjust the other styling attributes such as margin, border, etc. or adding a link to redirect your audience to another content from the **[!UICONTROL Component settings]** pane.

## Social {#social}

Use the **[!UICONTROL Social]** component to insert links to social media pages into your email content.

1. From **[!UICONTROL Content Components]**, drag and drop the **[!UICONTROL Social]** component into a **[!UICONTROL Structure component]**.

1. Select your newly added component.

1. In the **[!UICONTROL Social]** field of the **[!UICONTROL Settings]** tab, choose which social media you want to add or remove.

   SCREENSHOT

1. Choose the size of your icons through the dedicated field.

1. Click each of your social media icons to configure the **[!UICONTROL URL]** to which your audience will be redirected.

   SCREENSHOT

1. You can also change the icons of each of your social media if needed from your Assets.

1. Adjust the other styling attributes such as style, margin, border, etc. from the **[!UICONTROL Styles]** tab.

## Offer decision {#offer-decision}

Use the **[!UICONTROL Offer decision]** component to insert offers into your messages. The `[decision management](../offers/get-started/starting-offer-decisioning.md)` engine will pick the best offer to deliver to your customers.

1. From **[!UICONTROL Content Components]**, drag and drop the **[!UICONTROL Offer decision]** component into a **[!UICONTROL Structure component]**.

1. Click **[!UICONTROL Add]** to select your **[!UICONTROL Offer decision]**.

   SCREENSHOT

1. From the drop-down, select your **[!UICONTROL Placements]**.  Then, select the the **[!UICONTROL Offer decision]** you want to add to your content and click **[!UICONTROL Add]**.

   SCREENSHOT

1. From the **[!UICONTROL Offer decision]** tab, you can preview or change the inserted Offer.

Learn how to add personalized offers into an email in `[this section](add-offers-email.md)`.

>[!IMPORTANT]
>
>If changes are made to an offer decision which is being used in a journey's message, you need to unpublish the journey and republish it.  This will ensure that the changes are incorporated into the journey's message and that the message is consistent with the latest updates.
