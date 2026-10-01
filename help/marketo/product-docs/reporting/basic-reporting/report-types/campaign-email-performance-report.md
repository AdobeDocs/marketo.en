---
unique-page-id: 2360188
description: Learn about Campaign Email Performance reports that group email statistics by smart campaign. Track opens, clicks, bounces, and unsubscribes to measure campaign effectiveness.
title: Campaign Email Performance Report
exl-id: 524222c6-7cf6-4e6d-a1a5-20a771cd9da5
feature: Reporting
TQID: https://experienceleague.adobe.com/pMoHSEmaDbjOVpoVaUi1lvUHBYkyzOwkuF1n7mxpmY0
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
---
# Campaign Email Performance Report {#campaign-email-performance-report}

To see your email performance stats grouped by [Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/creating-a-smart-campaign/understanding-batch-and-trigger-smart-campaigns.md), run a Campaign Email Performance report.

>[!NOTE]
>
>A Campaign Email Performance Report can only be created as a local asset in a Marketing Activities program. It is not available in the Analytics section.

1. In your program, click **New** and select **New Local Asset**.

   ![](assets/campaign-email-performance-report-1.png)

1. Select **Report**.

   ![](assets/campaign-email-performance-report-2.png)

1. In the _Type_ drop-down, select **Campaign Email Performance**. Give your report a name and click **Create**.

   ![](assets/campaign-email-performance-report-3.png)

1. Define your report's parameters.

   ![](assets/campaign-email-performance-report-4.png)

1. When done, click the **Report** tab to view your report.

[Columns you can select](/help/marketo/product-docs/reporting/basic-reporting/editing-reports/select-report-columns.md) for a Campaign Email Performance report include:

| Column |Description |
|---|---|
| [!UICONTROL Hard Bounced] |Email was rejected because of a permanent condition, such as nonexistent email address. |
| [!UICONTROL Soft Bounced] |Email was rejected because of a temporary condition, such as a server being down or a full inbox. |
| [!UICONTROL Pending] |Email is still in the process of being delivered. |
| [!UICONTROL Clicked Link] |Number of email recipients who clicked a link in the email. |
| [!UICONTROL Unsubscribed] |Number of email recipients who clicked the **[!UICONTROL Unsubscribe]** link in the email and filled out the form. |

>[!NOTE]
>
>In general, we try to use common sense to record these statistics. For example, if someone clicked a link in an email, they obviously opened it first. For the specific rules we follow, see the [Email Performance Report](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md).

>[!MORELIKETHIS]
>
>* [Filter Assets in a Campaign Email Report](/help/marketo/product-docs/reporting/basic-reporting/report-activity/filter-assets-in-a-campaign-email-reports.md)
>* [Email Performance Report](/help/marketo/product-docs/email-marketing/email-programs/email-program-data/email-performance-report.md)
