---
unique-page-id: 18874736
description: Remove Bizible Tracking Parameters from the Landing Page URL in Google Analytics - Bizible - Product Documentation
title: Remove Bizible Tracking Parameters from the Landing Page URL in Google Analytics
---

# Remove Bizible Tracking Parameters from the Landing Page URL in Google Analytics {#remove-bizible-tracking-parameters-from-the-landing-page-url-in-google-analytics}

Remove Bizible Tracking Parameters from the Landing Page URL in Google Analytics - Bizible - Product Documentation

Sometimes when viewing landing pages in Google Analytics, you’ll want to remove tracking parameters from the URLs. Otherwise, they’ll split into individual rows.

Luckily, this is an easy fix.

##### 1. In Google Analytics, go to Admin > View Settings > Exclude URL Query Parameters. {#removebizibletrackingparametersfromthelandingpageurlingoogleanalytics-ingoogleanalytics-gotoadmin>viewsettings>excludeurlqueryparameters.}

##### 2. Type “_bt,_bk,_bm,_bn,_bg” in the box (minus the quotes). {#removebizibletrackingparametersfromthelandingpageurlingoogleanalytics-type“-bt-bk-bm-bn-bg”inthebox(minusthequotes).}

##### 3. Scroll down and click Save. {#removebizibletrackingparametersfromthelandingpageurlingoogleanalytics-scrolldownandclicksave.}

Keep in mind that Google Analytics does not reprocess data. Therefore this change will only be reflected moving forward, and your past data will still show with the bt, bk, and bm parameters.

