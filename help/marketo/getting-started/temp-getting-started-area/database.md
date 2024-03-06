---
description: Setting up the Database section for a new Marketo Engage instance.
title: NEW AREA DATABASE
hide: yes
hidefromtoc: yes
feature: Getting Started
---
# NEW AREA: Database Checklist {#new-area-database-checklist}

Learn how to implement the necessary steps for the Database section in your new Marketo Engage instance. Follow the "Implement a new instance" guides and keep track of tasks in progress to help you set your instance up for long-term efficiency.

## System Smart Lists {#system-smart-lists}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>All People</td>
    <td><li>Determine implementing a 1:1 sync with CRM or applying filters to limit who moves from system to system and when.</li> 
    <li>Review the total number of people and marketable people in your <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/database-dashboard.html" target="_blank" rel="noopener noreferrer">database</a>.</li></td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Blocklist</td>
    <td><li>Define blocklist criteria. Consider adding competitor's domains to <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.html" target="_blank" rel="noopener noreferrer">blocklist</a> to prevent them from receiving any marketing and operational emails.</li></td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Marketing Suspended</td>
    <td><li>Define <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe.html#marketing-suspended" target="_blank" rel="noopener noreferrer">Marketing Suspended</a> criteria.</li></td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Bounced Email Addresses </td>
    <td><li>Define your criteria for Bounced Email Addresses.</li>
    <li>Review the people in Email Invalid category and if their emails need be <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/hard-and-soft-bounces-in-email.html" target="_blank" rel="noopener noreferrer">reset manually</a>.</li></td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Possible Duplicates</td>
    <td><li>Review People in the Possible Duplicates list.</li> 
    <li>Define your duplicate management strategy to determine <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.html" target="_blank" rel="noopener noreferrer">merging people manually</a> or not.</li>  
    <li>If you have a CRM integration, you should define a process and account for <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.html#effect-in-salesforce" target="_blank" rel="noopener noreferrer">the effect of merging leads in CRM</a>.</li></td>
    <td>Text</td>
  </tr>
  <tr>
    <td>No Acquisition Program</td>
    <td><li>Establish campaigns in your program templates that set Acquisition Program, especially if using global forms.</li></td>
    <td>Text</td>
  </tr>
  <tr>
    <td>Unsubscribed People</td>
    <td><li>Review your criteria for <a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/email-marketing/deliverability/understanding-unsubscribe.html" target="_blank" rel="noopener noreferrer">Unsubscribed People</a>.</li></td>
    <td>Text</td>
  </tr>
</tbody>
</table>

## Group Smart Lists {#group-smart-lists}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Group Smart Lists</td>
    <td><li>Be aware of creating Group Smart Lists so that there aren't duplicate lists.</li>
    <li>Keep track of the master lists here in the database.</li></td>
    <td>Text</td>
  </tr>
</tbody>
</table>

## Segmentation {#segmentation}

<table>
<thead>
  <tr>
    <th>Area</th>
    <th>Action Items</th>
    <th>Priority</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Segmentation</td>
    <td><li><a href="https://experienceleague.adobe.com/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.html" target="_blank" rel="noopener noreferrer">Create segmentations</a> based on your business needs. Each subscription is limited to 20 segmentations and 100 segments within each segmentation.</li></td>
    <td>Text</td>
  </tr>
</tbody>
</table>
