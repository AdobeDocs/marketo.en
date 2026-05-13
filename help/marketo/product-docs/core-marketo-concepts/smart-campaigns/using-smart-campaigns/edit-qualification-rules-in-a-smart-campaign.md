---
unique-page-id: 1146974
description: Learn how to edit qualification rules in a Smart Campaign. Change how many times people can run through the campaign.
title: Edit Qualification Rules in a Smart Campaign
exl-id: 8b016fe4-8caf-4266-9f8f-2b05dae78cff
feature: Smart Campaigns
TQID: https://experienceleague.adobe.com/4ECvGFFV51jBniUn7-LG82svSLPwu3VJI2kt5-EmIqc
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
---
# Edit Qualification Rules in a Smart Campaign {#edit-qualification-rules-in-a-smart-campaign}

Qualification rules control how many times someone can run through the flow in a Smart Campaign. By default, even if someone triggers a Smart Campaign multiple times, they will only be sent through the flow once.

1. In your Smart Campaign, click the **[!UICONTROL Schedule]** tab and then **[!UICONTROL Edit Settings]**.

   ![](assets/edit-qualification-rules-in-a-smart-campaign-1.png)

   >[!TIP]
   >
   >You can also click **[!UICONTROL Edit]** to the right of "Smart Campaign Settings."

1. Choose how often to run your people through the Smart Campaign flow: **[!UICONTROL only once]**, **[!UICONTROL every time]**, or **once every # days**/**weeks**/**months**.

   ![](assets/edit-qualification-rules-in-a-smart-campaign-2.png)

   >[!NOTE]
   >
   >* When you set a rule for once every day, Marketo converts that to hours. For example, if you set the rule for once per day, and a person qualifies at 10pm on a Sunday night, it can't qualify again until 10pm Monday night. This logic also applies when using weeks or months. A month is always counted as 30 days.
   >
   >* Communication limits are not applied to Smart Campaigns by default. Learn how to [apply communication limits to a Smart Campaign](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/apply-communication-limits-to-smart-campaign.md){target="_blank"}.
