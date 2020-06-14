---
unique-page-id: 10096679
description: Example ON24 Event Integration - Marketo Docs - Product Documentation
title: Example ON24 Event Integration
---

# Example ON24 Event Integration {#example-on-event-integration}

Example ON24 Event Integration - Marketo Docs - Product Documentation

Here's a sample event, including campaigns, for an ON24 webinar. When you build your event, be sure to test your campaigns before running them.

### What's in this article? {#what-s-in-this-article}

[Create a New Event in Marketing Activities](#exampleon24eventintegration-createaneweventinmarketingactivities)  
[Invite (Batch Campaign)](#exampleon24eventintegration-invite(batchcampaign))  
[Registration/Confirmation (Trigger Campaign)](#exampleon24eventintegration-registration/confirmation(triggercampaign))  
[Reminder (Batch Campaign)](#exampleon24eventintegration-reminder(batchcampaign))  
[Follow-Up Campaign (Batch or Trigger Campaign)](#exampleon24eventintegration-follow-upcampaign(batchortriggercampaign))

#### Create a New Event in Marketing Activities {#exampleon24eventintegration-createaneweventinmarketingactivities}

##### 1. Select New > New Program. {#exampleon24eventintegration-selectnew>newprogram.}

![](assets/image2015-12-22-15-3a35-3a15.png)

##### 2. Select a Campaign Folder where the event will live. {#exampleon24eventintegration-selectacampaignfolderwheretheeventwilllive.}

![](assets/image2015-12-22-15-3a39-3a51.png)

##### 3. Enter a Name for the event. {#exampleon24eventintegration-enteranamefortheevent.}

![](assets/image2015-12-22-15-3a43-3a4.png)

##### 4. Select Event as the Program Type. {#exampleon24eventintegration-selecteventastheprogramtype.}

![](assets/image2015-12-22-15-3a44-3a41.png)

##### 5. Select Webinar as the Channel for the event. {#exampleon24eventintegration-selectwebinarasthechannelfortheevent.}

![](assets/image2015-12-22-15-3a46-3a34.png)

##### 6. Click Create. {#exampleon24eventintegration-clickcreate.}

![](assets/image2015-12-22-15-3a48-3a20.png)

#### Invite (Batch Campaign)  {#exampleon24eventintegration-invite(batchcampaign)}

* **Smart List** – Define whom you will invite to the event.
* **Flow**

    * Send Email – If this is a local asset email, it will have the following naming convention: EventName.EmailName. You can also use global emails.
    * Change Status in Progression – Set to Webinar > Invited.

* **Schedule** – Set the date for the invitation to be sent.

#### Registration/Confirmation (Trigger Campaign) {#exampleon24eventintegration-registration/confirmation(triggercampaign)}

* **Smart List**

    * Trigger the campaign based on **Fills Out Form**. Be sure to include the landing page that the form lives on by using **Add Constraint**, especially if the form is used on multiple landing pages.

>[!CAUTION]
>
>You must use a Marketo form to register people for the event, or a non-Marketo form with the proper API integration to push registration data to Marketo. This is critical to the success of your Event Partner integration. **NOTE**: If you are using a Marketo form on a non-Marketo landing page, your trigger will be **Fills Out Form** with the Form Name.

![](assets/image2015-12-22-15-3a50-3a22.png)

* **Flow**

    * **Change Status in Progression** – Set to Webinar > Registered. **CAUTION**: This flow step is required when setting up your child campaign. When a person’s progression status changes to **Registered**, Marketo pushes the registration information to ON24. 
    
    * **Send Email** – Confirmation email (set to **Operational** so that unsubscribed people that have registered still receive it).

![](assets/image2015-12-22-15-3a52-3a9.png)

**NOTE**: If the person is returned with a registration error, they won't receive the email confirmation.

#### Reminder (Batch Campaign) {#exampleon24eventintegration-reminder(batchcampaign)}

* **Smart List** – Filter using **Member of Program** and set the status to **Registered**.

* **Flow** – Send Email (Reminder Email).

**NOTE**: You could use a similar campaign to send a *different* follow-up email to people who were invited but who haven't registered yet.

#### Follow-Up Campaign (Batch or Trigger Campaign) {#exampleon24eventintegration-follow-upcampaign(batchortriggercampaign)}

* **Smart List** – Trigger based on changes in program status.

![](assets/image2015-12-22-15-3a57-3a25.png)

* **Flow** - Send Email. Use choices to send different emails based on program status.

![](assets/ten.png)

>[!NOTE]
>
>**Related Articles**
>
>* [Understanding Marketo ON24 Adapter Events](understanding-marketo-on24-adapter-events.md)
>

