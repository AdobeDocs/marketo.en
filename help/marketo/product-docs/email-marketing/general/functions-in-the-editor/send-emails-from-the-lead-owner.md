---
unique-page-id: 1147340
description: Send Emails from the Lead Owner - Marketo Docs - Product Documentation
title: Send Emails from the Lead Owner
---

# Send Emails from the Lead Owner {#send-emails-from-the-lead-owner}

What if you want to send an email to a lead on behalf of the Lead Owner?  Here's how.

1. Find your email, select it and click **Edit Draft**.

   ![](assets/one.png)

1. Click in the **From** field (delete any existing name), and click the **Insert Token** button.

   ![](assets/two.png)

1. Start typing "`{{lead.Lead Owner`" and select the **`{{lead.Lead Owner First Name}}`** token.

   ![](assets/image2014-9-11-13-3a7-3a43.png)

1. Enter a default value in case the lead does not yet have a lead owner and click **Insert**.

   ![](assets/image2014-9-11-13-3a7-3a58.png)

1. Click after the first token, add a space, then click the **Insert Token** button.

   ![](assets/five.png)

1. Start typing "`{{lead.Lead Owner`" and select the **`{{lead.Lead Owner Last Name}}`** token.

   ![](assets/image2014-9-11-13-3a8-3a24.png)

1. Enter a default value in case the lead does not yet have a lead owner and click **Insert**.

   ![](assets/image2014-9-11-13-3a8-3a39.png)

   >[!TIP]
   >
   >Make sure you added a space between the first and last name tokens.

1. Click in the From Email field (delete any existing email address), and click the Insert Token button.

   ![](assets/eight.png)

1. Start typing "`{{lead.Lead Owner`" and select the **`{{lead.Lead Owner Email Address}}`** token.

   ![](assets/image2014-9-11-13-3a9-3a33.png)

1. Enter a default value in case the lead does not yet have a lead owner and click **Insert**.

   ![](assets/ten.png)

1. Make sure the **Reply-to** and **Subject** fields are populated, and you're done!

   ![](assets/eleven.png)
