---
unique-page-id: 11371040
description: Email Template Syntax - Marketo Docs - Product Documentation
title: Email Template Syntax
---

# Email Template Syntax {#email-template-syntax}

In Marketo's new Email 2.0 Experience, email templates are composed of any combination of Elements, Variables, Modules, or Containers. Each is defined by adding Marketo-specific syntax to your HTML. Old (v1.0) email templates are supported in Email Editor 2.0; however, they will not include all of the new Editor's features.

Marketo email syntax only works in templates and individual emails; it does **not** work if embedded in snippets or Rich Text tokens.

>[!NOTE]
>
>Marketo Support is not set up to assist with CSS/HTML. If you are not familiar with CSS/HTML, please consult your developer.

>[!CAUTION]
>
>Class values containing Marketo syntax (i.e. mktoModule, mktoContainer, mktoText) are case sensitive. Custom attribute names (i.e. mktoimgwidth, mktoname) are not.

# Elements {#elements}

Elements are content regions that you define as editable in your email template. The editing experience of an element is unique to its type and offers a simple way to work with content. The possible elements that can be included in an email template are:

* Rich Text
* Images
* Snippets
* Videos

## Rich Text {#rich-text}

If you define a region as Rich Text, users will be able to edit its contents [using Marketo's Rich Text Editor](../../../../product-docs/email-marketing/general/understanding-the-email-editor/using-the-rich-text-editor.md). There are two ways to define a Rich Text element inside of an email template: mktEditable and mktoText. Keep in mind, a&nbsp;Rich Text element can always be converted into a snippet from within the email editor.

###### Option 1 - mktEditable {#option-mkteditable}

Because Email Editor 2.0 is backward compatible, some old email templates may specify rich text elements by adding class="mktEditable" on any HTML element. This is still supported, and the ID of the element is what will be used as the display name inside the email editor.

Required attributes  
**class**: "mktEditable".  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
  
Optional attributes  
**mktoName** : String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.  
  
Default value   
The content within the HTML element (if provided) with class="mktEditable" will be used as the default value for the Rich Text element.

Example:
`<pre data-theme="Confluence"><div class="mktEditable" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div></pre>` 

###### Option 2 - mktoText {#option-mktotext}

It's recommended to specify Rich Text elements using the class="mktoText" syntax. This ensures there is always a proper display name for the element.

Required attributes  
**class**: "mktoText"  
**id**: ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName** : String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.  
  
Default Value   
The content within the HTML element (if provided) with class="mktoText" will be used as the default value for the Rich Text element.&nbsp;

Example:
`<pre data-theme="Confluence"><div class="mktoText" id="exampleText" mktoName="Main Body Text"> Optionally add default text for the editable text area. </div></pre>` 

## Images {#images}

You have two options for defining editable Image elements. You may use either a <div>, which specifies a container that the <img> will be inserted into, or an <img> tag. If you intend for the end user to simply pick an image that will return the image URL (as opposed to the DOM), please refer to "image variables" in the section below. The following two options will insert an HTML <img> element.

###### Option 1 - Use a <div> {#option-use-a-div}

Required attributes  
**class:** "mktoImg".  
**id:** ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName :** String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.

Optional attributes  
**mktoImgClass:** String. The value here will be added to the class attribute of the <img> element inside the div.  
**mktoImgSrc:** To be used as the default value for the image that is placed within this div. A placeholder is used if this is omitted.  
**mktoImgLink:** Indicate that the <img> should be surrounded by an <a> tag with this destination URL. The user can change this in the Email Editor.  
**mktoImgLinkTarget:** Indicate that the <a> tag from the mktoImgLink attribute should use this target. Has no effect if mktoImgLink is not also used.  
**mktoImgWidth:** Used as the width on the enclosed <img>.  
**mktoImgHeight:** Used as the height on the enclosed <img>.  
**mktoLockImgSize:** Used to unlock the <img> element's height and width property so that the end user can modify (default is true if omitted).  
**mktoLockImgStyle:** Used to lock the <img> element's style property (default is false).

Default value (optional)  
**<img>**:&nbsp;To be used as the <img> element that the image will be placed in. Useful if you want to add inline styling to the image. Remember to include surrounding <a> </a> tags, so if the user adds a link, your styling won't be stripped!

Example:
`<pre data-theme="Confluence"><div class="mktoImg" id="exampleImg" mktoName="Example Image" mktoImgLink="http://www.marketo.com"> <a><img style="border:10px solid red;"></a> </div></pre>` 

###### Option 2 - Use an <img> {#option-use-an-img}

>[!NOTE]
>
>This option does not allow end users to add a link to their image. Use Option 1 if this is important to your template.

Required attributes   
**class:** "mktoImg".   
**id:** ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.   
**mktoName:** String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.  Default value (optional)  
**src:** To be used as the default value for the image. A placeholder is used if this is omitted.  
**mktoLockImgSize:** Used to unlock the <img> element's height and width property so that the end user can modify (default is true if omitted).  
**mktoLockImgStyle:** Used to lock the <img> element's style property (default is false).

Example:
`<pre data-theme="Confluence"><img class="mktoImg" id="exampleImg" mktoName="Example Image"></pre>` 

## Snippets {#snippets}

If you define a region as a Snippet, end users will be able to choose which approved [Snippet](../../../../product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email.md)they'd like to insert in this region. Although Rich Text elements can be converted into Snippets from within the email editor, when you define a region specifically as a Snippet it cannot be converted to Rich Text.&nbsp;You can specify a Snippet region using a <div> with class=”mktoSnippet”

Required attributes  
**id: **ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName:** String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.

Default value (optional)  
**mktoDefaultSnippetId**:&nbsp;The numerical ID of the Marketo Snippet that should appear by default (will only work if a Snippet with that ID exists and is approved in that workspace).

Example:
`<pre data-theme="Confluence"><div class="mktoSnippet" id="unsubscribeFooter" mktoName="Unsubscribe Footer" mktoDefaultSnippetId="12"></div></pre>` 

## Video {#video}

If you define a region as a Video, end users will be able to insert either a YouTube or Vimeo URL that will be displayed as a thumbnail image (with 'play' button) inside of the email. You can specify a Video region using a <div> with class=”mktoVideo"

Required attributes  
**id: **ID string. Contains only letters, numbers, dash "-", and underscore "_". No spaces allowed. Must be unique.  
**mktoName:** String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.

Optional attributes  
**mktoImgClass:** String. The value here will be added to the class attribute of the video thumbnail <img> inside the div.

Example:
`<pre data-theme="Confluence"><div class="mktoVideo" id="productVideo" mktoName="Product Announcement Video"></div></pre>` 

# Variables {#variables}

Variables are like tokens. You first define them within the <head> section of your email template using <meta> tags, then use them as many times as you want throughout your template. Because they’re defined in the template, the end user will be able to modify their values according to their rules. Note that you can define a variable as local or global in scope. If you use a variable within a "Module" (see below), and an end user duplicates that module, local variables will have independent values, while global variables will apply to both modules.

## String {#string}

If you specify a variable as a String, the end user will be able to enter text within a text box in the email editor. You specify a String variable using <meta> with class=“mktoString”

Required attributes  
**id:** How you reference the variable within your email template.  
**mktoName:** String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.

Optional attributes  
**allowHTML:** Boolean. Controls if the variable's value is HTML-escaped. Defaults to False if omitted.**default**: Default value for the string. Blank if omitted.  
**mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module.&nbsp;Defaults to False if omitted.

Example Declaration:
`<pre data-theme="Confluence"><meta class="mktoString" id="textHeader" mktoName="Text Header" default="Edit Me"></pre>` Example Usage:
`<pre data-theme="Confluence">${textHeader}</pre>` 

## List {#list}

If you specify a variable as a List, the end user will be able to pick from a set of values you define in the email editor. You specify a List variable using <meta> with class=“mktoList”

Required attributes  
**id**:&nbsp;How you reference the variable within your email template.  
**mktoName:** String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.  
**values:** Comma separated list of values. Must have at least one string.

Optional attributes  
**default:** Default value of the select dropdown. If omitted, the first value from the "values" attribute is used.  
**mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. Defaults to False if omitted.

Example Declaration:
`<pre data-theme="Confluence"><meta class="mktoList" id="textFontFamily" mktoName="Main Text Font Family" values="Arial,Verdana,Times New Roman"></pre>` Example Usage:
`<pre data-theme="Confluence">${textFontFamily}</pre>` 

## Number {#number}

If you specify a variable as a Number, the end user will be able to enter a number in the email editor. You specify a Number variable using <meta> with class=”mktoNumber”

Required attributes  
**id**:&nbsp;How you reference the variable within your email template.  
**mktoName**: String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.  
**default:** Default numeric value for the variable.

Optional attributes  
**min:** Min accepted value.  
**max:** Max accepted value.  
**units:** Units to be appended to the number value (ex: px, pt, em, etc.) when displayed in the Email Editor, as well as in the resulting code.  
**step:** How many units the number variable should increase/decrease by (0.1, 1, 10, etc.). If omitted, defaults to 1. 
**mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. Defaults to False if omitted.

Example Declaration:
`<pre data-theme="Confluence"><meta class="mktoNumber" id="textFontSize" mktoName="Main Text Font Size" default="12" min="8" max="18" units="px" step="1"> </pre>` Example Usage:
`<pre data-theme="Confluence">${textFontSize}</pre>` 

## Color {#color}

If you specify a variable as a Color, the end user will be able to enter a hexadecimal color value or choose a color from the color picker within the email editor. You specify a Color variable using <meta> with class=“mktoColor”

Required attributes  
**id**:&nbsp;How you reference the variable within your email template.  
**mktoName**: String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.

Optional attributes  
**default:** Default value for the color. 6-digit hex color code. Ex: #ffffff.  
**mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. Defaults to False if omitted.

Example Declaration:
`<pre data-theme="Confluence"><meta class="mktoColor" id="textColor" mktoName="Main Text Color" default="#FFFFFF"></pre>` Example Usage:
`<pre data-theme="Confluence">${textColor}</pre>` 

## Boolean {#boolean}

If you specify a variable as a Boolean, the end user will be able to toggle the option on/off within the email editor. You specify a Boolean variable using&nbsp;<meta> with class=“mktoBoolean”

Required attributes  
**id**:&nbsp;How you reference the variable within your email template.  
**mktoName**: String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.

Optional attributes  
**default:** Boolean value determining the default state of the toggle switch. False if omitted.  
**false_value:** Value to be inserted when toggle is in OFF position. False if omitted.  
**true_value:** Value to be inserted when toggle is in ON position. True if omitted.  
**false_value_name:** UI shown in the toggle when in OFF position. False if omitted.  
**true_value_name:** UI shown in the toggle when in ON position. True if omitted.  
**mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. Defaults to False if omitted.

Example Declaration:
`<pre data-theme="Confluence"><meta class="mktoBoolean" id="showFooter" mktoName="Show Footer BG?" default="false" false_value="transparent" true_value="black" false_value_name="NO" true_value_name="YES"></pre>` Example Usage:
`<pre data-theme="Confluence">${showFooter}</pre>` 

## HTML Block {#html-block}

If you specify a variable as an HTML Block, the end user will be able to input verbatim HTML from within the email editor. You specify an HTML Block variable using <meta> with class=”mktoHTML”

Required attributes  
**id**:&nbsp;How you reference the variable within your email template.  
**mktoName**: String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.

Optional attributes**default:** HTML encoded value to serve as the default contents of the block.  
**mktoModuleScope**: Boolean. Controls whether the variable is local (true) or global (false) when used in a module. Defaults to False if omitted.

Example Declaration:
`<pre data-theme="Confluence"><meta class="mktoHTML" id="trackingPixel" mktoName="Add Tracking Pixel"></pre>` Example Usage:
`<pre data-theme="Confluence">${trackingPixel}</pre>` 

## Image Variable {#image-variable}

If you specify a variable as an Image, the end user will be able to choose an image from the image picker within the email editor. The selected image URL will be the value of the variable. You specify an Image variable using&nbsp;<meta> with class="mktoImg"

Required attributes  
**id**:&nbsp;How you reference the variable within your email template.  
**mktoName**: String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.

Optional attributes  
**default:** Default image URL for the element.  
**mktoModuleScope**: Boolean.&nbsp;Controls whether the variable is local (true) or global (false) when used in a module.&nbsp;Defaults to False if omitted.

Example Declaration:
`<pre data-theme="Confluence"><meta class="mktoImg" id="heroBackgroundImage" mktoName="Hero Background Image" default="http://www.company.com/image.jpg"></pre>` Example Usage:
`<pre data-theme="Confluence">${heroBackgroundImage}</pre>` 

# Modules {#modules}

Modules are templatized sections defined at the template level that will show up for end users to insert into their email. Because you have pre-built these modules, you can ensure they will interact with the rest of your email content gracefully (in a fully responsive manner). You can only put a module in a container.

**For containers of type <table>, <tbody>, <thead>, or <tfoot>:**

Specified using <tr> with class=”mktoModule”

**For containers of type <td>:**

Specified using <table> with class="mktoModule"

Required attributes  
**id**:&nbsp;How you reference the module within your email template.  
**mktoName**: String. This is the display name that will be shown in Email Editor 2.0. Best practice is to use a descriptive name.

Optional attributes  
**mktoActive:** Determines whether this module appears in the list of modules within the email editor. Defaults to true. If false, the module cannot be added by an end user to an email.   
**mktoAddByDefault:** Determines whether this module will be in the canvas of a new email that uses this template upon creation. Defaults to true (if mktoActive is false, this value is ignored).

>[!NOTE]
>
>**Reminder**
>
>Class values containing Marketo syntax (i.e. mktoModule, mktoContainer, mktoText) are case sensitive. Custom attribute names (i.e. mktoimgwidth, mktoname) are not.

# Containers {#containers}

A container holds Modules and defines where they can be placed. When end users are re-ordering and inserting modules into their email, the container controls where they may go.

**Specified using either <table>, <tbody>, <thead>, <tfoot> or <td> with class=”mktoContainer”**

Required attributes  
**id**:&nbsp;How you reference the module within your email template.

>[!CAUTION]
>
>Containers can only contain Modules-if there's anything else present, the Container is considered invalid! Only one container is allowed per template.

