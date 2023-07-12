---
description: Engagement Canvas Tab - Marketo Docs - Product Documentation
title: Engagement Canvas Tab
hide: yes
hidefromtoc: yes
exl-id: f54b9258-451b-4607-b5a9-f8627c6f420a
---
# Engagement Canvas Tab {#engagement-canvas-tab}

Engagement Canvas is represented through a series of trigger, filter, and flow cards. Clicking on each card will reveal additional information.

Trigger Overview: This card shows the number of triggers in your campaign. Clicking on it will reveal a card for each trigger, as well a slide-out panel with the following information:

* Campaign the trigger belongs to
* List of trigger names
* "Edit Trigger" button

SCREENSHOT

Trigger Detail: This card shows trigger name. Clicking on it will reveal a slide-out panel with the following information: 

* Campaign the trigger belongs to
* List of constraints associated with the trigger
* "Edit Trigger" button

SCREENSHOT

Filter: Clicking on this card will reveal a slide-out panel with the following information:

* Campaign the trigger belongs to
* Estimated number of people who qualify for the filter
* List of filters and their respective constraints
* "Edit Filter" button

SCREENSHOT

Flow steps: If a flow step includes choices, this card will show name of the flow step. Clicking on it will reveal a slide-out panel with the following information:

* Campaign the Flow step belongs to 
* List of choice conditions associated to the flow step
* "Edit Flow" button

SCREENSHOT

Flow steps: If a flow step does _not_ include any choices, this card will show attributes associated to the flow step. Clicking on it will reveal a slide-out panel with the following information:

* Campaign the Flow step belongs to
* List of attributes associated to the flow step
* "Edit Flow" button

SCREENSHOT

## Flow Step for Execute and Request Campaigns {#flow-step-for-execute-and-request-campaigns}

* If the Execute or Request Campaign flow step does not include any choices, the card will show the name of the campaign. Clicking on the card will reveal a slide-out panel with the following information:

   * Campaign the flow step belongs to 
   * "Edit Flow" button 
   * List of attributes associated to the flow step 
   * "View List" button, which opens a list of campaigns that use the specific Request/Execute Campaign

>[!NOTE]
>
>You can edit the flow step(s) from a primary campaign. To edit nested campaigns, you'll have to navigate to the campaign via the link in the slide-out panel.  

SCREENSHOT

SCREENSHOT

* If the Execute or Request Campaign flow step includes choices, the card will show the name of the campaign. Clicking on the card will reveal a slide-out panel with the following information: 

   * Campaign the flow step belongs to
   * List of choice conditions associated to the flow step
   * "Edit Flow" button

SCREENSHOT

SCREENSHOT

* If an Execute or Request Campaign includes choices, clicking on the flow card will expand to show all choices in individual cards. Clicking on the choice card will expand the campaign associated to the specific choice as well as reveal a slide-out panel with the following information:

   * Campaign the choice belongs to
   * "Edit Choice" button
   * List of choice conditions associated to the flow step
   * "View List" button, which opens a list of campaigns that use the specific Request/Execute Campaign

SCREENSHOT

## Visualizing a Nested Execute Campaign {#visualizing-a-nested-execute-campaign}

STOPPED EDITING HERE - PICK UP AFTER SHUTDOWN

Execute campaigns run in series with the parent campaign i.e leads that qualify for an executable campaign complete all flow steps from the campaign and return to the primary campaign to continue through flow steps of this campaign.  

Here's an example of a smart campaign "Campaign A" which includes a execute campaign flow step. You can think of "Campaign A" to be your primary campaign. 

SCREENSHOT

1. Clicking on the execute campaign flow card will expand to show details of "Campaign B".
1. Campaign B includes filter which branches out in not qualified and qualified audience.  
1. Qualified audience goes through flow steps associated to "Campaign B".
1. All audience (qualified and not qualified) return to "Campaign A" and move to the next flow step.

SCREENSHOT

You can click on Execute Campaign flow step in "Campaign B" which will expand to show choice cards and campaign associated with each choice. 

SCREENSHOT

## Visualizing Request Campaign {#visualizing-request-campaign}

Request campaigns run in parallel with the parent campaign i.e leads that qualify for a request campaign complete all flow steps from the campaign and exit the campaign. In parallel, the same set of leads will also go through flow steps from the primary campaign 

Here's an example of a smart campaign "Campaign A" which includes a request campaign flow step. You can think of "Campaign A" to be your primary campaign.

SCREENSHOT

1. Clicking on the request campaign flow card will expand to show details of "Campaign B" 
1. Campaign B includes filter which branches out in to qualified audience.  
1. Qualified audience goes through flow steps associated to "Campaign B" 
1. In parallel, all audience move to the next flow steps in "Campaign A" 

SCREENSHOT

You can dive deeper into nested campaigns, if any of the flow steps includes yet another request campaign by clicking on the flow card to view details of the campaign 

SCREENSHOT

Here's an example of request campaign with choices.  

SCREENSHOT

## Error Handling {#error-handling}

Errors in smart list and flow steps will be highlighted via error icon in the card. Additionally, corresponding error message will be reflected in the slide out panel.

Here's an example of error in trigger which will be indicated in the trigger overview card, slide out panel as well as detail trigger card

SCREENSHOT

SCREENSHOT

Error in filter card can include 

Error in smart list which will result in qualified audience not being shown 

Error in filter logic 

Error in constraints or lack thereof in one or more filters 

SCREENSHOT

Not entering values (attributes) will not be flagged as errors, it will continue to work as it does in Flow tab. Therefore, existing campaigns will not be disrupted. However, when flow steps do not include any attributes these will show up as warnings. 

SCREENSHOT

Note: Errors within a nested campaign will not be visible until you have clicked to expand the nested campaign