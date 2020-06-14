---
unique-page-id: 18874775
description: Machine Learning Model FAQ - Bizible - Product Documentation
title: Machine Learning Model FAQ
---

# Machine Learning Model FAQ {#machine-learning-model-faq}

Machine Learning Model FAQ - Bizible - Product Documentation

Bizible's Machine Learning model uses your touchpoint data to calculate how much attribution weighting should be assigned to each stage. This is determined by how important each stage was in driving deals to close.

### What's in this article? {#what-s-in-this-article}

[What do the attribution percentages from the Machine Learning Model tell me about each stage?](#machinelearningmodelfaq-whatdotheattributionpercentagesfromthemachinelearningmodeltellmeabouteachstage?)  
[How is the Machine Learning Model calculated?](#machinelearningmodelfaq-howisthemachinelearningmodelcalculated?)  
[Why am I not seeing any numbers in the Machine Learning column?](#machinelearningmodelfaq-whyaminotseeinganynumbersinthemachinelearningcolumn?)  
[How often is the Machine Learning Model updated?](#machinelearningmodelfaq-howoftenisthemachinelearningmodelupdated?)  
[Why does the Model always set Middle Touches to 10%?](#machinelearningmodelfaq-whydoesthemodelalwayssetmiddletouchesto10%?)  
[When should I change my attribution distribution?](#machinelearningmodelfaq-whenshouldichangemyattributiondistribution?)

##### What do the attribution percentages from the Machine Learning Model tell me about each stage? {#machinelearningmodelfaq-whatdotheattributionpercentagesfromthemachinelearningmodeltellmeabouteachstage?}

The attribution percentages of each stage reflects the potential impact of your marketing efforts. A higher percentage means that marketing can directly influence the movement of the funnel at that point. A lower attribution percentage means that stages are less important for your team to monitor.

##### How is the Machine Learning Model calculated? {#machinelearningmodelfaq-howisthemachinelearningmodelcalculated?}

Bizible calculates the importance of each custom stage by using the touchpoint data from your account. The criteria used to determine the importance of each stage are:

* Model Accuracy: If we build a predictive model with the touchpoint data to predict whether we will win a deal eventually, how accurate will the model be? Higher predictive accuracy means that the details of this stage correlates more with whether a deal will close
* Conversion Rate: If Leads or Opportunities at this certain stage convert to the next stage at a high rate, this suggests that the marketing activities that occurred at this stage didn't matter very much. Conversely, if a certain stage converts to the next stage at a low rate, this can suggest that the marketing activities that occurred at this stage were influential in driving the conversion.
* Touchpoint Uniqueness Weight: If a stage occurs as a standalone transition, meaning there weren't any other stage transitions that occurred at the same time, this stage could receive a higher attribution weight. Conversely, if a touchpoint for a stage is shared with other stages (e.g. the touchpoint shares the First Touch, Lead Conversion, and Opportunity Conversion stages) this stage could receive a lower attribution weighting. `  
  `

The final weight for a custom stage is calculated as such:

***Model Percentage = Model Accuracy x Conversion Rate x Touchpoint Uniqueness Weight***

At the end, all the custom stage weights are normalized and converted to % as shown below.

##### Why am I not seeing any numbers in the Machine Learning column? {#machinelearningmodelfaq-whyaminotseeinganynumbersinthemachinelearningcolumn?}

When the Custom Attribution Model is enabled for your account, it generally takes between 3-7 days for our model to run and build these numbers, based off of your historical data.

##### How often is the Machine Learning Model updated? {#machinelearningmodelfaq-howoftenisthemachinelearningmodelupdated?}

We re-run the model every 7 days.

##### Why does the Model always set Middle Touches to 10%? {#machinelearningmodelfaq-whydoesthemodelalwayssetmiddletouchesto10%?}

Assigning 10% attribution credit to Middle Touches is a standard setting across all of our attribution models.

##### When should I change my attribution distribution? {#machinelearningmodelfaq-whenshouldichangemyattributiondistribution?}

Please reach out to your account manager to discuss the implications of changing your attribution percentages, and which stages to include in your custom model. Each Salesforce and sales process is unique, and we want to ensure that your custom model is accurately modeled.

That being said, we've identified some general trends across our customers:

One trend we've noticed is that it's not always beneficial to include more stages in your model. For example, when customers have added multiple Opportunity stages towards the bottom of the funnel, these stages tend to receive very low attribution percentage values. Low percentage values indicate a high conversion rate, which typically means that that these stages aren't as impactful at driving deals to close. Some customers ultimately decide to not include these stages in the funnel. If you decide to remove a stage from your attribution model, the machine model will recalculate and redistribute the percentages.

We've also noticed that there is a high conversion rate from Lead Creation to Marketing Qualified stages, and consequently, the Marketing Qualified stage could receive a lower percentage attribution weighting. Depending on your business and sales cycle, it may be beneficial to remove this stage from the custom model.

Please keep in mind if you'd like to track marketing activities through a specific stage transition but you do not want this stage to receive attribution credit, you can include this stage in your model and assign 0% attribution credit to that stage.
