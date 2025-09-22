---
unique-page-id: 11375827
description: "Required Fields for Syncing Marketo with Dynamics - Marketo Docs - Product Documentation"
title: Required Fields for Syncing Marketo with Dynamics
exl-id: c1b9d208-bdc0-4718-b3e5-e9e915b8ae0f
feature: Marketo Sales Insights
---
# Required Fields for Syncing Marketo with [!DNL Dynamics] {#required-fields-for-syncing-marketo-with-dynamics}

These fields *must* be synced with Marketo for both [!UICONTROL Lead] and for [!UICONTROL Contact] for [!DNL Sales Insight] to work:

* Priority
* Urgency
* Relative Score

If any of these fields are missing, you will see an error message in Marketo with the name of the missing fields. To fix this, check in your instance to be sure the fields are synced for both **[!UICONTROL Lead]** and **[!UICONTROL Contact]**. If not, add them.

Here's how to verify and add sync fields.

1. Go to [!UICONTROL Admin] and click **[!UICONTROL Microsoft Dynamics]**.

   ![](assets/image2015-10-9-9-3a50-3a9.png)

1. Click **[!UICONTROL Edit]** on [!UICONTROL Field Sync Details].

   ![](assets/image2015-10-9-9-3a52-3a23.png)

1. Under [!UICONTROL Lead], check the [!UICONTROL Priority] checkbox.

   ![](assets/image2016-6-8-13-3a33-3a50.png)

1. Now, scroll down and check the [!UICONTROL Urgency] checkbox...

   ![](assets/image2016-6-8-13-3a35-3a22.png)

1. ...and the [!UICONTROL Relative Score] checkbox.

   ![](assets/image2016-6-8-13-3a36-3a1.png)

1. Next, check the checkboxes for [!UICONTROL Priority], [!UICONTROL Urgency], and [!UICONTROL Relative Score] for [!UICONTROL Contact].

   ![](assets/image2016-6-8-13-3a36-3a36.png)

1. Click **[!UICONTROL Save]**.

   ![](assets/image2016-6-8-13-3a41-3a27.png)

>[!NOTE]
>
>Be sure to wait at least 10 minutes for a sync to run before verifying that you've fixed the issue.

>[!MORELIKETHIS]
>
>[Setting up Stars and Flames for Lead/Contact Records](/help/marketo/product-docs/marketo-sales-insight/msi-for-microsoft-dynamics/setting-up-and-using/setting-up-stars-and-flames-for-lead-contact-records.md)
