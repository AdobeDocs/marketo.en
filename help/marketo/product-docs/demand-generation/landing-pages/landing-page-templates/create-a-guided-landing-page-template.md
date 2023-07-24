---
unique-page-id: 7515401
description: Create a Guided Landing Page Template - Marketo Docs - Product Documentation
title: Create a Guided Landing Page Template
exl-id: 7d097162-d862-4d09-9440-aba1628450c2
feature: Landing Pages
---
# Create a Guided Landing Page Template {#create-a-guided-landing-page-template}

Guided landing page templates have a special syntax. Use this syntax to specify what is customizable and where content will end up on each landing page built from your template. Only the regions or variables you specify as editable will be available for customization within the “Guided” landing page editor.

>[!TIP]
>
>Use good naming conventions and your marketing team will fall in love with you.

There are two ways to declare that something on your page should be editable:

* Declare an object as an "element". The landing page creator will be able to add images, text, or Marketo assets into those specified regions.
* Declare a string as a "variable". The landing page creator will be able to replace that variable with a string, color, or boolean state from a true/false lever.

## Editable Elements {#editable-elements}

Elements are declared by adding a normal DOM element to the template, then decorating the element with a Marketo-specific class name.

## Text {#text}

If you define a region as Rich Text, users will be able to edit its contents [using Marketo's Rich Text Editor](/help/marketo/product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md).

Required attributes:  
**class**: "mktoText"  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Optional:  
The content of an element with class mktoText (if provided) will be used as the default value for the editable region.

Example:

`<div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area.</div>`

## Image {#image}

You have two options for defining editable Image Elements. You may use either a `<div>`, which specifies a container that the image will be inserted into, or an `<img>` tag.

## Option 1 - Use a `<div>` {#option-use-a-div}

Required attributes:

class: "mktoImg"  
id: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
mktoName : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Optional:  
mktoImgClass: String. The value here will be added to the class attribute of the `<img>` element inside the div.

Example:

`<div class="mktoImg" id="exampleImg" mktoName="Example Image"></div>`

## Option 2 - Use a `<img>` {#option-use-a-img}

Required attributes:  
class: "mktoImg"  
id: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
mktoName : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Optional:  
src: String URL. This will be used as the default value for the image.

Example:

`<img class="mktoImg" id="exampleImg" mktoName="Example Image">`

>[!NOTE]
>
>When using the `<img>` version, the rendered HTML will contain a generated div wrapper around the `<img>` tag. It will be set to class .”mktoImg.mktoGen,” and will be display:inline-block.

## Form {#form}

Example:Required attributes:  
**class**: "mktoForm"  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

`<div class="mktoForm" id="exampleForm" mktoName="Example Form"></div>`

## Snippet {#snippet}

Required attributes:  
**class**: "mktoSnippet"  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Example:

`<div class="mktoSnippet" id="exampleSnippet" mktoName="Example Snippet"></div>`

## Share Button {#share-button}

Required attributes:  
**class**: "mktoShareButton"  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Example:

`<div class="mktoShareButton" id="exampleShareButton" mktoName="Example Share Button"></div>`

## Video {#video}

>[!NOTE]
>
>When using the video element in a landing page, Marketo only supports videos from YouTube. If you use another service, we recommend utilizing a rich text box and pasting in the video's embed code.

Required attributes:
**class**: "mktoVideo"
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.  

Example:

`<div class="mktoVideo" id="exampleVideo" mktoName="Example Video"></div>`

## Poll {#poll}

Required attributes:  
**class**: "mktoPoll"  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Example:

`<div class="mktoPoll" id="examplePoll" mktoName="Example Poll"></div>`

## Referral {#referral}

Required attributes:  
**class**: "mktoReferral"  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Example:

`<div class="mktoReferral" id="exampleReferral" mktoName="Example Referral"></div>`

## Sweepstakes {#sweepstakes}

Required attributes:  
**class**: "mktoSweepstakes"  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Example:

`<div class="mktoSweepstakes" id="exampleSweepstakes" mktoName="Example Sweepstakes"></div>`

## Editable Variables {#editable-variables}

All variable types are used by referencing the value of their id attribute wrapped inside of a ${ } character sequence. They can be used anywhere in the document, except for inside of other variable declarations.

Example:

`${var1}`

**Declaration:**

Variables are declared as meta tags inside the `<head>` element of the template. There are three types of variables available for use: String, Color, and Boolean.

## String {#string}

Required Attributes:  
**class** : "mktoString",  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Optional:  
**default**: String value for the attribute. Blank if none provided.  
**allowHtml**: "true" or "false". Controls if the value will be printed without being HTML escaped. Defaults to "false" if unset.

Basic Example:

`<meta class="mktoString" id="var1" mktoName="My Variable">`

Example with all attributes:

`<meta class="mktoString" id="var1" mktoName="My Variable" default="This is my default value" allowHtml="true">`

## Color {#color}

Required Attributes:  
**class** : "mktoColor",  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Optional:  
**default**: A 7-digit HEX character color code. Eg: "#336699"

Basic Example:

`<meta class="mktoColor" id="color1" mktoName="My Color Variable">` 

Example with all attributes:

`<meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699">`

## Boolean {#boolean}

Required Attributes:  
**class** : "mktoBoolean",  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in the landing page editor. Best practice is to use a descriptive name.

Optional:  
**default**: Boolean string. "true" or "false" controls if the value starts in the ON or OFF position. "false" if not provided.  
**false_value**: String. The value to be inserted for the variable when it is in the OFF position. "false" if not provided.  
**true_value**: String. The value to be inserted for the variable when it is in the ON position. "true" if not provided.  
**false_value_name**: String. The display name to be shown in the landing page editor when the value is in the OFF position. "OFF" if not provided.  
**true_value_name**: String. The display name to be shown in the landing page editor when the value is in the ON position. "ON" if not provided.

Basic Example:

`<meta class="mktoColor" id="color" mktoName="My Color Variable" default="#336699">`

`<meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable">`

Example with all attributes:

This example shows a common use case where a boolean variable controls the visibility of a css element by setting the value of css display property to either "block" or "none" to show/hide an element by id with CSS. The landing page editor will use the display name Show/Hide instead of OFF/ON.

`<meta class="mktoBoolean" id="boolean1" mktoName="My Boolean Variable" default="true" true_value="block" false_value="none" false_value_name="Hide" true_value_name="Show"> <style> #myConditionalDisplayArea { display: ${boolean1}; } </style>`

>[!NOTE]
>
>Program tokens (my.token) can also be used anywhere in Guided or Free-form landing pages.
