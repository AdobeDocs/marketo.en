---
description: On-Demand Webinars - Marketo Docs - Product Documentation
title: On-Demand Webinars
hide: yes
hidefromtoc: yes
feature: Interactive Webinars
---
# On-Demand Webinars {#on-demand-webinars}

On-Demand Webinars capture and refine the leads that registered for your event and didn't attend, but want to obtain information related to the event by watching the recording. Such information as Name, Email ID, and Watch Date/Duration can be captured in Marketo Engage and used to target these no-show leads. 

The Webinar Joining URL that was shared with the registrants prior to the event can be used as a link to watch the on-demand recording. Once a registrant, who did not attend the live event i.e. a lead with a program status as "No-Show", clicks on the Webinar Joining URL, the program status of such a lead changes from "No-Show" to "Attended On-Demand". Note that the program status of the leads who have watched the event live and have the status "Attended" would not be impacted even if they visit the Joining URL and watch the on-demand recording.

Adobe Connect, the technology that powers Interactive Webinars, tracks the visit as well as the watch duration of the leads that have watched the recording and reports the same on a daily basis to Marketo. The recording is available at the Joining URL for a duration of 30 days post the event and the duration is fixed.

Marketo provides the watch statistics for On-Demand Webinars on the Dashboard tab with the help of the following two widgets:
1.    On-Demand Summary: This provides a day-wise summary of the count of visitors (No-Shows) that have watched the recording post the event.
2.    On-Demand Statistics: These widgets provide information on:
a.    Days that the On-Demand recording is available for viewing. This can help marketers take actions such as executing email campaigns closer to the end of the recording availability duration of 30 days.
b.    Overall visitor count for On-Demand webinars till date. This would be the count of all the No-Show registrants that have watched the on-demand recording till date.
c.    Average watch duration in minutes for all the visitors. This would give the marketer a sense of how much of the recording is viewed and what smart campaigns can be used to target leads above a certain watch duration.
  
SCREENSHOT

The filters and triggers for Interactive Webinars have been modified to cater to On-Demand Webinars. The trigger "Attends Event" and filter "Has attended event" is added with an additional constraint "Event Mode" where a marketer can choose whether the target is Live audience or On-Demand audience. If the "Event Mode" constraint is not selected then both the Live and On-Demand audiences would be targeted. Other constraints such as "Watch Date" and "Watch Duration" could be used with the "On-Demand" event mode. Inactivity Filter "Has not attended an event" can also be used for On-Demand webinars with "On-Demand" event mode.
