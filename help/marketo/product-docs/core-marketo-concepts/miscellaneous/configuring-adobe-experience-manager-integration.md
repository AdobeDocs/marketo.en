---
unique-page-id: 30081815
description: Configuring Adobe Experience Manager Integration - Marketo Docs - Product Documentation
title: Configuring Adobe Experience Manager Integration
---

# Configuring Adobe Experience Manager Integration {#configuring-adobe-experience-manager-integration}

Configure AEM so you can access, select, and import AEM assets into Marketo's Design Studio.

>[!NOTE]
>
>**Admin Permissions Required**

>[!CAUTION]
>
>Currently, this feature is only fully supported in Firefox. It is not supported in Safari, and it might not work in the latest version of Chrome (v. 80), depending on your SameSite cookie settings.

1. Navigate to the Adobe Experience Manager (the URL is specific to your company).

   ![](assets/one.png)

1. You can sign in with Adobe or sign in locally. In this example we'll sign in locally.

   ![](assets/two.png)

1. In **Tools**, click **Operations** and select **Web Console**.

   ![](assets/2a.png)

1. In your browser, search (ctrl+f on Windows, cmd+f on Mac) for "Adobe Granite Cross-Origin Resource Sharing Policy."

   ![](assets/three.png)

1. Click the **+** sign on the right.

   ![](assets/four.png)

1. In the **Allowed Origins (Regexp)** text box, type in `https://.*\.marketo\.com` and click **Save**.

   ![](assets/five-psd.png)

1. In the header at the top of the page, click **Web Console** and select **System Information**.

   ![](assets/six.png)

1. Under Server Information, click the **Restart** button.

   ![](assets/seven.png)

1. Click **OK** to confirm.

   ![](assets/eight.png)

1. In Marketo Classic, click **Admin**.

   ![](assets/nine.png)

1. Under Integration, select **Adobe Experience Manager**.

   ![](assets/ten.png)

1. Click **Edit**.

   ![](assets/eleven.png)

1. Enter your AEM URL and click **OK**.

   ![](assets/twelve.png)

   You're all set! You can now [import AEM assets into the Design Studio in Marketo Sky](https://help.marketo.com/hc/en-us/articles/360036765993).
