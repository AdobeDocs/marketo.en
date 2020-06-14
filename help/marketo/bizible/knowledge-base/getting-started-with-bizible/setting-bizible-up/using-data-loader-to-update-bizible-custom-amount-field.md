---
unique-page-id: 18874771
description: Using Data Loader to Update Bizible Custom Amount Field - Bizible - Product Documentation
title: Using Data Loader to Update Bizible Custom Amount Field
---

# Using Data Loader to Update Bizible Custom Amount Field {#using-data-loader-to-update-bizible-custom-amount-field}

Using Data Loader to Update Bizible Custom Amount Field - Bizible - Product Documentation

Bizible recommends using Data Loader as a convenient option to update opportunity values when using a custom revenue field (we use the Amount field out of the box) in Bizible. Data Loader is preferred&nbsp;over using the Bizible update script as the script requires users to disable all Salesforce validation rules while the Bizible script runs.

#### Using Data Loader to Update Bizible Custom Amount Field  
{#usingdataloadertoupdatebiziblecustomamountfield-usingdataloadertoupdatebiziblecustomamountfield}

##### 1. Create an excel sheet with the: {#usingdataloadertoupdatebiziblecustomamountfield-createanexcelsheetwiththe-}

* Opportunity Id
* Custom Opportunity Amount field (your preferred revenue field)
* Bizible Opportunity Amount field

##### 2. Copy and paste the values from your preferred revenue field into the Bizible Opportunity Amount field. Then, update these Opps using the .csv file.  {#usingdataloadertoupdatebiziblecustomamountfield-copyandpastethevaluesfromyourpreferredrevenuefieldintothebizibleopportunityamountfield.then-updatetheseoppsusingthe.csvfile.}

***Alternatively, you can go into Salesforce and use a custom list view to mass edit all the opportunities...*** 

##### 1. Create a Custom List view for all Opportunities. {#usingdataloadertoupdatebiziblecustomamountfield-createacustomlistviewforallopportunities.}

##### 2. Add a filter for preferred revenue field is not blank *and* Bizible Opportunity Amount field is blank. {#usingdataloadertoupdatebiziblecustomamountfield-addafilterforpreferredrevenuefieldisnotblankandbizibleopportunityamountfieldisblank.}

##### 3. Click Mass Edit, but don’t actually change anything. {#usingdataloadertoupdatebiziblecustomamountfield-clickmassedit-butdon’tactuallychangeanything.}

##### 4. Click Save. This will trigger the workflow to populate the Bizible Opportunity Amount fields with the Software Revenue field. {#usingdataloadertoupdatebiziblecustomamountfield-clicksave.thiswilltriggertheworkflowtopopulatethebizibleopportunityamountfieldswiththesoftwarerevenuefield.}

