---
unique-page-id: 13795727
description: Abort Delivery of Email Programs Scheduled with Recipient Time Zone - Marketo Docs - Product Documentation
title: Abort Delivery of Email Programs Scheduled with Recipient Time Zone
---

# Abort Delivery of Email Programs Scheduled with Recipient Time Zone {#abort-delivery-of-email-programs-scheduled-with-recipient-time-zone}

Abort Delivery of Email Programs Scheduled with Recipient Time Zone - Marketo Docs - Product Documentation

In emergency cases, you can abort the delivery of an email program that has already started running with Recipient Time Zone enabled.

Since email programs scheduled with Recipient Time Zone can run for up to 24 hours, aborting the delivery of the program will cancel any subsequent sends after that point.

##### 1. Select the email program you want to cancel, then click Abort Delivery under the Approval tile in the control panel. {#abortdeliveryofemailprogramsscheduledwithrecipienttimezone-selecttheemailprogramyouwanttocancel-thenclickabortdeliveryundertheapprovaltileinthecontrolpanel.}

![](assets/ptz-abortdelivery.png)

##### 2. Confirm that you want to cancel the delivery by clicking Abort. {#abortdeliveryofemailprogramsscheduledwithrecipienttimezone-confirmthatyouwanttocancelthedeliverybyclickingabort.}

![](assets/image2018-2-23-11-3a20-3a27.png)

##### 3. After cancellation, the Results grid of your email program will look something like the one below. Any subsequent sends are canceled and will show up as "Email Bounced Soft" in the Activity Type column. {#abortdeliveryofemailprogramsscheduledwithrecipienttimezone-aftercancellation-theresultsgridofyouremailprogramwilllooksomethingliketheonebelow.anysubsequentsendsarecanceledandwillshowupas"emailbouncedsoft"intheactivitytypecolumn.}

![](assets/image2018-2-23-11-3a22-3a11.png)

>[!NOTE]
>
>Canceled emails will **not** show up as a soft bounce *until* the time they were originally scheduled to be delivered in their respective time zones. Up until that point, they will still display as "Send Email."

##### 4. From the grid, you can click any email to view activity details. For a canceled send, the details pop-up will look like this: {#abortdeliveryofemailprogramsscheduledwithrecipienttimezone-fromthegrid-youcanclickanyemailtoviewactivitydetails.foracanceledsend-thedetailspop-upwilllooklikethis-}

![](assets/image2018-2-23-11-3a30-3a46.png)

>[!NOTE]
>
>**Related Articles**
>
>* [Understanding Recipient Time Zone](understanding-recipient-time-zone.md)
>* [Schedule Email Programs with Recipient Time Zone](schedule-email-programs-with-recipient-time-zone.md)
>

