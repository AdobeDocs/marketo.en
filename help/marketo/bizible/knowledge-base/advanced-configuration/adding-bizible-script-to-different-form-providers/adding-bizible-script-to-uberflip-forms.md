---
unique-page-id: 18874749
description: Adding Bizible Script to Uberflip Forms - Bizible - Product Documentation
title: Adding Bizible Script to Uberflip Forms
---

# Adding Bizible Script to Uberflip Forms {#adding-bizible-script-to-uberflip-forms}

Adding Bizible Script to Uberflip Forms - Bizible - Product Documentation

If you are currently using Uberflip to manage your content, it's important that you take these necessary steps to make sure that Bizible is tracking those form submissions. Your Success Manager at Uberflip should also be able to assist you with this.

##### 1. Add this script to Uberflip's Custom Code>HTML section. {#addingbiziblescripttouberflipforms-addthisscripttouberflip'scustomcode>htmlsection.}

*<script type="text/javascript" src="//cdn.bizible.com/scripts/bizible.js" async=""></script>*

##### 2. Ensure this Bizible preamble code fires on both page load and AJAX page change. Do this within the Custom Code>JS section {#addingbiziblescripttouberflipforms-ensurethisbiziblepreamblecodefiresonbothpageloadandajaxpagechange.dothiswithinthecustomcode>jssection}

*window['Bizible'] = window['Bizible'] || { _queue: [], Push: function (o, p) {this._queue.push({ type: o, data: p }); } };*

You'll add this preamble to both the Hubs.onLoad and the Hubs.onPageChange AJAX Javascript event hooks per below. (Note: You may have other codes in these event hooks as well. Just make sure you include the preamble too.)  
  
*Hubs.onLoad = function () {* 
  
*window['Bizible'] = window['Bizible'] || { _queue: [], Push: function (o, p) {this._queue.push({ type: o, data: p }); } };* 
  
*}* 
  
*Hubs.onPageChange = function () {* 
  
*window['Bizible'] = window['Bizible'] || { _queue: [], Push: function (o, p) {this._queue.push({ type: o, data: p }); } };* 
  
*}*

##### 3. Create and define a function that will push data to Bizible upon a Form CTA submit. This goes into the Custom Code>Javascript section. (Note: this function only requires the ctaData parameter Uberflip provides, but you can include the other parameters ctaId and ctaName in case the user wants to customize their code to pass this data as well). {#addingbiziblescripttouberflipforms-createanddefineafunctionthatwillpushdatatobizibleuponaformctasubmit.thisgoesintothecustomcode>javascriptsection.(note-thisfunctiononlyrequiresthectadataparameteruberflipprovides-butyoucanincludetheotherparametersctaidand}

*function bizibleFormCode(ctaId, ctaData, ctaName) {* 
* var email = ctaData["email"];* 
*if(email){* 
* Bizible.Push('User', {* 
* eMail: email, // required* 
* }); }* 
  
*}*

##### 4. When a Form CTA is submitted, make sure your Bizible function is executed per below. This is done within the Custom Code>JS section. (Note: You might have other code within the Hubs.onCtaFormSubmitSuccess javascript event hook, just make sure you include this function call as well). {#addingbiziblescripttouberflipforms-whenaformctaissubmitted-makesureyourbiziblefunctionisexecutedperbelow.thisisdonewithinthecustomcode>jssection.(note-youmighthaveothercodewithinthehubs.onctaformsubmitsuccessjavascripteventhook-justmakesureyouincludethisf}

*Hubs.onCtaFormSubmitSuccess = function (ctaId, ctaData, ctaName) {* 
* bizibleFormCode(ctaId, ctaData, ctaName); * 
* }*
