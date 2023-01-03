---
unique-page-id: 2953419
description: Using the Rich Text Editor - Marketo Docs - Product Documentation
title: Using the Rich Text Editor
exl-id: 9b2d6d41-f947-4859-aad9-a10c15eb013a
---
# Using the Rich Text Editor {#using-the-rich-text-editor}

The Rich Text Editor (RTE) appears throughout Marketo and is available whenever you want to add or edit content. You'll see a version of it on landing pages, programs, emails, forms, and snippets. Just click **[!UICONTROL Edit Draft]**, and it'll pop up to serve you.

## Editor Settings {#editor-settings}

The root block element setting defines which tags wrap your content. By default, the email root block element utilizes `<p>` tags. You have the option to change that by following the steps below.

>[!TIP]
>
>While you have the option to choose your root block element, we always recommend using default settings for the best user experience.

1. Click **[!UICONTROL Admin]**.

   ![](assets/one.png)

1. Click **[!UICONTROL Email]**.

   ![](assets/two.png)

1. Click **[!UICONTROL Edit Text Editor Settings]**.

   ![](assets/three.png)

1. In the **[!UICONTROL Email] / [!UICONTROL Snippet Editor]** drop-down, select `<div>` or [!UICONTROL None] and click **[!UICONTROL Save]**. `<div>` is used in this example.

   ![](assets/four.png)

   If you have `<div class=“mktEditable”></div>` in an Email Template, you will see the following HTML Source behavior when you open the section and type “Text Goes Here” in the editor:

<table> 
 <tbody> 
  <tr> 
   <th>&lt;p&gt;</th> 
   <th>&lt;div&gt;</th> 
   <th>None</th> 
  </tr> 
  <tr> 
   <td><p>&lt;div class=“mktEditable”&gt;<br>&lt;p&gt;Text Goes Here&lt;/p&gt;<br>&lt;/div&gt;</p></td> 
   <td><p>&lt;div class=“mktEditable”&gt;<br>&lt;div&gt;Text Goes Here&lt;/div&gt;<br>&lt;/div&gt;</p></td> 
   <td><p>&lt;div class=“mktEditable”&gt;<br>Text Goes Here<br>&lt;/div&gt;</p></td> 
  </tr> 
 </tbody> 
</table>

   >[!TIP]
   >
   >You can also change the Landing Page Editor's root block element by following the same steps, but clicking the **[!UICONTROL Landing Page Editor]** drop-down in Step 4 instead of [!UICONTROL Email] / [!UICONTROL Snippet Editor].

   >[!NOTE]
   >
   >The root block element is always `<p>` for rich-text program tokens.

## Features {#features}

Here are the features you'll find in an RTE.

