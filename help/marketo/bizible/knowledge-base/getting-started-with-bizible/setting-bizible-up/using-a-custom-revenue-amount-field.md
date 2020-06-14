---
unique-page-id: 18874793
description: Using a Custom Revenue Amount Field - Bizible - Product Documentation
title: Using a Custom Revenue Amount Field
---

# Using a Custom Revenue Amount Field {#using-a-custom-revenue-amount-field}

Using a Custom Revenue Amount Field - Bizible - Product Documentation

By default, Bizible Attribution Touchpoints will pull the Opportunity Amount from one of two fields:

* `Amount (SFDC Default)`
* `Bizible Opportunity Amount (Custom)`

If you are using a custom Amount field on your Opportunities, we will need to configure a workflow in order to calculate the Bizible Touchpoint Revenue. This takes some more advanced knowledge of Salesforce, so it may require assistance from your SFDC Admin.

Starting off, we will need the following information:

* `API Name of your Amount field`

From here, we will start creating the workflow.

##### 1. Navigate to Setup > Create > Workflow & Approvals > Workflow Rules. {#usingacustomrevenueamountfield-navigatetosetup>create>workflow&approvals>workflowrules.}

![](assets/1-1.jpg)

##### 2. Select New Rule and set the object as “Opportunity” and click Next. {#usingacustomrevenueamountfield-selectnewruleandsettheobjectas“opportunity”andclicknext.}

![](assets/2-1.jpg)

![](assets/3-1.jpg)

##### 3. Configure the workflow. Set the Rule Name as “Update Bizible Opportunity Amount." Set the Evaluation Criteria to “Created, and every time it’s edited.” For the Rule Criteria, select your custom Amount field and select the Operator as “Not Equal To” and leave the “Value” field blank. {#usingacustomrevenueamountfield-configuretheworkflow.settherulenameas“updatebizibleopportunityamount."settheevaluationcriteriato“created-andeverytimeit’sedited.”fortherulecriteria-selectyourcustomamountfieldandselecttheoperatoras“notequalto”andleavethe“val}

![](assets/4-1.jpg)

##### 4. Add a workflow action. Set this picklist to “New Field Update.” {#usingacustomrevenueamountfield-addaworkflowaction.setthispicklistto“newfieldupdate.”}

![](assets/5-1.jpg)

##### 5. Here you will fill out field information. In the “Name” field, we recommend using this naming: “Bizible Opp Amount." The “Unique Name” will automatically populate based off the “Name” field. In the “Field to Update” picklist select “Bizible Opportunity Amount." After selecting the field, select the "Re-Evaulate Workflow Rules after Field Change" box. In the “Specify New Field Value,” select “Use a formula to set the new value." In the empty box, drop the API name of your custom Amount field. Click Save. {#usingacustomrevenueamountfield-hereyouwillfilloutfieldinformation.inthe“name”field-werecommendusingthisnaming-“bizibleoppamount."the“uniquename”willautomaticallypopulatebasedoffthe“name”field.inthe“fieldtoupdate”picklistselect“bizibleopportunityamount."af}

` ![](assets/6-4.png)  
`

##### 6. You will be brought back to a roll-up page for your workflow, be sure to “Activate” and you’ll be good to go. To activate, click Edit next to your new workflow and then click Activate.  {#usingacustomrevenueamountfield-youwillbebroughtbacktoaroll-uppageforyourworkflow-besureto“activate”andyou’llbegoodtogo.toactivate-clickeditnexttoyournewworkflowandthenclickactivate.}

Once you’ve completed these steps, the opportunities will need to be updated in order to trigger the workflow to have the new value from the custom opportunity field.

This can be accomplished by running your opportunities through Data Loader within SFDC. Please find details on using Data Loader in [this article](http://docs.marketo.com/x/kwEgAQ).

If there are any questions along the way, please don’t hesitate to reach out to your Bizible Success Manager or [ `[email protected]`](http://docs.marketo.com/cdn-cgi/l/email-protection#e2919792928d9096a2808b988b808e87cc818d8f).

