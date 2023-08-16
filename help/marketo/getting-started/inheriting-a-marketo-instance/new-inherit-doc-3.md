---
description: Inherit Doc 3 - Marketo Docs - Product Documentation
title: Inherit Doc 3
hide: yes
hidefromtoc: yes
---
# Inherit Doc 3 {#inherit-doc-3}

Did you inherit an existing Marketo Engage instance from another Admin? If so, this article is for you.

>[!TIP]
>
>If you're a new(er) Marketo Engage user and are not familiar with many of the terms, please check out the [Marketo Glossary](/help/marketo/getting-started/marketo-glossary.md){target="_blank"}.

## Organization {#organization}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Naming Conventions</td> 
   <td><li>Do your programs have a consistent <a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/best-practice-how-to-organize-your-programs.md#naming-schemes" target="_blank">naming convention</a>?</li></td>
  </tr>
  <tr> 
   <td>Folder Structure</td> 
   <td><li>Do you have a consistent and easy-to-navigate <a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/best-practice-how-to-organize-your-programs.md#folders" target="_blank">folder structure</a>?</li></td>
  </tr>
  <tr> 
   <td>Programs</td> 
   <td><li>Is there a Center of Excellence with program templates? If so, do the program templates make sense for the teams' use cases?</li>
<li>Are similar program types <a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/best-practice-how-to-organize-your-programs.md" target="_blank">consistently structured</a>?</li>
<li>Are <a href="/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/understanding-period-costs.md" target="_blank">period costs</a> put in place?</li>
<li>Are all programs <a href="/help/marketo/product-docs/crm-sync/salesforce-sync/sfdc-sync-details/how-to-match-program-statuses-and-salesforce-campaign-statuses-prior-to-sync.md" target="_blank">synced to SFDC Campaigns</a> (if applicable)?</li>
<li>Do you have flow steps assigning an <a href="/help/marketo/product-docs/core-marketo-concepts/programs/creating-programs/understanding-program-membership.md#acquisition-program" target="_blank">acquisition program</a> to people?</li></td>
  </tr>
  <tr> 
   <td>Archive</td> 
   <td><li>Are older programs archived? The best practice is to review every year.</li>
<li>How often does your company review and archive old programs?</li></td>
  </tr>
  <tr> 
   <td>Notifications</td> 
   <td><li>Are there any campaign errors in the Notifications tab at the top of your instance?</li>
<li>Are you subscribed to notifications to stay on top of any errors that may arise in the future?</li></td>
  </tr>
  <tr> 
   <td>Smart List Subscriptions 
   <br/>(Marketing Activities/Subscriptions tab)</td> 
   <td><li>Are there ongoing smart list subscriptions in your instance? If yes, who are they going to?</li>
<li>Consider setting up smart list subscriptions to go to a team alias rather than an individual. This covers you in case individuals are on vacation or leave.</li></td>
  </tr>
 </tbody> 
</table>

## Assets {#assets}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Tokens</td> 
   <td><li>Are tokens being used in regularly used program types? If not, you should consider using them to increase efficiency.</li>
<li>If tokens are implemented, are there global folder tokens? How are they being used?</li></td>
  </tr>
  <tr> 
   <td>Engagement Programs</td> 
   <td><li>Are there live nurture programs running?</li>
<li>How many people are exhausted? If there are many exhausted people, consider adding content.</li>
<li>Are people engaging with the nurture content? If not, consider updating the content and/or A/B testing.</li>
<li>How many people are in more than one engagement program? Should they be in multiple?</li></td>
  </tr>
  <tr> 
   <td>Batch Campaigns</td> 
   <td><li>How many recurring Batch Campaigns are there?</li>
<li>Should any of them be deactivated/archived?</li></td>
  </tr>
   <tr> 
   <td>Trigger Campaigns</td> 
   <td><li>How many Trigger Campaigns are there?</li>
<li>Should any of them be deactivated/archived?</li>
<li>Should any Trigger Campaigns be changed to Batch Campaigns to improve processing efficiency?</li></td>
  </tr>
  <tr> 
   <td>Local Forms</td> 
   <td><li>How many programs have local forms? Should these forms be turned into global forms?</li>
<li>Are they capturing appropriate data for your Marketing and Sales teams?</li>
<p>Tip: Limit the number of local forms to ease updating and alignment to changes with data privacy, opt-in/opt-out policies? Consider when creating a form, what questions need to be asked, if the information gathered doesn't change and advanced form functionality doesn't shift - consider a global form instead of a local form.</td>
  </tr>
  <tr> 
   <td>Global Forms</td> 
   <td><li>Where do you use global forms? (Marketo landing pages vs. non-Marketo landing pages)</li>
<li>How do your global forms point users to a thank you page? (via hidden form field or within your CMS' page template)</li>
<li>Are there form fields that you should consider adding or removing?</li>
<li>Are there picklist values that you should change?</li>
<li>Do you need to consider progressive profiling?</li>
<li>Are all your required fields for CRM sync and Marketing needs included?</li>
<li>Do your global forms consider your data privacy & legal requirements for opt-in strategy and management?</li></td>
  </tr>
 </tbody> 
</table>

## Operational Programs {#operational-programs}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>Area</th> 
   <th>Review Focus</th>
  </tr> 
  <tr> 
   <td>Person Scoring</td> 
   <td><li>Do you have a centralized person scoring program in place?</li>
<li>Does your person scoring both increase and decrease scoring?</li></td>
  </tr>
  <tr> 
   <td>Person Source</td> 
   <td><li>Do you have a centralized program assigning values to person source fields?</li>
<p>Note: Marketo Engage automatically gathers data in a Source field regardless of operational programs</td>
  </tr>
  <tr> 
   <td>Data Standardization</td> 
   <td><li>Do you have a centralized program in place to standardize incoming data?</li></td>
  </tr>
  <tr> 
   <td>Bounce Management</td> 
   <td><li>Do you have a centralized program to deal with people that bounce?</li></td>
  </tr>
  <tr> 
   <td>Privacy & Compliance</td> 
   <td><li>Do you have programs to ensure you're compliant with data privacy and spam laws? Consider GDPR, CASL, CAN-SPAM, CCPA, etc.</li>
<p>Tip: Remember to always consult your Legal team on these issues. Ask your team about previous initiatives to maintain compliance before making any changes.</td>
  </tr>
  <tr> 
   <td>Lifecycle</td> 
   <td><li>Do you have a program to move people through your Person Lifecycle?</li>
<li>What values are available for Person Status?</li></td>
  </tr>
  <tr> 
   <td>Email Deliverability</td> 
   <td><li>Pull an Email Performance Report for sends in the past few months. How does email deliverability look?</li>
<li>If email deliverability is poor, consider investigating and implementing email deliverability best practices such as SPF and DKIM.</li>
<li>Are you reaching out to your full marketable audience?</li></td>
  </tr>
  <tr> 
   <td>Subscription/Preference Center</td> 
   <td><li>Do you have a Subscription/Preference Center set up? Is it operating as it should?</li></td>
  </tr>
  <tr> 
   <td>Interesting Moments (if applicable)</td> 
   <td><li>Do you have a program or flow steps in programs to send Interesting Moments to Salesforce appropriately?</li></td>
  </tr>
 </tbody> 
</table>
