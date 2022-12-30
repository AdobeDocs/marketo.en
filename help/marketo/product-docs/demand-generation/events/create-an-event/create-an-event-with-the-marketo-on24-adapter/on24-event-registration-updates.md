---
unique-page-id: 10096683
description: ON24 Event Registration Updates - Marketo Docs - Product Documentation
title: ON24 Event Registration Updates
exl-id: 1d194ef2-b6ca-4e2d-b476-beb5bccd3c5f
---
# ON24 Event Registration Updates {#on-event-registration-updates}

## Manually Approving Registrants {#manually-approving-registrants}

You can manually approve your registrants before sending them a confirmation email. To do so, you will need to configure your campaigns to handle this additional step:

1. For the Registration Trigger Campaign:

    * In the [!UICONTROL Smart List], set the trigger to **[!UICONTROL Fills Out Form]**.
    * In the Flow, set the [!UICONTROL Status in Progression] to **[!UICONTROL Pending Approval]**.

1. Go to the Event and click the **[!UICONTROL Members]** tab. This tab displays all the people who have filled out the form. Their status should be set to **[!UICONTROL Pending Approval]**.
1. Use the filter at the top of the grid to view only the people with a status of **[!UICONTROL Pending Approval]**.
1. Select the people that you wish to register (Shift-click, Control-click, or Select All).
1. From the menu, click **[!UICONTROL Change Status]**. Select **[!UICONTROL Registered]**, **[!UICONTROL Rejected]**, or any other applicable status.

## Handling People with a Registration Error {#handling-people-with-a-registration-error}

If a person ends up not being registered but rather set to the status [!UICONTROL Registration Error], it's not too late to recover.

1. From the [!UICONTROL Members] tab, filter the list of people with the status **[!UICONTROL Registration Error]**.
1. Before continuing, make sure you have determined and fixed the issue with integration (check to make sure there are no errors under **[!UICONTROL Event Partners]** in Admin).
1. After the issue is resolved, select all the people with the [!UICONTROL Registration Error] status and change their status to **[!UICONTROL Registered]**. This will attempt to register them again with ON24.

## Updating Member Status from ON24 {#updating-member-status-from-on}

Marketo automatically pulls in the attendance information at approximately 11pm Pacific each night. To manually update attendance information, click **[!UICONTROL Refresh from Webinar Provider]** under **[!UICONTROL Event Actions]**.

>[!MORELIKETHIS]
>
>[Understanding Marketo ON24 Adapter Events](/help/marketo/product-docs/demand-generation/events/create-an-event/create-an-event-with-the-marketo-on24-adapter/understanding-marketo-on24-adapter-events.md){target="_blank"}
