---
description: Inherited Instance Database Checklist - Marketo Docs - Product Documentation
title: Inherited Instance Database Checklist
hide: yes
hidefromtoc: yes
---
# Inherited Instance: Database Checklist {#inherited-instance-database-checklist}

Understand the total number of people, marketable people, and top person-acquiring sources in your subscription.

## System Smart Lists {#system-smart-lists}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>All People</td> 
   <td><li>How many people exist in the <a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/database-dashboard.md" target="_blank">database</a>?</li>
<li>If your database is close to full, does your company policy recommend that you expand your database size or clean out historical data?</li>
<li>Is your overall database at least 85% marketable? 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If yours falls under this threshold, look at the other system smart lists (Blocklist, Marketing Suspended, Duplicates, Unsubscribe) with greater scrutiny.</li></td>
  </tr>
  <tr> 
   <td>Unsubscribed People</td> 
   <td><li>What are your criteria for <a href="/help/marketo/product-docs/email-marketing/deliverability/understanding-unsubscribe.md#marketing-suspended" target="_blank">unsubscribed people</a>? Are there too many unsubscribed people?</li>
<li>Do your unsubscribe methods align with your data privacy requirements?</li>
<li>Is your unsubscribe preference up to date? How long have records remained in your database as unmarketable?</li></td>
  </tr>
  <tr> 
   <td>Marketing Suspended</td> 
   <td><li>What are your criteria for <a href="/help/marketo/product-docs/email-marketing/deliverability/durable-unsubscribe.md#marketing-suspended" target="_blank">Marketing Suspended</a>? Are there too many people who are Marketing Suspended?</li>
<li>How long have records remained in the Marketing Suspended status?</li>
<p>Marketing Suspended use case example: people records who are actively involved with sales in late-stage opportunities that you want to suppress marketing communications for.</td>
  </tr>
   <tr> 
   <td>Blocklist</td> 
   <td><li>What are your criteria for <a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/add-person-to-blocklist.md" target="_blank">blocklisting records</a>? Are there too many people who are blocklisted?</li></td>
  </tr>
  <tr> 
   <td>Bounced Email Addresses</td> 
   <td><li>Do you have a lot of <a href="/help/marketo/product-docs/email-marketing/deliverability/hard-and-soft-bounces-in-email.md" target="_blank">people who bounced</a> in your Database?
   <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If so, consider investigating why.</li></td></li></td>
  </tr>
  <tr> 
   <td>Possible Duplicates</td> 
   <td><li>How many <a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/find-and-merge-duplicate-people.md" target="_blank">potentially duplicate records</a> are there?
   <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Consider deleting or merging them.</li></td>
  </tr>
   <tr> 
   <td>No Acquisition Program</td> 
   <td><li>How many people don't have an <a href="/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md#acquisition-program" target="_blank">acquisition program</a>?
   <br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If there are a lot, consider investigating why.</li></td>
  </tr>
 </tbody> 
</table>

## Smart Lists {#smart-lists}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Smart Lists</td> 
   <td><li>How many <a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/understanding-smart-lists.md" target="_blank">Smart Lists</a> are there? How are they used in this instance?</li>
<li>Are the lists organized in a cohesive folder structure? 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If you have orphan lists, consider organizing your tree so assets are easy to find.</li>
<p><img src="assets/tip-icon.png" alt="tip icon">TIP: <a href="/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-folders.md#archive-a-folder" target="_blank">Archiving</a> Smart Lists that are no longer needed will help with organization and performance.</td>
  </tr>
 </tbody> 
</table>

## Static Lists {#static-lists}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Static Lists</td> 
   <td><li>How many <a href="/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/static-lists/understanding-static-lists.md" target="_blank">Static Lists</a> are there? How are they used in this instance?</li></td>
  </tr>
 </tbody> 
</table>

## Segmentations {#segmentations}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th style="width:20%">Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Segmentations</td> 
   <td><li>Which <a href="/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md" target="_blank">segmentations</a> are there? How are they being used?</li>
<li>Are too many people in <a href="/help/marketo/product-docs/personalization/segmentation-and-snippets/segmentation/segmentation-order-priority.md" target="_blank">default segments</a>?</li>
<li>Is there a segmentation for the marketable audience? 
<br/>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;If not, consider creating one.</li></td>
  </tr>
 </tbody> 
</table>

<br>&nbsp;

[◄ Audit an Inherited Instance: Admin](/help/marketo/getting-started/inheriting-a-marketo-instance/admin-section-checklist.md)

[Audit an Inherited Instance: Marketing Activities ►](/help/marketo/getting-started/inheriting-a-marketo-instance/marketing-activities-checklist.md)
