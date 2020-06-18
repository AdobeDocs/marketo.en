---
unique-page-id: 18874646
description: Difference Between Bizible Touchpoints and Bizible Attribution Touchpoints - Bizible - Product Documentation
title: Difference Between Bizible Touchpoints and Bizible Attribution Touchpoints
---

# Difference Between Bizible Touchpoints and Bizible Attribution Touchpoints {#difference-between-bizible-touchpoints-and-bizible-attribution-touchpoints}

Difference Between Bizible Touchpoints and Bizible Attribution Touchpoints - Bizible - Product Documentation

Learn what defines a Bizible Touchpoint (BT) and Bizible Attribution Touchpoint (BAT), the differences between the two, and answer commonly asked questions.

The key distinguisher between Bizible Touchpoints and Bizible Attribution Touchpoints is their relationship with Salesforce Objects. BTs relate to the Lead, Contact, and Case Objects, but not the Opportunity object. Meaning there'll never be revenue associated to Bizible Touchpoints.

While the Bizible Attribution Touchpoint Object related to the Contact, Account, and Opportunity Objects, but not the Lead Object. Meaning there'll never be Bizible Attribution Touchpoints tied to Leads. The BAT Object is where you'll see revenue tied to specific marketing interactions.

Difference between BT and BAT:

<table> 
 <colgroup> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td>Bizible Touchpoint (BT)</td> 
   <td>Bizible Attribution Touchpoint (BAT)</td> 
  </tr> 
  <tr> 
   <td> 
    <ul> 
     <li>Relates to the Lead, Contact, and Case Objects</li> 
     <li>Does not relate to the Opportunity Object</li> 
     <li>Revenue is not associated to a Bizible Touchpoint</li> 
    </ul></td> 
   <td> 
    <ul> 
     <li>Relates to the Contact, Account, and Opportunity Objects</li> 
     <li>Does not relate to the Lead Object</li> 
     <li>Since a Bizible Attribution Touchpoint is associated to an Opportunity, all BATs have revenue associated to them</li> 
    </ul></td> 
  </tr> 
 </tbody> 
</table>

#### FAQ {#differencebetweenbizibletouchpointsandbizibleattributiontouchpoints-faq}

##### When does a Bizible Touchpoint become a Bizible Attribution Touchpoint? {#differencebetweenbizibletouchpointsandbizibleattributiontouchpoints-whendoesabizibletouchpointbecomeabizibleattributiontouchpoint}

A BT becomes a BAT once this BT is associated to a Contact that has an associated Opportunity. One very important thing to understand is that one specific marketing interaction can be a BT and BAT.

##### Can a Bizible Touchpoint have a Touchpoint Position of Opportunity Creation (OC)? {#differencebetweenbizibletouchpointsandbizibleattributiontouchpoints-canabizibletouchpointhaveatouchpointpositionofopportunitycreation-oc}

A Bizible Touchpoint will only have a Touchpoint Position of either First Touch (FT), Lead Creation (LC), or Form submission (intermediary touchpoints). Since BTs aren't related to Opportunities it's not possible for a BT to have a Touchpoint Position of Opportunity Creation or Closed.

##### How is Bizible Touchpoint data leveraged? {#differencebetweenbizibletouchpointsandbizibleattributiontouchpoints-howisbizibletouchpointdataleveraged}

Typically customers leverage Bizible Touchpoint data to understand Top of the Funnel & Middle of the Funnel engagement. Meaning Bizible users know who's submitting forms, who's viewing their site, what blog post is performing well, what AdWords ad is driving leads to convert, etc. Bizible Touchpoint data is great for understanding the engagement of your Leads & Contacts.

##### What does a Bizible Touchpoint look like in Salesforce? {#differencebetweenbizibletouchpointsandbizibleattributiontouchpoints-whatdoesabizibletouchpointlooklikeinsalesforce}

Here's a screenshot of a BT in Salesforce:

![](assets/1.png)

##### What does a Bizible Attribution Touchpoint look like in Salesforce? {#differencebetweenbizibletouchpointsandbizibleattributiontouchpoints-whatdoesabizibleattributiontouchpointlooklikeinsalesforce}

Here's a screenshot of a BAT in Salesforce:

![](assets/2.png)

