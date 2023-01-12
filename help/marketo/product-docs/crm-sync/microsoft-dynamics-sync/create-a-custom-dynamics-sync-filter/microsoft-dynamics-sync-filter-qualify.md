---
unique-page-id: 10092977
description: Microsoft Dynamics Sync Filter -Qualify - Marketo Docs - Product Documentation
title: Microsoft Dynamics Sync Filter -Qualify
exl-id: 9b26795c-fc94-478e-a7f0-ac8e602792b1
---
# [!DNL Microsoft Dynamics] Sync Filter: Qualify {#microsoft-dynamics-sync-filter-qualify}

When you want to convert a lead to a contact in [!DNL Microsoft Dynamics], be sure to use this default Qualify process. Then, sync it to Marketo.

## The Conversion Process {#the-conversion-process}

Here's how the filters work during the conversion process.

| If the lead sync filter is: |and the contact sync filter is: |This is the result in Marketo |
|---|---|---|
| False |False |Nothing is synced in Marketo |
| True |True |The contact is synced in Marketo |
| False |True |New contact record is created in Marketo |
| True |False |[!DNL MS Dynamics] updates lead info in Marketo but contact record is not synced |

>[!CAUTION]
>
>We only support the out-of-the-box Qualify conversion process.
