---
unique-page-id: 18874558
description: Boomerang Stages and Touchpoints - Bizible - Product Documentation
title: Boomerang Stages and Touchpoints
---

# Boomerang Stages and Touchpoints {#boomerang-stages-and-touchpoints}

Boomerang Stages and Touchpoints - Bizible - Product Documentation

Bizible has released our Boomerang Stage feature! The Boomerang Stage feature was created to provide greater visibility into the customer’s journey for Bizible customers with long sales cycles. This feature allows marketers to create touchpoints for all stage transitions that occur in the Opportunity journey, like when a contact MQLs, then moves to SAL, and then reverts back to the MQL stage. When contacts “re-enter the MQL stage” or “re-MQL’s”, we consider the MQL to be a boomerang stage. The Boomerang Stage feature functions alongside Bizible’s Custom Stages.

### What's in this article? {#what-s-in-this-article}

[What This Feature Does](#boomerangstagesandtouchpoints-whatthisfeaturedoes)  
[What Boomerang Stages and Touchpoints Look like in Your CRM](#boomerangstagesandtouchpoints-whatboomerangstagesandtouchpointslooklikeinyourcrm)  
[How Boomerang Stages Change Your Existing Data](#boomerangstagesandtouchpoints-howboomerangstageschangeyourexistingdata)  
[FAQ](#boomerangstagesandtouchpoints-faq)

#### What This Feature Does {#boomerangstagesandtouchpoints-whatthisfeaturedoes}

* Creates a “boomerang” touchpoint for all stage transitions that occur in an opportunity’s journey
* Tracks repeat transitions between any custom stage (ex. when a Contact MQLs, moves to SAL, and then goes back to the MQL stage)
* Allows you to specify how many and which set of stage transitions you would like included in the Opportunity (ex. The first 10 MQLs OR the last 5 MQLs)
* If you are a Custom Model user, you are able to determine the attribution weighting and percentage credit you’d like to allocate to each of these stages (ex. designate attribution weight to the first or last MQL occurrence, or distribute attribution weighting evenly amongst all occurrences)

>[!NOTE]
>
>[Instructions on how to set up Boomerang Stages](http://docs.marketo.com/x/jwEgAQ).

#### What Boomerang Stages and Touchpoints Look like in Your CRM {#boomerangstagesandtouchpoints-whatboomerangstagesandtouchpointslooklikeinyourcrm}

Without Boomerang stages (the “before”), you will only see the most recent MQL or most recent SQL touchpoint associated to a Lead/Contact record.

![](assets/1.png)&nbsp;

With Boomerang Stages and touchpoints, you will see touchpoints that occur for each stage transition. The naming convention for these boomerang touchpoints will be as follows:

**[Stage Name]-00.**

Using the example below, this Bizible account has included MQL and SQL in their boomerang stages, and have chosen to display 2 boomerang touchpoints per stage.

![](assets/2.png)

**MQL-01** is the first MQL stage transition.

The numerical value in the touchpoint position will denote the order in which the stage transition occurred. The last boomerang touchpoint be stamped as:

MQL-02 **(Last)**

#### How Boomerang Stages Change Your Existing Data {#boomerangstagesandtouchpoints-howboomerangstageschangeyourexistingdata}

Boomerang Stages will impact:

**Attribution by channel**

* Since Boomerang Stages will create more touchpoints, this will change how attribution is distributed among the touchpoints that currently exist in your data. As a result, this may mean that revenue values will shift between marketing channels. Please take this into consideration before implementing Boomerang stages, or contact your account manager for more information.

**Any reports that use “equals [Touchpoint Position]”**

* Boomerang stages will introduce new touchpoint positions to your data. Bizible is changing the format of the Touchpoint Position to include the occurrence of the stage, like “MQL-01” or “MQL-05 (Last).” Using this example, Boomerang Stages will impact any reports that are using “Touchpoint Position is equal to MQL.” To adjust these reports the filter should be using the “contains” operator instead.

#### FAQ {#boomerangstagesandtouchpoints-faq}

##### Q: How many boomerang stages can I include in my attribution model? {#boomerangstagesandtouchpoints-q-howmanyboomerangstagescaniincludeinmyattributionmodel}

You can select up to 15 stages.

##### Q: How many “boomerang” touchpoints can I have per stage? {#boomerangstagesandtouchpoints-q-howmany“boomerang”touchpointscanihaveperstage}

You can select up to 10 boomerang touchpoints per stage.

##### Q: Why are we only limited to 10 boomerangs per stage? {#boomerangstagesandtouchpoints-q-whyareweonlylimitedto10boomerangsperstage}

Bizible has to place a limit on the number of stages in order to keep processing times under control. If you choose to include all 15 Boomerang Stages in your attribution model, and 10 boomerang touchpoints per stage, you could potentially have over 150 touchpoints per Lead/Contact record.

##### Q: I have Data Warehouse. Do I get all of the data or does the Boomerang Stages cap apply to me as well? {#boomerangstagesandtouchpoints-q-ihavedatawarehouse-doigetallofthedataordoestheboomerangstagescapapplytomeaswell}

The cap will apply to Data Warehouse and CRMs because of the processing limits that Bizible has in place. Data Warehouse will also see the limit of 10 touchpoints per stage.

##### Q: What is the benefit of using Boomerang Stages with Custom Modeling? {#boomerangstagesandtouchpoints-q-whatisthebenefitofusingboomerangstageswithcustommodeling}

Using Boomerang Stages with Custom Modelling will allow you to assign attribution weighting to Boomerang touchpoints, which will allocate revenue credit to these stages.

Without custom modeling, Bizible will create touchpoints for each boomerang and stage transition but will not assign any attribution credit to these touchpoints. The only boomerang touchpoints that will receive attribution credits are form submission touchpoints. Without custom model, Boomerang touchpoints are considered the same as a ‘middle touch’ and receive attribution credit accordingly.
