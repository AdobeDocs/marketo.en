---
description: Engagement Map Tab - Marketo Docs - Product Documentation
title: Engagement Map Tab
hide: yes
hidefromtoc: yes
exl-id: f54b9258-451b-4607-b5a9-f8627c6f420a
---
# Engagement Map Tab {#engagement-map-tab}

Engagement Map is represented through a series of trigger, filter, and flow cards. Clicking on each card will reveal additional information.

Trigger Overview: This card shows the number of triggers in your campaign. Clicking on it will reveal a card for each trigger, as well a slide-out panel with the following information:

* Campaign the trigger belongs to
* List of trigger names
* "Edit Trigger" button

   ![](assets/engagement-map-tab-1.png)

Trigger Detail: This card shows trigger name. Clicking on it will reveal a slide-out panel with the following information: 

* Campaign the trigger belongs to
* List of constraints associated with the trigger
* "Edit Trigger" button

   ![](assets/engagement-map-tab-2.png)

Filter: Clicking on this card will reveal a slide-out panel with the following information:

* Campaign the trigger belongs to
* Estimated number of people who qualify for the filter
* List of filters and their respective constraints
* "Edit Filter" button

   ![](assets/engagement-map-tab-3.png)

Flow steps: If a flow step includes choices, this card will show name of the flow step. Clicking on it will reveal a slide-out panel with the following information:

* Campaign the Flow step belongs to 
* List of choice conditions associated to the flow step
* "Edit Flow" button

   ![](assets/engagement-map-tab-4.png)

Flow steps: If a flow step does _not_ include any choices, this card will show attributes associated to the flow step. Clicking on it will reveal a slide-out panel with the following information:

* Campaign the Flow step belongs to
* List of attributes associated to the flow step
* "Edit Flow" button

   ![](assets/engagement-map-tab-5.png)

## Flow Step for Execute and Request Campaigns {#flow-step-for-execute-and-request-campaigns}

* If the Execute or Request Campaign flow step does not include any choices, the card will show the name of the campaign. Clicking on the card will reveal a slide-out panel with the following information:

   * Campaign the flow step belongs to 
   * "Edit Flow" button 
   * List of attributes associated to the flow step 
   * "View List" button, which opens a list of campaigns that use the specific Request/Execute Campaign

>[!NOTE]
>
>You can edit the flow step(s) from a primary campaign. To edit nested campaigns, you'll have to navigate to the campaign via the link in the slide-out panel.  

   ![](assets/engagement-map-tab-6.png)

   ![](assets/engagement-map-tab-7.png)

* If the Execute or Request Campaign flow step includes choices, the card will show the name of the campaign. Clicking on the card will reveal a slide-out panel with the following information: 

   * Campaign the flow step belongs to
   * List of choice conditions associated to the flow step
   * "Edit Flow" button

   ![](assets/engagement-map-tab-8.png)

   ![](assets/engagement-map-tab-9.png)

* If an Execute or Request Campaign includes choices, clicking on the flow card will expand to show all choices in individual cards. Clicking on the choice card will expand the campaign associated to the specific choice as well as reveal a slide-out panel with the following information:

   * Campaign the choice belongs to
   * "Edit Choice" button
   * List of choice conditions associated to the flow step
   * "View List" button, which opens a list of campaigns that use the specific Request/Execute Campaign

   ![](assets/engagement-map-tab-10.png)

## Visualizing a Nested Execute Campaign {#visualizing-a-nested-execute-campaign}

Execute campaigns run in series with the parent campaign. People that qualify for an executable campaign complete all flow steps from the campaign and return to the primary campaign to continue through the flow steps of this campaign.

Below is an example of a Smart Campaign, "Campaign A," which includes an execute campaign flow step. Think of "Campaign A" as your primary campaign. 

   ![](assets/engagement-map-tab-11.png)

1. Clicking on the execute campaign flow card will expand to show details of "Campaign B".
1. "Campaign B" includes a filter that splits the audience into two groups: qualified and not qualified.  
1. Qualified audience goes through the flow steps associated to "Campaign B."
1. All audience (qualified and not qualified) return to "Campaign A" and move on to the next flow step.

   ![](assets/engagement-map-tab-12.png)

You can click on the Execute Campaign flow step in "Campaign B" which will expand to show the choice cards and campaign associated with each choice.

   ![](assets/engagement-map-tab-13.png)

## Visualizing Request Campaign {#visualizing-request-campaign}

Request campaigns run in parallel with the parent campaign. People that qualify for a request campaign complete all the flow steps from the campaign and then exit the campaign. Concurrently, the same set of people go through the flow steps from the primary campaign. 

Here's an example of a Smart Campaign, "Campaign A," which includes a request campaign flow step. Think of "Campaign A" as your primary campaign.

   ![](assets/engagement-map-tab-14.png)

1. Clicking on the request campaign flow card will expand to show the details of "Campaign B" 
1. "Campaign B" includes a filter that splits the audience into two groups: qualified and not qualified.    
1. Qualified audience goes through the flow steps associated to "Campaign B."
1. At the same time, all audience moves to the next flow steps in "Campaign A." 

   ![](assets/engagement-map-tab-15.png)

You can dive deeper into your nested campaigns if any of the flow steps include another request campaign by clicking on the flow card to view the details of the campaign.

   ![](assets/engagement-map-tab-16.png)

Here's an example of a request campaign with choices.  

   ![](assets/engagement-map-tab-17.png)

## Error Handling {#error-handling}

Errors in Smart Lists and flow steps will be highlighted via an error icon in the card. Additionally, a corresponding error message will be reflected in the slide-out panel.

Below is an example of an error in a trigger which shows in the trigger overview card, slide-out panel, and the detail trigger card.

   ![](assets/engagement-map-tab-18.png)

   ![](assets/engagement-map-tab-19.png)

**Errors in filter cards can include:**

* An error in the Smart List which will result in qualified audience not being shown 

* An error in the filter logic 

* An error in constraints (or lack thereof) in one or more filters 

   ![](assets/engagement-map-tab-20.png)

Not entering values (attributes) will not result in an error, it will continue to work as it does in Flow tab. Therefore, existing campaigns will not be disrupted. However, when flow steps do not include any attributes these will show up as warnings. 

^^^ DO WE REALLY NEED THIS, WON'T CUSTOMER SEE WARNING???

   ![](assets/engagement-map-tab-21.png)

>[!NOTE]
>
>Errors within a nested campaign won't be visible until you've clicked to expand the nested campaign.
