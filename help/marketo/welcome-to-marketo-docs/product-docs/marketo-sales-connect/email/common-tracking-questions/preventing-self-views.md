---
unique-page-id: 14352540
description: Preventing Self Views - Marketo Docs - Product Documentation
title: Preventing Self Views
---

# Preventing Self Views {#preventing-self-views}

Preventing Self Views - Marketo Docs - Product Documentation

### What's in this article? {#what-s-in-this-article}

[Overview](#preventingselfviews-overview)  
[Web (Outlook Web App and Gmail)](#preventingselfviews-web(outlookwebappandgmail))  
[Desktop (Windows)](#preventingselfviews-desktop(windows))  
[Desktop (Mac)](#preventingselfviews-desktop(mac))

#### Overview {#preventingselfviews-overview}

Getting false positives on your view tracking can lead to reporting inconsistencies. This often occurs when users of MSC accidentally invoke the tracking pixel from their email client (we call this a self-view). Below are a few tips on significantly reducing and even eliminating self-views.

#### Web (Outlook Web App and Gmail) {#preventingselfviews-web(outlookwebappandgmail)}

Sales Connect will store a cookie in your browser to prevent views from being tracked when opening your emails from Outlook Web App and Gmail. If you are still receiving self-views, we recommend doing the following:

* Ensure that you have cookies enabled on your computer.

* If you're using a new computer or mobile device, make sure you've logged in to the web application. This will allow us to recognize your computer/device going forward.

#### Desktop (Windows) {#preventingselfviews-desktop(windows)}

Views are tracked by downloading a small invisible image pixel in your email client. You can significantly lower the amount of self-views in Outlook by disabling images to be automatically downloaded. Below are the steps how.

##### 1. In Outlook, click File in the menu bar. {#preventingselfviews-inoutlook-clickfileinthemenubar.}

![](assets/win-1.png)

##### 2. Click Options. {#preventingselfviews-clickoptions.}

![](assets/win-2.png)

##### 3. In the Outlook Options dialog box, click Trust Center. {#preventingselfviews-intheoutlookoptionsdialogbox-clicktrustcenter.}

![](assets/win-3.png)

##### 4. Under Microsoft Outlook Trust Center, click Trust Center Settings. {#preventingselfviews-undermicrosoftoutlooktrustcenter-clicktrustcentersettings.}

![](assets/win-4.png)

##### 5. Click Automatic Download in the menu on the left, and select the Don't download pictures automatically in HTML email or RSS items check box. {#preventingselfviews-clickautomaticdownloadinthemenuontheleft-andselectthedon'tdownloadpicturesautomaticallyinhtmlemailorrssitemscheckbox.}

![](assets/win-5.png)

##### 6. Click OK in the Trust Center dialog box. {#preventingselfviews-clickokinthetrustcenterdialogbox.}

![](assets/win-6.png)

##### 7. Click OK in the Outlook Options dialog box. {#preventingselfviews-clickokintheoutlookoptionsdialogbox.}

![](assets/win-6.png)

#### Desktop (Mac) {#preventingselfviews-desktop(mac)}

Views are tracked by downloading a small invisible image pixel in your email client. You can significantly lower the amount of self-views in Outlook by disabling images to be automatically downloaded. Below are the steps how.

##### 1. In Outlook, click Outlook in the menu bar and select Preferences. {#preventingselfviews-inoutlook-clickoutlookinthemenubarandselectpreferences.}

![](assets/mac-1.png)

##### 2. Under Email, choose Reading. {#preventingselfviews-underemail-choosereading.}

![](assets/mac-2.png)

##### 3. Under Security, click the Never radio button. {#preventingselfviews-undersecurity-clicktheneverradiobutton.}

![](assets/mac-3.png)