| Icon |Name |What it does |
|---|---|---|
| ![--](assets/image2015-7-9-10-3a23-3a24.png)|[!UICONTROL Font Family] |Choose your style--we've got plenty! |
| ![--](assets/image2015-7-9-10-3a22-3a11.png)|[!UICONTROL Font Size] |How big do you want it? 25 choices, from 8px to 90px. |
| ![--](assets/image2015-7-9-10-3a59-3a4.png)|[!UICONTROL Styles] |Choose Paragraph or a six Heading styles (for landing pages). |
| ![--](assets/image2015-7-9-10-3a20-3a1.png)|[!UICONTROL Line Spacing] |Pick your distance between the lines. |
| ![--](assets/image2015-7-9-10-3a25-3a52.png)|[!UICONTROL Text Color] |Black, red, or whatever you want. |
| ![--](assets/image2015-7-9-10-3a24-3a38.png)|[!UICONTROL Background Color] |Highlight for emphasis. |
| ![--](assets/image2015-7-9-10-3a28-3a4.png)|[!UICONTROL Bold] |**Darker and thicker**. |
| ![--](assets/image2015-7-9-10-3a29-3a1.png)|[!UICONTROL Italic] |*Angled, for emphasis or quotation*s. |
| ![--](assets/image2015-7-9-10-3a30-3a56.png)|[!UICONTROL Underline] |Puts a line under your text. |
| ![--](assets/image2015-7-9-10-3a31-3a57.png)|[!UICONTROL Alignment] |Use this dropdown to lay out your text and images. Center them, choose left or right alignment, or spread it edge to edge with full justification. || ![--](assets/image2015-7-9-10-3a32-3a47.png)|List |Choose bullets or numbers from the dropdown. Bullets are good with lists and numbers with steps. |
| ![--](assets/image2015-7-9-10-3a38-3a0.png)|[!UICONTROL Indent] |Choose more or less indentation. Use for paragraphs or any text you want to stand out. |
| ![--](assets/image2015-7-9-10-3a38-3a58.png)|[!UICONTROL Insert/Edit Link] |Put in a link to a website or other content; easily make changes to it. |
| ![--](assets/image2015-7-9-10-3a39-3a42.png)|[!UICONTROL Insert/Edit Image] |A picture is worth a thousand words. Drop one in. Click the camera icon to browse your Design Studio. You can drop in images side by side. |
| ![--](assets/image2015-7-9-10-3a40-3a36.png)|[!UICONTROL Insert Token] |A powerful tool, great for email personalization and data tracking. Be sure to enter a default value. |
| ![--](assets/image2015-7-9-10-3a41-3a21.png)|[!UICONTROL Undo] |Oops! Let's you go back a step and try it again. |
| ![--](assets/image2015-7-9-10-3a42-3a13.png)|[!UICONTROL Redo] |If it's really OK as it is, return to the original. |
| ![--](assets/image2015-7-9-10-3a43-3a29.png)|[!UICONTROL Table] |Build your own, like this one. A drop-down menu lets you configure it. |
| ![--](assets/image2015-7-9-10-3a45-3a1.png)|[!UICONTROL Insert Anchor] |Drop anchor! |
| ![--](assets/image2015-7-9-10-3a45-3a48.png)|[!UICONTROL Horizontal Line] |Many uses - Great for dividing sections. |
| ![--](assets/image2015-10-6-12-3a12-3a17.png)|[!UICONTROL Edit HTML] |Pops up the HTML Source Editor so you can tweak your code. |
| ![--](assets/image2015-7-9-10-3a47-3a36.png)|[!UICONTROL Subscript] |Low-hanging letters (as in O`<sub>2</sub>`). |
| ![--](assets/image2015-7-9-10-3a48-3a35.png)|[!UICONTROL Superscript] |You have the power! (2`<sup>6</sup>`). |
| ![--](assets/image2015-7-9-10-3a49-3a31.png)|[!UICONTROL Strikethrough] |`<s>Put a line through text, like this</s>`. |
| ![--](assets/image2015-7-9-10-3a50-3a11.png)|[!UICONTROL Special Character] |Want to talk about euros? Math? You have 243 choices. |
| ![--](assets/image2015-7-9-10-3a52-3a26.png)|[!UICONTROL Find and Replace] |Search for and change things much faster than looking for each instance yourself. |
| ![--](assets/image2015-7-9-10-3a53-3a37.png)|[!UICONTROL Clear Formatting] |Return things to standard. |
| ![--](assets/image2015-7-9-10-3a55-3a2.png)|[!UICONTROL Cancel] |Press the button to say, "Never mind." |
| ![--](assets/image2015-7-9-10-3a56-3a2.png)|[!UICONTROL Save] |Press the button to say, "OK, I like it." |

>[!TIP]
>
>You edit your HTML and text on separate screens. Be sure to click **[!UICONTROL Copy from HTML]** on the **[!UICONTROL Text]** tab and then **[!UICONTROL Save]** so your text matches your HTML.

>[!NOTE]
>
>You are not limited to the fonts in the drop-down. You can use one not listed by accessing the HTML code. All web fonts are supported in Marketo, but web fonts do not work universally in all email clients.

## Landing Pages {#landing-pages}

The root block element setting defines which tags wrap your content. By default, the landing page root block element utilizes `<div>` tags. You have the option to change that, by following the steps below.

>[!TIP]
>
>While you have the option to choose your root block element, we always recommend using default settings for the best user experience.

1. Click **[!UICONTROL Admin]**.

   ![](assets/one.png)

1. Click **[!UICONTROL Email]**.

   ![](assets/two.png)

1. Click **[!UICONTROL Edit Text Editor Settings]**.

   ![](assets/three.png)

1. In the **[!UICONTROL Landing Page Editor]** drop-down, select `<p>` or [!UICONTROL None] and click **[!UICONTROL Save]**. `<p>` is used in this example.

   ![](assets/five.png)

   And that's it!
