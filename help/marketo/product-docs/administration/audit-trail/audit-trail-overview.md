---
unique-page-id: 11377945
description: Overview of Audit Trail and how it captures a six-month history of changes and login activity in your Marketo instance.
title: Audit Trail Overview
exl-id: e8aff7b7-72ca-4d4e-9159-56ff65f6345c
feature: Audit Trail
TQID: https://experienceleague.adobe.com/4MTpv09ZFWkX6tirnq7ZIABSkfoz07qljcUUORwYNn8
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: b0bb9048-d951-48d8-8232-45cf248a7e27
    internal-label: Forms
  - id: b13bd2ad-8e65-49e5-9691-2a0d31067b35
    internal-label: Integrations
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: d65b4a73-87a3-4d56-b638-74e74d9939ce
    internal-label: Design Studio
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: ed6be6bb-75bb-4ea9-9a42-3bcaa65e1bcc
    internal-label: Personalization
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Audit Trail Overview {#audit-trail-overview}

Audit Trail gives you the ability to obtain a complete history (six months' worth) of changes made within your Marketo instance.

>[!NOTE]
>
>Audit Trail data history began back on September 14, 2016.

![](assets/audit-trail-overview-1.png)

## What is Audit Trail {#what-is-audit-trail}

Audit Trail captures, in real-time, a comprehensive list of actions and events occurring within a Marketo subscription. It includes a self-serve way to access a six-month history of data to help answer questions such as:

"What happened to this asset or setting, and who last updated it?"

"What has user X been up to?"

"Who is logging into our account?"

## What We Audit {#what-we-audit}

Marketo audits the [create, edit, and delete](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md) actions for:

* Design studio assets
* All Marketo programs
* Smart campaigns
* Lists (smart/static)
* Users (admin)
* Roles and permissions (admin)
* Workspace and partitions (admin)
* User login history

>[!NOTE]
>
>Marketo is _not_ auditing changes made within Web Personalization, Predictive Content, or Sales Insight at this time.

## Audit Trail Components {#audit-trail-components}

Audit Trail consists of three components.

**1) [Asset Audit Trail](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#asset-audit-trail)**

See activity done to specific assets.

**2) [Admin Audit Trail](/help/marketo/product-docs/administration/audit-trail/change-details-in-audit-trail.md#admin-audit-trail)**

Monitor user-based details.

**3) [User Login History](/help/marketo/product-docs/administration/audit-trail/user-login-history.md)**

See who's been logging into your subscription and when (also includes failed login attempts).

>[!TIP]
>
>Since there's so much you can audit using Audit Trail, [filtering](/help/marketo/product-docs/administration/audit-trail/filtering-in-audit-trail.md) can be a big time-saver.

## Exporting Data {#exporting-data}

You can only view 30 days' worth of data in your instance. To obtain (up to) six months' worth, use the export option.

![](assets/two.png)

>[!NOTE]
>
>**Definition**
>
>**Unknown:** In [!DNL Webhook], you may see a user's name and email listed as "Unknown." This happens when you make a change to your picklist values in your CRM. These values appear in Marketo forms and landing pages. Doing this update on the CRM side will auto-draft your landing pages referencing the form. In [!DNL Webhook], Marketo captures that the landing page was drafted, but the user's name and email will show as "Unknown," as Marketo is not able to capture the user info from the CRM side.

>[!MORELIKETHIS]
>
>[Enable Audit Trail](/help/marketo/product-docs/administration/audit-trail/enable-audit-trail.md)
