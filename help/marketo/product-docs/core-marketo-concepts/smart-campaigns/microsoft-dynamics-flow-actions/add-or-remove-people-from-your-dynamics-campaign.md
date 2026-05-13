---
description: Learn how to add or remove people from a Microsoft Dynamics campaign with a flow step. Sync Marketo with Dynamics campaigns.
title: Add or Remove People from your [!DNL Dynamics] Campaign
exl-id: 4fea2f7c-0655-4816-8640-76878f760b6e
feature: Smart Campaigns, Microsoft Dynamics
TQID: https://experienceleague.adobe.com/b6tUqixPGr7ZWTUKVg4L6EKryziHA2IwzpuTepWWEwU
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
subfeature_v2:
  - id: ad89fb33-8541-4339-afe7-bb13d1633714
    internal-label: Flow Step
---
# Add or Remove People from your [!DNL Dynamics] Campaign {#add-or-remove-people-from-your-dynamics-campaign}

## Add to Dynamics Campaign {#add-to-dynamics-campaign}

This flow step can be used in Marketo Engage Smart Campaigns to add people as leads or contacts in a Microsoft campaign. If the lead does not yet exist in Dynamics, it will automatically be synced over and get added to the campaign.

>[!NOTE]
>
>This flow action is available for Trigger Campaigns only.

In your Smart Campaign, find and select the Dynamics campaign you want to add your people to.

![](assets/add-or-remove-people-from-your-dynamics-campaign-1.png)

>[!NOTE]
>
>If you cannot see a Dynamics campaign in the campaign list:
>
>* Verify the Campaign Sync is functional
>* The campaign is not active in [!DNL Microsoft Dynamics]

The system automatically creates a campaign-specific static marketing List, each for leads and contacts, to add the person to. It is a one-time action and once for subsequent syncs to the campaign, the same Marketing List is used. The naming standard adopted for the static Marketing List name is `Mkto-leads-<uniqueID>` for leads and `Mkto-contacts-<uniqueID>` for contacts.

Associating these Marketo-generated Marketing Lists to other campaigns could lead to confusing behavior. For example: adding to one campaign would also result in adding to the second campaign. Similarly, dissociating the Marketo-generated Marketing List from the Campaign in [!DNL Dynamics] is also not recommended.

## Remove from Dynamics Campaign {#remove-from-dynamics-campaign}

This flow step can be used in Marketo Smart Campaigns to remove people from a Microsoft campaign. This removes only those leads from a Campaign which have been previously added to the Campaign through the flow action "Added to Microsoft Campaign".

>[!NOTE]
>
>This flow action is available for Trigger Campaigns only.

In your Smart Campaign, find and select the Dynamics campaign you want to remove your people from.

![](assets/add-or-remove-people-from-your-dynamics-campaign-2.png)

>[!NOTE]
>
>If you do not see a [!DNL Dynamics] campaign in the campaign list:
>
>* Verify the Campaign Sync is functional
>* The campaign is not active in [!DNL Microsoft Dynamics]
