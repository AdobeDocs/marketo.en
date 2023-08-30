---
description: NUR-YYYY-MM-Advanced Nurture - Marketo Docs - Product Documentation
title: NUR-YYYY-MM-Advanced Nurture
hide: yes
hidefromtoc: yes
feature: Programs
---
# NUR-YYYY-MM-Advanced Nurture {#nur-yyyy-mm-advanced-nurture}

This is an example of advanced Nurture Programs utilizing the Marketo Engage Engagement Program. Nested Email Programs prevent people from receiving content they have already consumed, or control the type of content they should consume in each stream. Attribution reporting can be run for each individual Nested Email Program. Channels: "Nurture", and a dedicated "Nurture Email" channel for the Nested Email Programs sends one newsletter email utilizing a Marketo Engage Email Program. The email can include or not include an A/B test.

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
   <td>Nurture</td> 
   <td>01 - Member 
<br/>02 - Engaged - Success</td>
   <td>Inclusive</td>
   <td>Engagement</td>
  </tr>
  <tr> 
   <td>Nurture Email</td> 
   <td>01 - Skip 
<br/>02 - Sent
<br/>03 - Engaged - Success</td>
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
   <td>Nested Program</td> 
   <td>&nbsp</td>
   <td>01 - Topic X</td>
  </tr>
  <tr> 
   <td>Nested Program</td> 
   <td>&nbsp</td>
   <td>02 - Topic Y</td>
  </tr>
  <tr> 
   <td>Nested Program</td> 
   <td>&nbsp</td>
   <td>03 - Topic Z</td>
  </tr>
  <tr> 
   <td>Email</td> 
   <td>Quick Start Email Template</td>
   <td>01 - Email (Live in Nested Programs)</td>
  </tr>
   <tr> 
   <td>Email</td> 
   <td>Quick Start Email Template</td>
   <td>02 - Email (Live in Nested Programs)</td>
  </tr>
   <tr> 
   <td>Email</td> 
   <td>Quick Start Email Template</td>
   <td>03 - Email (Live in Nested Programs)</td>
  </tr>
  <tr> 
   <td>Local Report</td> 
   <td>&nbsp</td>
   <td>Email Performance</td>
  </tr>
  <tr> 
   <td>Local Report</td> 
   <td>&nbsp</td>
   <td>Email Link Performance</td>
  </tr>
  <tr>
  <tr> 
   <td>Smart Campaign</td> 
   <td>&nbsp</td>
   <td>01 - Add to Nurture</td>
  </tr>
  <tr> 
   <td>Smart Campaign</td> 
   <td>&nbsp</td>
   <td>02 - Pause Nurture</td>
  </tr>
  <tr> 
   <td>Smart Campaign</td> 
   <td>&nbsp</td>
   <td>03 - Resume Nurture</td>
  </tr>
  <tr> 
   <td>Smart Campaign</td> 
   <td>&nbsp</td>
   <td>04 - Engaged (Program Success)</td>
  </tr>
  <tr> 
   <td>Smart Campaign</td> 
   <td>&nbsp</td>
   <td>00 - Skip Email (Located in each Nested Program)</td>
  </tr>
  <tr> 
   <td>Smart Campaign</td> 
   <td>&nbsp</td>
   <td>01 - Send Email (Located in each Nested Program)</td>
  </tr>
  <tr> 
   <td>Smart Campaign</td> 
   <td>&nbsp</td>
   <td>02 - Engaged-Success (Located in each Nested Program)</td>
  </tr>
  <tr> 
   <td>Folder</td> 
   <td>&nbsp</td>
   <td>Assets (Contain Nested Programs and Asset folders also live in Nested Programs to contain emails)</td>
  </tr>
  <tr> 
   <td>Folder</td> 
   <td>&nbsp</td>
   <td>Nested Programs (Lives under Assets Folder)</td>
  </tr>
  <tr> 
   <td>Folder</td> 
   <td>&nbsp</td>
   <td>Campaigns - Houses all Smart Campaigns in parent Nurture program and campaign folders are also located in each Nested Program</td>
  </tr>
  <tr> 
   <td>Folder</td> 
   <td>&nbsp</td>
   <td>Reports</td>
  </tr>
 </tbody> 
</table>

## My Tokens Included {#my-tokens-included}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Token Type</th> 
   <th>Token Name</th>
   <th>Value</th>
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
 </tbody> 
</table>

SCREENSHOT OF PROGRAM

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

* Consider updating the templates in your imported program to utilize currently branded templates, or update the newly imported template to reflect your brand by adding in a snippet or your appropriate logo/footer information.

* Consider updating the naming convention of this program example to align with your naming convention.

* Ensure you have rules in place to pause and resume your nurture cadence. These Smart Campaigns should be activated or scheduled before the Engagement Program is activated.  

>[!NOTE]
>
>Remember to update the My Token Values on the program template and each time you use the program, as needed.

>[!TIP]
>
>Don't forget to activate the "04 - Engaged (Program Success)" campaign for tracking success! Do this _before_ your emails are sent.
