---
unique-page-id: 10096683
description: ON24 Event Registration Updates - Marketo Docs - Product Documentation
title: ON24 Event Registration Updates
---

# ON24 Event Registration Updates {#on-event-registration-updates}

ON24 Event Registration Updates - Marketo Docs - Product Documentation

### What's in this article? {#whats-in-this-article}

[Manually Approving Registrants](#manually-approving-registrants)  
[Handling People with a Registration Error](#handling-people-with-a-registration-error)  
[Updating Member Status from ON24](#updating-member-status-from-on)

#### Manually Approving Registrants {#manually-approving-registrants}

You can manually approve your registrants before sending them a confirmation email. To do so, you will need to configure your campaigns to handle this additional step:

1. For the Registration Trigger Campaign:

    * In the Smart List, set the trigger to **Fills Out Form**.
    * In the Flow, set the Status in Progression to **Pending Approval**.

1. Go to the Event and click the **Members** tab. This tab displays all the people who have filled out the form. Their status should be set to **Pending Approval**.
1. Use the filter at the top of the grid to view only the people with a status of **Pending Approval**.
1. Select the people that you wish to register (Shift-click, Control-click, or Select All).
1. From the menu, click **Change Status**. Select **Registered**, **Rejected**, or any other applicable status.

#### Handling People with a Registration Error {#handling-people-with-a-registration-error}

If a person ends up not being registered but rather set to the status Registration Error, it's not too late to recover.

1. From the Members tab, filter the list of people with the status **Registration Error**. 
1. Before continuing, make sure you have determined and fixed the issue with integration (check to make sure there are no errors under **Event Partners** in Admin). 
1. After the issue is resolved, select all the people with the Registration Error status and change their status to **Registered**. This will attempt to register them again with ON24.

#### Updating Member Status from ON24 {#updating-member-status-from-on}

Marketo automatically pulls in the attendance information at approximately 11pm Pacific each night. To manually update attendance information, click **Refresh from Webinar Provider** under **Event Actions**.

>[!NOTE]
>
>**Related Articles**
>
>* [Understanding Marketo ON24 Adapter Events](understanding-marketo-on24-adapter-events.md)
>

