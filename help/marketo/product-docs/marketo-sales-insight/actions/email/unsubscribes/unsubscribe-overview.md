---
description: Unsubscribe Overview - Marketo Docs - Product Documentation
title: Unsubscribe Overview
hide: yes
hidefromtoc: yes
---
# Unsubscribe Overview {#unsubscribe-overview}

It's becoming increasingly important for organizations to be in compliance with email privacy laws. To help with this, we've made some enhancements to our unsubscribe experience.

* Unsubscribe links are placed on all emails sent from Marketo Sales and Salesforce (this does not apply to custom emails sent from Outlook or Gmail)
* Admins can edit unsubscribe messaging for their entire team
* Unsubscribe information is stored in PDV
* Unsubscribes can be done manually: Clicked Link, Salesforce Sync, and Bounce
* New unsubscribe link landing page

## Unsubscribe Link Landing Page {#unsubscribe-link-landing-page}

When a person clicks your unsubscribe link, they'll be taken to an unsubscribe landing page where they can select what they would like to be unsubscribed from and why.

![](assets/unsubscribe-overview-1.png)

This information will get saved to the person details view for viewing later.

## Unsubscribe Group {#unsubscribe-group}

See and manage all of your unsubscribed people in one place.

![](assets/unsubscribe-overview-2.png)

Use the search bar to look up any unsubscribed people.

![](assets/unsubscribe-overview-3.png)

If you're an Admin, you can go to the unsubscribe group to filter by Account Unsubscribes and see all of the unsubscribes that have been collected in your people database.

![](assets/unsubscribe-overview-4.png)

## Unsubscribe History Card {#unsubscribe-history-card}

The Unsubscribe History Card helps admins and users get contextual information about their contacts' unsubscribe history. Navigate there by going to the People tab and selecting a person. It's at the bottom of the About tab in the Person Details View.

>[!NOTE]
>
>There will only be an Unsubscribe History card if the person has _resubscribed_ at some point.

![](assets/unsubscribe-overview-5.png)

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Date</strong></td> 
   <td><p>Shows the date the unsubscribe/resubscribe took place.</p></td> 
  </tr> 
  <tr> 
   <td><strong>Details</strong></td> 
   <td><p>Resubscribe: A Sales Connect admin manually removed the unsubscribe from the contact record. It may also show some details related to why the contact was unsubscribed.</p><p>Unsubscribe: The contact was unsubscribed.</p></td> 
  </tr> 
  <tr> 
   <td><strong>Source</strong></td> 
   <td><p>Salesforce Sync: Unsubscribe was captured by a sync from Salesforce.</p><p>Manual: User clicked the unsubscribe button to opt out.</p><p>Clicked Link: Recipient of an email clicked the unsubscribe link.</p><p>“Admin Name”: An admin's name will show when the action was to resubscribe contacts. This lets users know who removed the unsubscribe.</p></td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>[Customize Unsubscribe Link Message](/help/marketo/product-docs/marketo-sales-insight/actions/email/unsubscribes/customize-unsubscribe-link-message.md)
