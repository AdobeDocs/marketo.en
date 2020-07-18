---
unique-page-id: 18874572
description: Duplicate Records and Bizible - Bizible - Product Documentation
title: Duplicate Records and Bizible
---

# Duplicate Records and Bizible {#duplicate-records-and-bizible}

Duplicate Records and Bizible - Bizible - Product Documentation

Bizible leverages the email address as our unique identifier when matching data to a related Lead or Contact in the CRM. When Bizible finds multiple Leads or Contacts with the same email address, we will surface the same data on all records. The impact of this comes when you are reporting on the Leads or Contacts with Bizible and can incorrectly inflate the amount of unique people who have Bizible Touchpoints.  
  
What does this look like in Bizible Reporting?

*Example report: Bizible Persons with Bizible Touchpoints.*

![](assets/1-1.png)  
  
You can see for the Bizible Person ID of [`[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#f09b959c839589b092998a99929c95de939f9d) that there is both a Lead and Contact that exists with that email address. You will find that in this report, there are 2 First Touches reported, 2 Lead Creation Touches, and 2 PostLC interaction reported. These duplicate records share the same touchpoint date and touchpoint information which could lead to the conclusion that they are 2 different people despite being the same person.   
  
**Recommendation**

* In order to maximize the return in your reports, we recommend leveraging a de-duping tool within your CRM to ensure that you are only creating net new, unique records. This can be done with your Marketing Automation tool or a separate software installed within your CRM. Bizible does not dedupe records automatically and does not offer this service through our software.
* An alternative option would be to manually merge records as you identify duplicates. This process can be time consuming and tedious, but the output of accurate reporting is worth the time investment.

