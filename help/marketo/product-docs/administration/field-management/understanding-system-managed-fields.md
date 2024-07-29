---
unique-page-id: 5472615
description: Understanding System Managed Fields - Marketo Docs - Product Documentation
title: Understanding System Managed Fields
exl-id: 4a58d41f-c2f5-4bcc-93ef-10a31e5475fd
feature: Field Management
---
# Understanding System Managed Fields {#understanding-system-managed-fields}

You might have noticed that the [person detail page](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md){target="_blank"} has a series of non-editable fields created by Marketo. This data comes from various sources, and there are countless values that could display.

## Field Types {#field-types}

<table><thead>
  <tr>
    <th>Field Name</th>
    <th>Definition</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Original Source Type</td>
    <td>The location a person or website visitor was first discovered (Example: List Import, Web Page Visit)</td>
  </tr>
  <tr>
    <td>Original Source Info</td>
    <td>Specifics about that location (Example: Name of the list, URL of the web page)</td>
  </tr>
  <tr>
    <td>Original Search Engine</td>
    <td>If applicable, the search engine that referred the person to the original entry source</td>
  </tr>
  <tr>
    <td>Original Search Phrase</td>
    <td>If applicable, the search term used that referred the person to the original entry source</td>
  </tr>
  <tr>
    <td>Original Referrer</td>
    <td>URL that hosted the original entry source</td>
  </tr>
  <tr>
    <td>Registration Source Type</td>
    <td>The location an activity first became a person (Example: List Import, Web Page Visit)</td>
  </tr>
  <tr>
    <td>Registration Source Info</td>
    <td>Specifics about that location (Example: Name of the list, URL of the web page)</td>
  </tr>
  <tr>
    <td>Anonymous IP</td>
    <td>Indicates the IP address of a person</td>
  </tr>
  <tr>
    <td>Inferred Company</td>
    <td>Marketo's best guess (based on IP) of the person's company</td>
  </tr>
  <tr>
    <td>Inferred City</td>
    <td>Marketo's best guess (based on IP) of the person's city</td>
  </tr>
  <tr>
    <td>Inferred State Region</td>
    <td>Marketo's best guess (based on IP) of the person's state or region</td>
  </tr>
  <tr>
    <td>Inferred Postal Code</td>
    <td>Marketo's best guess (based on IP) of the person's postal code</td>
  </tr>
  <tr>
    <td>Inferred Country</td>
    <td>Marketo's best guess (based on IP) of the person's country</td>
  </tr>
  <tr>
    <td>Inferred Metropolitan Area</td>
    <td>Marketo's best guess (based on IP) of the person's metropolitan area</td>
  </tr>
  <tr>
    <td>Inferred Phone Area Code</td>
    <td>Marketo's best guess (based on IP) of the person's area code</td>
  </tr>
</tbody></table>

## Possible Values for Original and Registration Source Type {#possible-values-for-original-and-registration-source-type}

Below are some possible values and what they mean. 

<table><thead>
  <tr>
    <th>Original Source Type</th>
    <th>Definition</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Salesforce.com</td>
    <td>Person was discovered from the Salesforce sync</td>
  </tr>
  <tr>
    <td>Web Page Visits</td>
    <td>Person was discovered from a web page</td>
  </tr>
  <tr>
    <td>Web Form Fillout</td>
    <td>Person was discovered after filling out a form</td>
  </tr>
  <tr>
    <td>List Import</td>
    <td>Person was discovered from a list import</td>
  </tr>
  <tr>
    <td>New Person</td>
    <td>Person was manually entered into the database</td>
  </tr>
  <tr>
    <td>Web Link Click</td>
    <td>Person was discovered after clicking on a link</td>
  </tr>
  <tr>
    <td>Sales Email</td>
    <td>Person was sent an email via Sales Insight Email Add-In</td>
  </tr>
  <tr>
    <td>Person</td>
    <td>Person was synced over from Salesforce as a person</td>
  </tr>
  <tr>
    <td>Contact</td>
    <td>Person was synced over from Webhook as a contact</td>
  </tr>
  <tr>
    <td>Munchkin API</td>
    <td>Person was discovered by the Marketo Engage Munchkin API</td>
  </tr>
  <tr>
    <td>Social App</td>
    <td>Person was discovered by a social widget</td>
  </tr>
  <tr>
    <td>Web Service API</td>
    <td>Person was discovered by a web service API</td>
  </tr>
  <tr>
    <td>Event Partner</td>
    <td>Person was discovered through a synced webinar service</td>
  </tr>
  <tr>
    <td>Associate Lead</td>
    <td>Person that was merged via Associate Lead API call</td>
  </tr>
</tbody></table>

<table><thead>
  <tr>
    <th>Registration Source Type</th>
    <th>Definition</th>
  </tr></thead>
<tbody>
  <tr>
    <td>List Import</td>
    <td>Became a person through a list import</td>
  </tr>
  <tr>
    <td>Salesforce.com</td>
    <td>Became a person through Salesforce sync</td>
  </tr>
  <tr>
    <td>Web Form Fillout</td>
    <td>Became a person after filling out a form</td>
  </tr>
  <tr>
    <td>Sales Email</td>
    <td>Person was sent an email via Sales Insight Email Add-In</td>
  </tr>
  <tr>
    <td>Web Service API</td>
    <td>Person was created via SOAP/REST API</td>
  </tr>
  <tr>
    <td>New Person</td>
    <td>Person was manually entered into the database</td>
  </tr>
  <tr>
    <td>Munchkin API</td>
    <td>Became a person through Marketo's Munchkin API</td>
  </tr>
  <tr>
    <td>Social App</td>
    <td>Became a person through a social widget</td>
  </tr>
  <tr>
    <td>Event Partner</td>
    <td>Became a person through a linked webinar service</td>
  </tr>
</tbody>
</table>
