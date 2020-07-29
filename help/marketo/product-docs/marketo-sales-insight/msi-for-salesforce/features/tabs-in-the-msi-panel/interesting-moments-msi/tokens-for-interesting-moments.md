---
unique-page-id: 1146999
description: Tokens for Interesting Moments - Marketo Docs - Product Documentation
title: Tokens for Interesting Moments
---

# Tokens for Interesting Moments {#tokens-for-interesting-moments}

>[!NOTE]
>
>**Prerequisites**
>
>* Learn to use the [Interesting Moment flow step](../../../../../../product-docs/core-marketo-concepts/smart-campaigns/flow-actions/interesting-moment.md).
>* Learn more about [tokens](http://docs.marketo.com/display/docs/tokens).
>

#### Available Tokens {#available-tokens}

Check out [Tokens Overview](../../../../../../product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md) to see all the tokens you can put into an interesting moment.

#### Trigger Tokens {#trigger-tokens}

Based on the trigger used in a smart campaign, additional Trigger Tokens are made available.

* {{trigger.Trigger Name}} which is always the actual trigger itself. For example: Clicks Link in Email.
* {{trigger.Name}} is the name of the asset that triggered the campaign. For example: Clicks Link on Webpage is the URL itself, subject for Salesforce triggers, etc.
* Additional triggers are available based on constraints, which are listed below:

|   |{{trigger.Trigger Name}} |{{trigger.Name}} |{{trigger.Link}} |{{trigger.Subject}} |{{trigger.Category}} |{{trigger.Details}} |{{trigger.Web Page}} |{{trigger.Client IP Address}} |{{trigger.Sent By}} |{{trigger.Received By}} |
|---|---|---|---|---|---|---|---|---|---|---|
| Clicks Link in Email | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  |  |  |  |  |  |
| Email Bounces Hard | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  |  |  |  |
| Email Bounces Soft | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  |  |  |  |
| Email Is Delivered | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  | ![(tick)](assets/check.svg)

|  |  |  |  |  |  |
| Opens Email | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  | ![(tick)](assets/check.svg)

|  |  |  |  |  |  |
| Unsubscribes from Email | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  | ![(tick)](assets/check.svg)

|  |  | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  |  |
| Clicks Link in Sales Email | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  |  |  |  | ![(tick)](assets/check.svg)

|  |
| Sent Sales Email | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  | ![(tick)](assets/check.svg)

|  |  |  |  | ![(tick)](assets/check.svg)

|  |
| Opens Sales Email | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  | ![(tick)](assets/check.svg)

|  |  |  |  | ![(tick)](assets/check.svg)

|  |
| Sales Email Received | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  | ![(tick)](assets/check.svg)

|  |  |  |  |  | ![(tick)](assets/check.svg)

|
| Fills Out Form | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  |  |  |  | ![(tick)](assets/check.svg)

| ![(tick)](assets/check.svg)

|  | |
| Visits Web Page&#42; | ![(tick)](assets/check.svg)

|  |  |  |  |  | ![(tick)](assets/check.svg)

|  |  |  |

>[!NOTE]
>
>If it doesn't have a check ![(tick)](assets/check.svg) then it would return an empty string (nothing) in the interesting moment.

&#42;The Trigger **Visits Web Page** has a few additional tokens:

* {{trigger.Referrer}}
* {{trigger.Search Engine}} 
* {{trigger.Search Query}}

>[!TIP]
>
>Always test out your interesting moments to ensure they render the way you intend.
>
>Also, make sure it's interesting to the Sales person, not just to you. ![(wink)](assets/wink.svg)>

