---
unique-page-id: 12976798
description: Set up LinkedIn Lead Gen Forms - Marketo Docs - Product Documentation
title: Set up LinkedIn Lead Gen Forms
exl-id: 554a546c-adeb-4132-830d-ff15ba5cf9a1
---
# Set up LinkedIn Lead Gen Forms {#set-up-linkedin-lead-gen-forms}

Use LinkedIn Lead Gen Forms to run ad campaigns in LinkedIn and generate leads for Marketo.

>[!NOTE]
>
>**Admin Permissions Required**

1. Go to Marketo **Admin**.

   ![](assets/image2016-11-29-10-3a50-3a29.png)

1. Go to **LaunchPoint**, click on **New** and select **New Service**.

   ![](assets/image2016-11-29-10-3a51-3a11.png)

1. Enter a **Display Name** for your service, select the **LinkedIn Lead Gen** service from the drop-down, and click **Next**.

   ![](assets/linkedin-lead-gen.png)

1. Marketo opens a new tab in the same browser to [linkedin.com](https://www.linkedin.com). Log in to LinkedIn using the account you want to use for the integration.

   >[!NOTE]
   >
   >The LinkedIn account needs access to all the LinkedIn Business Accounts that you are creating sponsored campaigns for.

   ![](assets/linkedin-login.png)

1. After you're logged into LinkedIn, return to Marketo and click **Authorize**.

   ![](assets/linkedin-lead-gen-authorize.png)

1. When prompted, click **Allow** to accept the Marketo app installation into LinkedIn.

   ![](assets/linkedin-marketo-allow.png)

1. You'll notice you are now authorized. Click **Next**.

   ![](assets/image2017-9-28-7-3a55-3a14.png)

   >[!CAUTION]
   >
   >The service automatically expires one year after authorization. To regain access, simply click **Re-Authorize**. You may have to re-enter your LinkedIn password, depending on your browser settings.

1. Select the account(s) you want LinkedIn Lead Gen leads to come into Marketo from and click **Next**.

   >[!TIP]
   >
   >If you don't see the Business Accounts that you're expecting, make sure that the user's LinkedIn account that is being authorized has Lead Gen Form Manager Permissions to the Business Account in LinkedIn.

   ![](assets/linkedin-pages-to-capture.png)

1. To accept default LinkedIn to Marketo field mappings, simply click **Create**. If you would like to change the default field mapping, remove a field mapping, or add a new field mapping, you can do this on a per field basis through the modal below.

   >[!CAUTION]
   >
   >Marketo supports mapping two LinkedIn fields to a single Marketo field, **but only when** the two LinkedIn fields are not on the same form. If you map two fields from the same LinkedIn form to a single Marketo field, people may fail to enter your Marketo database.

   ![](assets/linkedin-lead-gen-mapping.png)

   >[!NOTE]
   >
   >Only LinkedIn fields that have already been saved to a [form template](https://www.linkedin.com/help/lms/answer/79634) in LinkedIn Campaign Manager will show up as LinkedIn Fields that can be mapped to Marketo fields.

   ![](assets/linkedin-installed-services.png)

Nicely done! People who submit LinkedIn Lead Gen forms will start flowing into Marketo as you run successful campaigns on the LinkedIn side.

>[!NOTE]
>
>You can only authorize a single LinkedIn user account. If you have multiple Business Accounts that you would like to link to Marketo, make sure that the user's LinkedIn account that's being authorized has Lead Gen Form Manager Permissions to the Business Account in LinkedIn.

>[!MORELIKETHIS]
>
>[Use LinkedIn Lead Gen Form Filters and Triggers in a Smart Campaign](/help/marketo/product-docs/demand-generation/social/social-functions/use-linkedin-lead-gen-form-filters-and-triggers-in-a-smart-campaign.md)
