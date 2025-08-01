---
description: Routing - Marketo Docs - Product Documentation
title: Routing
feature: Dynamic Chat
exl-id: e20193b9-55c1-40f2-9e42-5b5dc9b88144
---
# Routing {#routing}

Meetings booked in Dynamic Chat can be routed two ways. Round robin, or using a custom rule.

Round robin: Meetings get assigned to agents sequentially. So if you have five agents and agent three took the last meeting, agent four will get the next one, followed by agent five, then back to agent one.

Custom rule: You can choose specific agents to receive meetings based on attributes you select.

>[!NOTE]
>
>Account Routing is given the highest priority. When a visitor reaches the point in the conversation to either book a meeting or initiate a live chat, [Account Routing](#account-routing) is checked first before other routing options are considered.

## Create a Custom Rule {#create-a-custom-rule}

In this example we're sending all meetings from the inferred states of CA, OR, and WA to agent John.

1. Under Configuration, click **Routing Rules**.

   ![](assets/routing-1.png)

1. The **Custom Rules** tab opens by default.

   ![](assets/routing-2.png)

1. Click **Create Rule**.

   ![](assets/routing-3.png)

1. Name your rule. Optionally, you can add a description and set its priority level. Click **Next**.

   ![](assets/routing-4.png)

1. Choose your desired agent(s).

   ![](assets/routing-5.png)

1. Drag over your desired attribute(s).

   ![](assets/routing-6.png)

1. Find and select your desired value(s).

   ![](assets/routing-7.png)

1. When all of your desired values are selected, click **Save**.

   ![](assets/routing-8.png)

## Account Routing {#account-routing}

Identify and upload your target account and respective sales owners and route visitors coming from those accounts directly to the respective account owner.

   ![](assets/routing-9.png)

   >[!PREREQUISITES]
   >
   >Before _Account Routing_ is visible in Dynamic Chat, permissions must be enabled in the Admin Console. See [Enable Permissions](#enable-permissions) below.

### Enable Permissions {#enable-permissions}

+++ Enable Account Routing Permissions

1. Log in to [https://adminconsole.adobe.com/](https://adminconsole.adobe.com/){target="_blank"}.

1. Under _Products_, select **Dynamic Chat**.

   ![](assets/routing-10.png)

1. Under _Product profiles_, select the desired profile.

   ![](assets/routing-11.png)

1. Click the **Permissions** tab.

   ![](assets/routing-12.png)

1. Click the edit icon (![Edit icon](assets/icon-routing-edit.png)) next to _Configuration_.

   ![](assets/routing-13.png)

1. Click the **+** sign next to _View account routing_.

   ![](assets/routing-14.png){width="600" zoomable="yes"}

1. Click **Save** when done.

+++

### Add an Account {#add-an-account}

In this example, we'll route all employees from Lego directly to agent Steven.

1. In the Account Routing tab, click **+ Add Account**.

   ![](assets/routing-15.png)

   >[!TIP]
   >
   >You can create multiple Accounts at once by clicking **Upload Account List** and uploading a CSV.

1. Enter the company's name, domain, and select the desired agent.

   ![](assets/routing-16.png)
