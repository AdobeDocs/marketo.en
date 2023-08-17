---
description: Content on Marketo LP - Marketo Docs - Product Documentation
title: Content on Marketo LP
hide: yes
hidefromtoc: yes
feature: Programs
---
# Content on Marketo LP {#content-on-marketo-lp}

Program Name: CT-YYYY-MM-Content on Marketo LP 

This sample reference is designed to be a content program that leverages a Marketo Landing Page with a Marketo form utilizing a Marketo Default Program. The form is to access the content/offer. The link to the offer can be displayed on the thank you page, sent in a thank you email, or both. For further strategy assistance or help customizing a program, please contact the Adobe Account Team, or [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html). 

**Channel Summary**

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

**Program contains the following assets:**

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
   <td>Assets - Houses all creative assets 
<br/>(sub folders for Email & Landing Pages)  </td>
  </tr>
  <tr> 
   <td>Folder</td> 
   <td>&nbsp</td>
   <td>Campaigns - Houses all Smart Campaigns</td>
  </tr>
  <tr> 
   <td>Folder</td> 
   <td>&nbsp</td>
   <td>Reports</td>
  </tr>
 </tbody> 
</table>

SCREENSHOT - Picture of program  

**My Tokens included:**

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
<br/><--My Content Description Here--> 
<br/>Edit this content description at the Program Level, under the My Tokens tab. 
<br/>You'll learn: 
<li>Bullet 1</li>
<li>Bullet 2</li>
<li>Bullet 3</li></td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Content-Title}}</code></td>
   <td><--My Content Title Here--></td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Content-Type}}</code></td>
   <td><--My Content Type Here--></td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Content-URL}}</code></td>
   <td>my.ContentURL?without=http://</td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Email-FromAddress}}</code></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.Email-FromName}}</code></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my. Email-ReplyToAddress}}</code></td>
   <td>3</td>
  </tr>
  <tr> 
   <td>Text</td> 
   <td><code>{{my.PageURL-ThankYou}}</code></td>
   <td>3</td>
  </tr>
 </tbody> 
</table>







PlaceholderFrom.email@mydomain.com



<--My From Name Here-->



reply-to.email@mydomain.com




My.ThankYouPageURL?without the http://

 

 

CAUTION ** See Program Import Instructions for Default Conflict Rules  

Recommended Default Conflict Rules for Import:  

 

Program Tags 

Create tags in this subscription  (Default) – Recommended  

Ignore  

 

Landing Page template with the same name 

Copy original template (Default) 

Use destination template – Recommended 

 

Images with the same name  

Keep both files (Default) 

Replace item in this subscription – Recommended 

 

Email templates with the same name  

Keep both templates (Default) 

Replace existing template - Recommended 

INSERT Picture of default conflict rules   

 

 

Recommended Best Practices:  

 

Marketo Consulting best practices recommend that post import of the content program, move the form from a local asset to a global asset located in the Design Studio of Marketo.  

Decreasing the number of forms and utilizing more global assets from the Design Studio allows more scalability in your program design and administrative governance. It also provides flexibility in regular compliance updates for fields, opt-in language, etc.  

 

Consider updating the templates in your imported program to utilize currently branded templates or update the newly imported template to reflect you brand by adding in a snippet or your appropriate logo and footer information.  

 

Consider updating the naming convention of this program template to align to your naming convention, if needed.  

 

NOTE: Don't forget to activate the "02-Engaged" Campaign for tracking success! Do this BEFORE your form is live and emails are sent. 

 

Don't forget to update the My Token Values on the program template and each time you use the program, as needed.  

 

REMEMBER: My Tokens that reference a URL cannot contain the http:// or https:// otherwise the link will not work appropriately within the asset.  

 

For further strategy assistance or help customizing a program, please contact your Account Team or visit Adobe Professional Services for more information.
