---
unique-page-id: 10096683
description: ON24 Event Registration Updates - Marketo Docs - Product Documentation
title: ON24 Event Registration Updates
---

# ON24 Event Registration Updates {#on-event-registration-updates}

ON24 Event Registration Updates - Marketo Docs - Product Documentation

### What's in this article? {#what-s-in-this-article}

[Manually Approving Registrants](#on24eventregistrationupdates-manuallyapprovingregistrants)  
[Handling People with a Registration Error](#on24eventregistrationupdates-handlingpeoplewitharegistrationerror)  
[Updating Member Status from ON24](#on24eventregistrationupdates-updatingmemberstatusfromon24)

#### Manually Approving Registrants {#on24eventregistrationupdates-manuallyapprovingregistrants}

You can manually approve your registrants before sending them a confirmation email. To do so, you will need to configure your campaigns to handle this additional step:

##### 1. For the Registration Trigger Campaign: {#on24eventregistrationupdates-fortheregistrationtriggercampaign-}

* In the Smart List, set the trigger to **Fills Out Form**.
* In the Flow, set the Status in Progression to `**Pending Approval**`.

##### 2. Go to the Event and click the Members tab. This tab displays all the people who have filled out the form. Their status should be set to Pending Approval. {#on24eventregistrationupdates-gototheeventandclickthememberstab.thistabdisplaysallthepeoplewhohavefilledouttheform.theirstatusshouldbesettopendingapproval.}

##### 3. Use the filter at the top of the grid to view only the people with a status of Pending Approval. {#on24eventregistrationupdates-usethefilteratthetopofthegridtoviewonlythepeoplewithastatusofpendingapproval.}

##### 4. Select the people that you wish to register (Shift-click, Control-click, or Select All). {#on24eventregistrationupdates-selectthepeoplethatyouwishtoregister(shift-click-control-click-orselectall).}

##### 5. From the menu, click Change Status. Select Registered, Rejected, or any other applicable status. {#on24eventregistrationupdates-fromthemenu-clickchangestatus.selectregistered-rejected-oranyotherapplicablestatus.}

#### Handling People with a Registration Error {#on24eventregistrationupdates-handlingpeoplewitharegistrationerror}

If a person ends up not being registered but rather set to the status Registration Error, it's not too late to recover.

##### 1. From the Members tab, filter the list of people with the status Registration Error.  {#on24eventregistrationupdates-fromthememberstab-filterthelistofpeoplewiththestatusregistrationerror.}

##### 2. Before continuing, make sure you have determined and fixed the issue with integration (check to make sure there are no errors under Event Partners in Admin).  {#on24eventregistrationupdates-beforecontinuing-makesureyouhavedeterminedandfixedtheissuewithintegration(checktomakesuretherearenoerrorsundereventpartnersinadmin).}

##### 3. After the issue is resolved, select all the people with the Registration Error status and change their status to Registered. This will attempt to register them again with ON24. {#on24eventregistrationupdates-aftertheissueisresolved-selectallthepeoplewiththeregistrationerrorstatusandchangetheirstatustoregistered.thiswillattempttoregisterthemagainwithon24.}

#### Updating Member Status from ON24 {#on24eventregistrationupdates-updatingmemberstatusfromon24}

Marketo automatically pulls in the attendance information at approximately 11pm Pacific each night. To manually update attendance information, click **Refresh from Webinar Provider** under **Event Actions**.

>[!NOTE]
>
>**Related Articles**
>
>* [Understanding Marketo ON24 Adapter Events](understanding-marketo-on24-adapter-events.md)
>

