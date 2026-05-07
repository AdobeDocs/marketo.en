---
unique-page-id: 10092977
description: "Learn about the Dynamics sync filter Qualify process when converting a lead to a contact. Understand how lead and contact sync filter values affect Marketo sync."
title: Microsoft Dynamics Sync Filter -Qualify
exl-id: 9b26795c-fc94-478e-a7f0-ac8e602792b1
feature: Microsoft Dynamics
---
# [!DNL Microsoft Dynamics] Sync Filter: Qualify {#microsoft-dynamics-sync-filter-qualify}

When you want to convert a lead to a contact in [!DNL Microsoft Dynamics], use this default Qualify process. Then, sync it to Marketo.

## The Conversion Process {#the-conversion-process}

| If the lead sync filter is: |and the contact sync filter is: |This is the result in Marketo |
|---|---|---|
| [!UICONTROL False] |[!UICONTROL False] |Nothing is synced in Marketo |
| [!UICONTROL True] |[!UICONTROL True] |The contact is synced in Marketo |
| [!UICONTROL False] |[!UICONTROL True] |New contact record is created in Marketo |
| [!UICONTROL True] |[!UICONTROL False] |[!DNL MS Dynamics] updates lead info in Marketo but contact record is not synced |

>[!CAUTION]
>
>We only support the out-of-the-box Qualify conversion process.
