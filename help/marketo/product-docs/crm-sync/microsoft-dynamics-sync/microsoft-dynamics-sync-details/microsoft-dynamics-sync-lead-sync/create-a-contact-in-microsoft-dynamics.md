---
unique-page-id: 10095389
description: Learn how to create a contact in Microsoft Dynamics from Marketo. Use the Sync Person to Microsoft flow action in a trigger campaign for real-time contact creation.
title: Create a Contact in Microsoft Dynamics
exl-id: 66cb26c0-f383-4d1e-be22-e7f8c6b266fb
feature: Microsoft Dynamics
TQID: 'https://experienceleague.adobe.com/5q84B57P88MNhaYHluCKKCYLwOonW2xj7hAUNDOmXl8'
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
subfeature_v2:
  - id: d5c7388a-594e-4d15-9b39-98d6ce479e8b
    internal-label: Microsoft Dynamics
---
# Create a Contact in [!DNL Microsoft Dynamics] {#create-a-contact-in-microsoft-dynamics}

1. Select the Marketo Engage-only person (Microsoft Type is empty) that you want to create as a contact in Dynamics.

   ![](assets/one.png)

1. Click **[!UICONTROL Person Actions]** and **[!DNL Microsoft]**, and select **[!UICONTROL Sync Person to Microsoft]**.

   ![](assets/two.png)

1. Click **[!UICONTROL Sync As]** and select **[!UICONTROL Contact]**. Click **[!UICONTROL Run Now]**.

   ![](assets/three.png)

   >[!NOTE]
   >
   >When using the "[!UICONTROL Sync Person to Microsoft]" flow action (in a Trigger Campaign only), the lead/contact will be created in real-time in Dynamics.

1. Marketo qualifies that Lead record in [!DNL Dynamics] into a Contact that is not associated to any Account in [!DNL Dynamics].

   ![](assets/image2015-10-23-9-3a43-3a33.png)

1. Now, you can select **[!UICONTROL Contact]** when you use the Sync As constraint in a smart campaign filter.

   ![](assets/five.png)
