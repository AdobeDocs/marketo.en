---
unique-page-id: 4718683
description: Approving Stages and Assigning Leads to a Revenue Model - Marketo Docs - Product Documentation
title: Approving Stages and Assigning Leads to a Revenue Model
---

# Approving Stages and Assigning Leads to a Revenue Model {#approving-stages-and-assigning-leads-to-a-revenue-model}

Approving Stages and Assigning Leads to a Revenue Model - Marketo Docs - Product Documentation

Get your **Revenue** **Model** up and running by adding existing leads, creating assignment rules for any new leads.

### What's in this article? {#what-s-in-this-article}

[Approving Stages](#approvingstagesandassigningleadstoarevenuemodel-approvingstages)  
[Assigning Existing Leads](#approvingstagesandassigningleadstoarevenuemodel-assigningexistingleads)  
[New Leads: Create Assignment Rules](#approvingstagesandassigningleadstoarevenuemodel-newleads-createassignmentrules)  
[Example Assignment Rule](#approvingstagesandassigningleadstoarevenuemodel-exampleassignmentrule)

#### Approving Stages  
{#approvingstagesandassigningleadstoarevenuemodel-approvingstages}

Let's approve the stages of your model before you add any leads.

##### 1. Go to the Analytics area.  {#approvingstagesandassigningleadstoarevenuemodel-gototheanalyticsarea.}

![](assets/image2015-4-28-17-3a8-3a8.png)

##### 2. Select the model whose stages you'd like to approve. {#approvingstagesandassigningleadstoarevenuemodel-selectthemodelwhosestagesyou'dliketoapprove.}

![](assets/image2015-4-28-17-3a10-3a3.png)

##### 3. Under Model Actions, select Approve Stages. {#approvingstagesandassigningleadstoarevenuemodel-undermodelactions-selectapprovestages.}

![](assets/image2015-4-28-17-3a12-3a37.png)

##### 4. You'll be greeted with an alert; click Assign Leads. {#approvingstagesandassigningleadstoarevenuemodel-you'llbegreetedwithanalert-clickassignleads.}

![](assets/image2015-4-28-17-3a5-3a39.png)

Excellent! Let's move on and assign those leads.

#### Assigning Existing Leads {#approvingstagesandassigningleadstoarevenuemodel-assigningexistingleads}

[ `Create a Smart List`](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md) to identify the leads for one stage of your model in your `Lead Database.`

##### 1. Once you've [created your Smart List](../../../../../welcome-to-marketo-docs/product-docs/core-marketo-concepts/smart-lists-and-static-lists/creating-a-smart-list/create-a-smart-list.md), click the Leads tab. {#approvingstagesandassigningleadstoarevenuemodel-onceyou'vecreatedyoursmartlist-clicktheleadstab.}

![](assets/image2015-4-29-11-3a37-3a30.png)

##### 2. Click Select All to select the leads.  {#approvingstagesandassigningleadstoarevenuemodel-clickselectalltoselecttheleads.}

![](assets/image2015-4-29-11-3a39-3a39.png)

##### 3. Open the Lead Actions drop-down and select Special. Click Change Revenue Stage. {#approvingstagesandassigningleadstoarevenuemodel-opentheleadactionsdrop-downandselectspecial.clickchangerevenuestage.}

![](assets/image2015-4-29-11-3a40-3a38.png)

##### 4. Select the correct Model and the correct Stage. Click Run Now. {#approvingstagesandassigningleadstoarevenuemodel-selectthecorrectmodelandthecorrectstage.clickrunnow.}

![](assets/image2015-4-29-11-3a43-3a41.png)

##### 5. Repeat until all your leads are assigned to the various stages of your model.  {#approvingstagesandassigningleadstoarevenuemodel-repeatuntilallyourleadsareassignedtothevariousstagesofyourmodel.}

Great! To specify how new leads are assigned to stages, create assignment rules.

>[!NOTE]
>
>If your model is in the Approved Stages state, you will not see any Change Revenue Stage events in the leads' activity logs. If your model is fully approved, this flow step will be skipped if you move a lead into the same stage it's currently in.

#### New Leads: Create Assignment Rules  {#approvingstagesandassigningleadstoarevenuemodel-newleads-createassignmentrules}

##### 1. Click Marketo Home again, then select Analytics. {#approvingstagesandassigningleadstoarevenuemodel-clickmarketohomeagain-thenselectanalytics.}

![](assets/image2015-4-28-17-3a8-3a8.png)

##### 2. Click your model in the tree, then the Model Actions menu, selecting Assignment Rules.  {#approvingstagesandassigningleadstoarevenuemodel-clickyourmodelinthetree-thenthemodelactionsmenu-selectingassignmentrules.}

![](assets/image2015-4-29-11-3a52-3a17.png)

##### 3. If your assignment rules contain more than just one default choice click Stage, make your selection, then click Add Choice.  {#approvingstagesandassigningleadstoarevenuemodel-ifyourassignmentrulescontainmorethanjustonedefaultchoiceclickstage-makeyourselection-thenclickaddchoice.}

![](assets/image2015-4-29-12-3a5-3a46.png)

#### Example Assignment Rule {#approvingstagesandassigningleadstoarevenuemodel-exampleassignmentrule}

Create a Lead Score rule to assign the new leads with a minimum score to an appropriate step.

##### 1. Under If, select Lead Score. Then choose at least.  {#approvingstagesandassigningleadstoarevenuemodel-underif-selectleadscore.thenchooseatleast.}

` ![](assets/image2015-4-29-13-3a27-3a8.png)

` 

##### 2. Enter 40 in the field and select Sales Lead as a Stage. Click Save to complete. {#approvingstagesandassigningleadstoarevenuemodel-enter40inthefieldandselectsalesleadasastage.clicksavetocomplete.}

![](assets/image2015-4-29-14-3a4-3a23.png)

>[!NOTE]
>
>**Related Articles**
>
>To approve your model, read our help page on ** [Approving and Unapproving a Revenue Model](approve/unapprove-a-revenue-model.md)**.

