---
unique-page-id: 2949874
description: "Create an Event with [!DNL GotoWebinar] - Marketo Docs - Product Documentation"
title: "Create an Event with [!DNL GotoWebinar]"
exl-id: c0f0a202-e416-4523-b7d6-dbcfafc536cd
---
# Create an Event with [!DNL GotoWebinar] {#create-an-event-with-gotowebinar}

>[!PREREQUISITES]
>
>* [Add [!DNL GoToWebinar] as a [!DNL LaunchPoint] service](/help/marketo/product-docs/administration/additional-integrations/add-gotowebinar-as-a-launchpoint-service.md)
>* [Create a New Event Program](/help/marketo/product-docs/demand-generation/events/understanding-events/create-a-new-event-program.md)
>* Set the appropriate [flow actions](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/add-a-flow-step-to-a-smart-campaign.md) to track engagement

First create your webinar in [!DNL GoToWebinar]. Certain settings in the creation of your [!DNL GoToWebinar] are used by Marketo and some are only used by [!DNL GoToWebinar].

After you create a Marketo event and associate the [!DNL GoToWebinar] with it, the systems will be able to share registration and attendance information.

Below is a list of the settings used by Marketo.

## Title and Description {#title-and-description}

**[!UICONTROL Title]** - enter the name for the webinar. This name will be viewable in Marketo.

**[!UICONTROL Description]** (optional) - enter the description for the webinar. The description will be viewable in Marketo.

![](assets/image2015-5-28-15-3a1-3a36.png)

## Date & Time {#date-time}

Enter the following information for your webinar and it will be pulled into Marketo via the adapter. If you make any changes to this information, you must click the link “**[!UICONTROL Refresh from Webinar Provider]**” under **[!UICONTROL Event Actions]**, in order for Marketo to see the changes.

**[!UICONTROL Start Date]** - enter your start date. This will be viewable in Marketo.

**[!UICONTROL Start Time]** - enter your start time. This will be viewable in Marketo.

**[!UICONTROL End Time]** - enter your end time. This will be viewable in Marketo.

**[!UICONTROL Webinar Time Zone]** - select the applicable time zone. It will be viewable in Marketo.

**[!UICONTROL Type]** - set to **[!UICONTROL One Session]**.

![](assets/image2015-5-28-15-3a7-3a1.png)

>[!NOTE]
>
>Marketo does not currently support recurring webinars. You must set up a single session between each Marketo Event and [!DNL GoToWebinar] webinar.

>[!TIP]
>
>If you need additional [!DNL GoToWebinar] help, please visit their [Help Site](https://support.logmeininc.com/gotowebinar).

Now, let's jump into Marketo!

1. Select an event. Click **[!UICONTROL Event Actions]** and choose **[!UICONTROL Event Settings]**.

   ![](assets/image2015-5-14-14-3a53-3a10.png)

   >[!NOTE]
   >
   >The channel type of the event selected must be **webinar**.

1. Choose **[!UICONTROL GoToWebinar]** from the **[!UICONTROL Event Partner]** List.

   ![](assets/image2015-5-14-14-3a55-3a20.png)

1. Choose the account.

   ![](assets/rtaimage-2.png)

1. Select the webinar.

   ![](assets/image2015-5-14-14-3a57-3a31.png)

1. Click **[!UICONTROL Save]**.

   ![](assets/image2015-5-14-14-3a58-3a54.png)

1. Excellent! Now the event is synced and scheduled by **[!DNL GoToWebinar]**.

   ![](assets/image2015-5-14-15-3a0-3a47.png)

   >[!NOTE]
   >
   >The fields Marketo sends over are: First Name, Last Name, Email Address. These fields are required and must not be empty.

   >[!TIP]
   >
   >To populate your confirmation email with this unique URL, use the following token in your email: `{{member.webinar url}}`. When the confirmation URL is sent out, this token automatically resolves to the person's unique confirmation URL.
   >
   >Set your confirmation email to **Operational** to ensure that people who register and may be unsubscribed still receive their confirmation information.

   ![](assets/goto-webinar.png)

   >[!CAUTION]
   >
   >Avoid using nested email programs to send out your confirmation emails. Use the event program's smart campaign instead, as shown above.

   >[!TIP]
   >
   >It can take up to 48 hours for the data to appear in Marketo. If after waiting that long you still don't see anything, select **[!UICONTROL Refresh from Webinar Provider]** from the [!UICONTROL Event Actions] menu in the **[!UICONTROL Summary]** tab of your event.

People who sign up for your webinar will get pushed to your webinar provider via the [!UICONTROL Change Program Status] flow step when the [!UICONTROL New Status] is set to "Registered." No other status will push the person over. Also, be sure to make [!UICONTROL Change Program Status] flow step #1, and [!UICONTROL Send Email] flow step #2.

## Viewing the Schedule  {#viewing-the-schedule}

In the program schedule view, click the calendar entry for your event. You can see the schedule on the right side of the screen.

>[!NOTE]
>
>To change your event schedule, you'll need to edit the webinar on [!DNL GoToWebinar].

![](assets/image2015-5-14-15-3a3-3a13.png)
