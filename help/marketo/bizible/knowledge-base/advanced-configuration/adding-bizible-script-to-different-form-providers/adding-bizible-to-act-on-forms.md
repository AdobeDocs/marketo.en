---
unique-page-id: 18874753
description: Adding Bizible to Act-On Forms - Bizible - Product Documentation
title: Adding Bizible to Act-On Forms
---

# Adding Bizible to Act-On Forms {#adding-bizible-to-act-on-forms}

Adding Bizible to Act-On Forms - Bizible - Product Documentation

#### Directions {#addingbizibletoact-onforms-directions}

##### 1. In the form you're editing, select the Settings option in the right hand corner. {#addingbizibletoact-onforms-intheformyou'reediting-selectthesettingsoptionintherighthandcorner.}

##### 2. Look for an area labeled "External Web Analytics." This will be where you drop the Bizible tracking code snippet. {#addingbizibletoact-onforms-lookforanarealabeled"externalwebanalytics."thiswillbewhereyoudropthebizibletrackingcodesnippet.}

#### Bizible's JavaScript {#addingbizibletoact-onforms-bizible'sjavascript}

*<script type="text/javascript" src="//cdn.bizible.com/scripts/bizible.js" async=""></script>*

>[!NOTE]
>
>There may already be other tracking code snippets in this area, such as a Google Analytics code. Be sure to separate them using a semicolon (;) and a single space, like so:   
  
><script type="text/javascript" src="//cdn.bizible.com/scripts/bizible.js" async=""></script> `**; **`<script async="true" type="someothercode" src="someotherfile.js" ></script>

