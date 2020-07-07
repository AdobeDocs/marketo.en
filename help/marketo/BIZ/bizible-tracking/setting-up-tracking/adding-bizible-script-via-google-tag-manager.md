---
unique-page-id: 18874797
description: Adding Bizible Script via Google Tag Manager - Bizible - Product Documentation
title: Adding Bizible Script via Google Tag Manager
---

# Adding Bizible Script via Google Tag Manager {#adding-bizible-script-via-google-tag-manager}

Adding Bizible Script via Google Tag Manager - Bizible - Product Documentation

When installing the Bizible javascript, we strongly recommend [hard-coding the script](http://docs.marketo.com/x/qwEgAQ) directly into your site. However, if that isn't possible, you can also use Google Tag Manager (GTM) to load the Bizible JS. Please note that Bizible JS loaded through GTM is susceptible to latency. Latency causes a delay in script load times which can result in missing around 3-5% of all form submissions.

If you decide to add our script via GTM, please set the Bizible script to the highest priority in your firing order and ensure there are no synchronous scripts in front of the Bizible tag in order to reduce any effects from GTM latency.

>[!NOTE]
>
>Please use this support [article by Google](http://support.google.com/tagmanager/answer/2772421?hl=en) to learn more.

#### How to Add Bizible JS via Google Tag Manager {#how-to-add-bizible-js-via-google-tag-manager}

1. Open GTM and add the Bizible script on your website container. Be sure to select **Custom HTML tag**. 
1. Use the Bizible script below and incorporate it in your container.

   *<script type="text/javascript" src="//cdn.bizible.com/scripts/bizible.js" async=""></script>*

1. Click 

   ```
   +Add
   ```

   a Firing Rule so that you can tell Google to load our snippet on *All Pages.*
1. Go to the Container Draft Overview section on the left. Click the button to create a new version of your container and publish the changes.

