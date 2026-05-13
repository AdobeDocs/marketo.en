---
unique-page-id: 2359476
description: Learn how to use the email program dashboard to view performance. Monitor opens, clicks, and other metrics at a glance.
title: Use the Email Program Dashboard
exl-id: 47c1925a-144b-4277-a08d-1af660ed3d50
feature: Email Programs
TQID: https://experienceleague.adobe.com/CfPK3TiQRdHB01BUAPFHsM2mn3-CR-b7ELhz01gtUzo
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
# Use the Email Program Dashboard {#use-the-email-program-dashboard}

Check out how your email programs are performing with this dashboard view.

>[!CAUTION]
>
>For accurate reporting, avoid _reusing_ an email from an email program, either by referencing it in a Smart Campaign or by moving the asset from the launched email program to a new one. Doing so will aggregate all of the data in every reporting dashboard attached to that email. If you need to reuse an email, please [clone it](/help/marketo/product-docs/core-marketo-concepts/programs/working-with-programs/clone-an-asset-in-a-program.md){target="_blank"} instead, as that copies the email but creates a new one with a new email ID.

>[!NOTE]
>
>If your program has an A/B test, check out the [Email Program Dashboard - A/B Test View](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/use-the-email-program-dashboard-a-b-test-view.md){target="_blank"}.

![](assets/image2014-9-12-14-3a12-3a56.png)

>[!NOTE]
>
>All data in this view is aggregate (includes A/B test as well as the final email send).

## Email Send {#email-send}

Here you can see how many emails were sent, bounced, and delivered.

![](assets/image2014-9-12-14-3a13-3a3.png)

>[!NOTE]
>
>Due to email deliverability standards that are outside of Marketo's control, Bounced and Delivered stats are approximate, not exact.

## Opens/Clicks {#opens-clicks}

This chart shows you the number of emails opened/clicked during specific time periods after the email program was run.

![](assets/image2014-9-12-14-3a13-3a7.png)

>[!TIP]
>
>Notice how the number of opens/clicks diminishes as time goes by.

## Summary - Engagement {#summary-engagement}

This shows you the overall [engagement score](/help/marketo/product-docs/email-marketing/drip-nurturing/reports-and-notifications/understanding-the-engagement-score.md){target="_blank"}.

![](assets/image2014-9-12-14-3a13-3a11.png)

## Summary - Rest {#summary-rest}

The rest of the data will display Opens, Clicks, Click/Open Ratio, and Unsubscribes.

![](assets/image2014-9-12-14-3a13-3a15.png)

>[!TIP]
>
>The **Unsubscribe** rate in the above example was so small that Marketo zoomed in to give you a better look. The second number within the bar is merely added for scale.

>[!NOTE]
>
>**Definition**
>
>**[!UICONTROL Opens]** are counted when the email recipient downloads the email's images, which includes a Marketo-inserted tracking pixel. If the recipient views the email but chooses not to download its images, that will not count as an open. If the images load in the recipient's preview pane, that will usually count as an open, but it will vary based on the email client.
>
>**[!UICONTROL Click to Open]** measures the percentage of emails that were both opened and had a link clicked in the email. We take the number of unique clicks divided by the number of unique opens, then multiply by 100 to show it as a percentage.

## Refresh Dashboard {#refresh-dashboard}

To see the most up-to-date data, simply click the refresh icon on the dashboard.

![](assets/refreshicon.png)

>[!MORELIKETHIS]
>
>[Use the Email Program Dashboard - A/B Test View](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/use-the-email-program-dashboard-a-b-test-view.md){target="_blank"}
