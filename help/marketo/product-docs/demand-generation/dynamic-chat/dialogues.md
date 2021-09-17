---
description: Dialogues - Marketo Docs - Product Documentation
title: Dialogues
hide: yes
hidefromtoc: yes
---
# Dialogues {#dialogues}

Dialogues are the specific chat conversations you set up. They can be customized by look, as well as what is said and who sees it.

## Create a New Dialogue {#create-a-new-dialogue}

1. Click **Dialogues**.

PICC

1. Click the **Create New** button.

PICC

1. Enter a name (description is optional), set the priority level, and click **Save**.

PICC

>[!NOTE]
>
>EXPLAIN PRIORITY LEVEL

## Audience Criteria {#audience-criteria}

Similar to Marketo Smart Lists, Audience Criteria attributes allow you to define your target audience.

There are several attributes to choose from. In this example we're choosing Lead State _is_ California and Company Size _is greater than_ 50.

1. Grab the Lead State attribute and drag it to the right.

PICC

1. _Is_ is set by default. In the Select Values field, type in CA (you can also click the drop-down and select from the list).

PICC

1. Grab the Company Size attribute and drag it to the right.

PICC

1. Click the operator drop-down and select Greater Than.

PICC

1. Type 50 and click elsewhere on the screen to save.

PICC

## Add Groups {#add-groups}

You have the option of grouping attributes as well, in case you want to have all of certain attributes along with "any" of another.

FINISH THIS

## Target {#target}

This is where you enter the specific URL(s) that you want a specific Dialogue to be shown on.

Acceptable formats:

* `http://website.com`
* `https://*.website.com`
* `http://website.com/folder/*`
* `https://*.website.com/folder/*`

>[!NOTE]
>
>Using an asterisk acts as a catch-all wilcard. So `https://*.website.com` would put the dialogue on every page of the site, including sub-domains (ex: support.website.com). And `https://website.com/folder/*` would put the dialogue on every HTML page in the subsequent folder (ex: in this case let's say the folder is "sports," so: website.com/sports/baseball.html, website.com/sports/football.html, etc.).
