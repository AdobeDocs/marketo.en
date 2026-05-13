---
unique-page-id: 2360217
description: How to set first- and multi-touch attribution, lead conversion, and marketing-influenced opportunity options in Revenue Cycle Analytics.
title: Change Attribution Settings for Analytics
exl-id: 4740b0fa-ddaf-46ed-87d6-8b3f8d35afe3
feature: Administration
TQID: https://experienceleague.adobe.com/AjpEYRzLKRQQsTmYdQUvAVnlcmG-Q6nbVjaZCuQYaUc
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: ea90ebee-5c84-42d9-8b21-006bdabc95a3
    internal-label: Reporting
subfeature_v2:
  - id: e5d29014-8a81-4c0c-845b-2adc7a5d6258
    internal-label: Campaign Inspector
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
    internal-label: Reporting
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Change Attribution Settings for Analytics {#change-attribution-settings-for-analytics}

You can change the way Marketo ties contacts to opportunities for first- and multi-touch attribution, lead conversion metrics, and the marketing-influenced opportunity flag.

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/change-attribution-settings-for-analytics-1.png)

1. Click **[!UICONTROL Revenue Cycle Analytics]**.

   ![](assets/change-attribution-settings-for-analytics-2.png)

1. Click the **[!UICONTROL Edit]** link under **[!UICONTROL Attribution]**.

   ![](assets/change-attribution-settings-for-analytics-3.png)

   >[!TIP]
   >
   >Changing this setting does not modify any Marketo data; it changes the way your reports run. This can be reverted at any time.

1. Select an option and click **[!UICONTROL Save]**.

   ![](assets/change-attribution-settings-for-analytics-4.png)

   >[!NOTE]
   >
   >**Definition**
   >
   >**[!UICONTROL Explicit]**: Only contacts with roles (default).
   >
   >**[!UICONTROL Hybrid]**: Contacts with roles if available. If none are available, it uses all contacts in accounts.
   >
   >**[!UICONTROL Implicit]**: All contacts regardless of role.

>[!CAUTION]
>
>When using **[!UICONTROL Implicit]**, Marketo will always examine all contacts associated to the account regardless of role. **Marketo strongly recommends using [!UICONTROL Explicit] mode**. Using [!UICONTROL Implicit] may create false positives; i.e., people with credit for an opportunity despite having no real influence in the opportunity. Use [!UICONTROL Implicit] with caution.
