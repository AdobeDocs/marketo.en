---
unique-page-id: 11377945
description: Audit Trail Overview - Marketo Docs - Product Documentation
title: Audit Trail Overview
---

# Audit Trail Overview {#audit-trail-overview}

Audit Trail Overview - Marketo Docs - Product Documentation

Audit Trail gives you the ability to obtain a complete history (six months' worth) of changes made within your Marketo instance.

>[!NOTE]
>
>Audit trail data history began as of September 14, 2016.

### What's in this article? {#what-s-in-this-article}

[What is Audit Trail](#audittrailoverview-whatisaudittrail)  
[What We Audit](#audittrailoverview-whatweaudit)  
[Audit Trail Components](#audittrailoverview-audittrailcomponents)  
[Exporting Data](#audittrailoverview-exportingdata)  
![](assets/one.png)

#### What is Audit Trail {#audittrailoverview-whatisaudittrail}

Audit Trail captures, in real-time, a comprehensive list of actions and events occurring within a Marketo subscription. It includes a self-serve way to access a six-month history of data to help answer questions such as:

What happened to this asset or setting, and who last updated it?

What has user X been up to?

Who is logging into our account?

#### What We Audit {#audittrailoverview-whatweaudit}

Marketo will audit the [create, edit and delete](http://docs.marketo.com/display/DOCS/Change+Details+in+Audit+Trail) actions for:

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
>Marketo is **not** auditing changes made within Web Personalization, Predictive Content, or Sales Insight at this time.

#### Audit Trail Components {#audittrailoverview-audittrailcomponents}

Audit Trail consists of three components.

**1) [Asset Audit Trail](http://docs.marketo.com/display/DOCS/Change+Details+in+Audit+Trail#ChangeDetailsinAuditTrail-AssetAuditTrail)**

See activity done to specific assets.

**2) [Admin Audit Trail](http://docs.marketo.com/display/DOCS/Change+Details+in+Audit+Trail#ChangeDetailsinAuditTrail-AdminAuditTrail)**

Monitor user-based details.

**3) [User Login History](http://docs.marketo.com/display/DOCS/User+Login+History)**

See who's been logging into your subscription and when. Also includes failed login attempts.

>[!TIP]
>
>There's so much you can audit using Audit Trail, be sure to utilize [Filtering](http://docs.marketo.com/display/DOCS/Filtering+in+Audit+Trail)!

#### Exporting Data {#audittrailoverview-exportingdata}

You can only view 30 days' worth of data in your instance. To obtain (up to) six months' worth, use the export option.

![](assets/two.png)

>[!NOTE]
>
>**Definition**
>
>**Unknown:** In audit trail, you may see a user’s name and email listed as “Unknown.” This happens when you make a change to your picklist values in your CRM. These values appear in Marketo forms and landing pages. Doing this update on the CRM side will auto-draft your landing pages referencing the form. In audit trail, we will capture that the landing page was drafted, but the user’s name and email will show as “Unknown,” as we are not able to capture the user info from the CRM side.

>[!NOTE]
>
>**Related Articles**
>
>* [Enable Audit Trail](enable-audit-trail.md)
>

