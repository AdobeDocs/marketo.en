---
description: Name Tab - Marketo Docs - Product Documentation
title: Name Tab
hide: yes
hidefromtoc: yes
---
# Name Tab {#name-tab}

Journeys is represented through a series of trigger, filter, and flow cards. Clicking on each of these cards will open corresponding slide out panel.

Trigger Overview: The card shows number of triggers in the specific campaign. Clicking on this card will also expand to show Trigger detail cards and simultaneously open slide out panel with the following information: 

Campaign that the trigger belongs to 

Edit Trigger button to access smart list tab 

List of trigger names 

SCREENSHOT

Trigger Detail: The card shows trigger name. Clicking on this card will open slide out panel with the following information: 

Campaign that the trigger belongs to 

Edit Trigger button to access smart list tab 

List of constraints associated with the trigger 

SCREENSHOT

Filters: Clicking on this card will open slide out panel with the following information: 

Campaign that the trigger belongs to 

Edit Filter button to access smart list tab 

Estimated number of people who qualify for the filter 

List of filters and their respective constraints 

SCREENSHOT

Flow steps: If a flow step does not include any choices, the card will show attributes associated to the flow step. Clicking on the card will open slide out panel with the following information: 

Campaign that the Flow step belongs to 

Edit Flow button to access Flow tab 

List of attributes associated to the flow step 

SCREENSHOT

Flow steps: If a flow step includes choices, the card will show name of the flow step. Clicking on the card will open slide out panel with the following information: 

Campaign that the Flow step belongs to 

Edit Flow button to access Flow tab 

List of choice conditions associated to the flow step

SCREENSHOT

Flow step for Execute and Request Campaigns:  

If Execute or Request Campaign flow step does not include any choices, the card will show name of the campaign. Clicking on the card will open slide out panel with the following information: 

Campaign that the flow step belongs to 

Edit Flow button to access Flow tab 

List of attributes associated to the flow step 

View List button which open a list of campaigns that use the specific request or execute campaign  

Note: You can edit the flow step from a primary campaign. To edit nested campaigns, you will have to navigate to the campaign via the hyperlink in the slide out panel.  

SCREENSHOT

SCREENSHOT

If Execute or Request Campaign flow step includes choices, the card will show name of the campaign. Clicking on the card will open slide out panel with the following information: 

Campaign that the flow step belongs to 

Edit Flow button to access Flow tab 

List of choice conditions associated to the flow step 

SCREENSHOT

SCREENSHOT

If a execute or request campaign includes choices, clicking on the flow card will expand to show all choices in individual cards.  

Clicking on the choice card will expand the campaign associated to the specific choice and simultaneously open slide out panel with the following information: 

Campaign that the choice belongs to 

Edit choice button to access Flow tab 

List of choice conditions associated to the flow step 

View List button which open a list of campaigns that use the specific request or execute campaign  

SCREENSHOT

Visualizing Nested Execute Campaign (new section) 

Execute campaigns run in series with the parent campaign i.e leads that qualify for an executable campaign complete all flow steps from the campaign and return to the primary campaign to continue through flow steps of this campaign.  

Here's an example of a smart campaign "Campaign A" which includes a execute campaign flow step. You can think of "Campaign A" to be your primary campaign. 

SCREENSHOT

Clicking on the execute campaign flow card will expand to show details of "Campaign B" 

Campaign B includes filter which branches out in not qualified and qualified audience.  

Qualified audience goes through flow steps associated to "Campaign B" 

All audience (qualified and not qualified) return to "Campaign A" and move to the next flow step 

SCREENSHOT

You can click on Execute Campaign flow step in "Campaign B" which will expand to show choice cards and campaign associated with each choice. 

SCREENSHOT

Visualizing Request Campaign (new section) 

Request campaigns run in parallel with the parent campaign i.e leads that qualify for a request campaign complete all flow steps from the campaign and exit the campaign. In parallel, the same set of leads will also go through flow steps from the primary campaign 

Here's an example of a smart campaign "Campaign A" which includes a request campaign flow step. You can think of "Campaign A" to be your primary campaign.

SCREENSHOT

Clicking on the request campaign flow card will expand to show details of "Campaign B" 

Campaign B includes filter which branches out in to qualified audience.  

Qualified audience goes through flow steps associated to "Campaign B" 

In parallel, all audience move to the next flow steps in "Campaign A" 

SCREENSHOT

You can dive deeper into nested campaigns, if any of the flow steps includes yet another request campaign by clicking on the flow card to view details of the campaign 

SCREENSHOT

Here's an example of request campaign with choices.  

SCREENSHOT

Error handling: 

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
