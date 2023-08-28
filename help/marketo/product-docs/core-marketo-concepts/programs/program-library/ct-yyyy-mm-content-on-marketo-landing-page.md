---
description: CT-YYYY-MM-Content on Marketo LP - Marketo Docs - Product Documentation
title: CT-YYYY-MM-Content on Marketo LP
hide: yes
hidefromtoc: yes
feature: Programs
---
# CT-YYYY-MM-Content on Marketo Landing Page {#ct-yyyy-mm-content-on-marketo-landing-page}

This example is designed to be a content program that leverages a Marketo Engage Landing Page with a Marketo Engage form utilizing a Marketo Engage default program. The form is to access the content/offer. The link to the offer can be displayed on the thank you page, sent in a thank you email, or both. 

For further strategy assistance or help customizing a program, please contact the Adobe Account Team or visit the [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html){target="_blank"} page.

## Channel Summary {#channel-summary}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Channel</th> 
   <th>Membership Status</th>
   <th>Analytics Behavior</th>
   <th>Program Type</th>
  </tr> 
  <tr> 
   <td>Web Content</td> 
   <td>01-Member 
<br/>02-Engaged-Success</td>
   <td>Inclusive</td>
   <td>Default</td>
  </tr>
 </tbody> 
</table>

## Program Contains the Following Assets {#program-contains-the-following-assets}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Type</th> 
   <th>Template Name</th>
   <th>Asset Name</th>
  </tr> 
  <tr> 
   <td>Email</td> 
   <td>Quick Start Email Template</td>
   <td>01-Email-Thank You</td>
  </tr>
  <tr> 
   <td>Landing Page</td> 
   <td>Quick Start LP Template</td>
   <td>01 - LP - Registration</td>
  </tr>
  <tr> 
   <td>Landing Page</td> 
   <td>Quick Start LP Template</td>
   <td>02 - LP - Thank You</td>
  </tr>
  <tr> 
   <td>Form</td> 
   <td>&nbsp</td>
   <td>Content Registration Form</td>
  </tr>
  <tr> 
   <td>Local Report</td> 
   <td>&nbsp</td>
   <td>Email Performance</td>
  </tr>
  <tr> 
   <td>Local Report</td> 
   <td>&nbsp</td>
   <td>Landing Page Performance</td>
  </tr>
  <tr> 
   <td>Smart Campaign</td> 
   <td>&nbsp</td>
   <td>01-Filled-Out Form</td>
  </tr>
  <tr> 
   <td>Smart Campaign</td> 
   <td>&nbsp</td>
   <td>02-Engaged (Program Success)</td>
  </tr>
  <tr> 
   <td>Folder</td> 
   <td>&nbsp</td>
   <td>Assets - houses all creative assets 
<br/>(subfolders for Email & Landing Pages)  </td>
  </tr>
  <tr> 
   <td>Folder</td> 
   <td>&nbsp</td>
   <td>Campaigns - houses all Smart Campaigns</td>
  </tr>
  <tr> 
   <td>Folder</td> 
   <td>&nbsp</td>
   <td>Reports</td>
  </tr>
 </tbody> 
</table>

SCREENSHOT OF PROGRAM

## My Tokens Included {#my-tokens-included}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Token Type</th> 
   <th>Token Name</th>
   <th>Value</th>
  </tr> 
  <tr> 
   <td>Rich Text</td> 
   <td><code>{{my.Content-Description}}</code></td>
   <td>Double-Click for Details  
<br/><code><--My Content Description Here--></code> 
<br/>Edit this content description at the program level, under the My Tokens tab. 
<br/>You'll learn: 
<li>Bullet 1</li>
<li>Bullet 2</li>
<li>Bullet 3</li></td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Content-Title}}</code></td>
   <td><code><--My Content Title Here--></code></td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Content-Type}}</code></td>
   <td><code><--My Content Type Here--></code></td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Content-URL}}</code></td>
   <td>my.ContentURL?without=http://</td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Email-FromAddress}}</code></td>
   <td>PlaceholderFrom.email@mydomain.com</td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Email-FromName}}</code></td>
   <td><code><--My From Name Here--></code></td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Email-ReplyToAddress}}</code></td>
   <td>reply-to.email@mydomain.com</td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.PageURL-ThankYou}}</code></td>
   <td>My.ThankYouPageURL?without the http://</td>
  </tr>
 </tbody> 
</table>

## Conflict Rules {#conflict-rules}

* **Program Tags**
   * Create tags in this subscription - _Recommended_
   * Ignore

* **Landing Page template with the same name**
   * Copy original template
   * Use destination template - _Recommended_

* **Images with the same name**
   * Keep both files
   * Replace item in this subscription - _Recommended_

* **Email templates with the same name**
   * Keep both templates
   * Replace existing template - _Recommended_

SCREENSHOT OF CONFLICT RULES

## Best Practices {#best-practices}

* After import of the content program, move the form from a local asset to a global asset located in the Design Studio.
   * Decreasing the number of forms and utilizing more global assets from the Design Studio allows more scalability in your program design and administrative governance. It also provides flexibility in regular compliance updates for fields, opt-in language, etc. 

* Consider updating the templates in your imported program to utilize currently branded templates, or update the newly imported template to reflect your brand by adding in a snippet or your appropriate logo/footer information.

* Consider updating the naming convention of this program example to align with your naming convention.

>[!NOTE]
>
>Remember to update the My Token Values on the program template and each time you use the program, as needed.

>[!TIP]
>
>Don't forget to activate the "02-Engaged" Campaign for tracking success! Do this _before_ your form is live and emails are sent.

>[!IMPORTANT]
>
>My Tokens that reference a URL cannot contain the http:// or https:// otherwise the link will not work appropriately within the asset.
