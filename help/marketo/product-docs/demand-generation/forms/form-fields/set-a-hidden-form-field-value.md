---
unique-page-id: 2359663
description: Set a Hidden Form Field Value - Marketo Docs - Product Documentation
title: Set a Hidden Form Field Value
exl-id: acec7de1-8567-42c0-a6ce-a91b0bf69f41
---
# Set a Hidden Form Field Value {#set-a-hidden-form-field-value}

Hidden fields are usually populated dynamically. They are not shown to the person filling out the form. Here's how to set the value.

>[!PREREQUISITES]
>
>[Set a Form Field as Hidden](/help/marketo/product-docs/demand-generation/forms/form-fields/set-a-form-field-as-hidden.md)

## Select the Field {#select-the-field}

1. In your form, select the hidden field and click **[!UICONTROL Edit]** for **[!UICONTROL Autofill]**.

   ![](assets/autofill.png)

## Use Default Value {#use-default-value}

By selecting Use **[!UICONTROL Default Value]** you can hard-code a specific value to always be used when this form is submitted. Enter the **[!UICONTROL Default Value]** and click **[!UICONTROL Save]**.

![](assets/image2014-9-15-13-3a5-3a27.png)

## URL Parameter {#url-parameter}

If you want to capture URL Parameters (Query Strings) from the page the person is on when filling out the form, you can use **[!UICONTROL URL Parameters]** to populate your hidden field.

>[!NOTE]
>
>Parameters are kinda techie, aren't they? Once you get them though, they are powerful. This [Wikipedia page on Query Strings](https://en.wikipedia.org/wiki/Query_string) is somewhat helpful.

1. Select **[!UICONTROL URL Parameter]** for **[!UICONTROL Get Value Type]**.

   ![](assets/image2014-9-15-13-3a6-3a48.png)

1. Enter the **[!UICONTROL Parameter Name]** and click **[!UICONTROL Save]**.

   ![](assets/image2014-9-15-13-3a7-3a35.png)

>[!TIP]
>
>You can enter a **[!UICONTROL Default Value]** in case the URL parameter is not found.

## Cookie Value {#cookie-value}

If you're storing data in cookies, you can use **[!UICONTROL Cookie Value]** to pick up data when the form is submitted.

1. Select **[!UICONTROL Cookie Value]** for **[!UICONTROL Get Value From]**.

   ![](assets/image2014-9-15-13-3a8-3a21.png)

1. Enter the cookie **[!UICONTROL Parameter Name]** you want and click **[!UICONTROL Save]**.

   ![](assets/image2014-9-15-13-3a8-3a43.png)

   >[!TIP]
   >
   >You can enter a **[!UICONTROL Default Value]** in case the parameter/cookie is not found.

## Referrer Parameter {#referrer-parameter}

If you want to capture data from the page the visitor came from before filling out the form, you can use **[!UICONTROL Referrer Parameter]**.

1. Set **[!UICONTROL Get Value From]** to **[!UICONTROL Referrer Parameter]**.

   ![](assets/image2014-9-15-13-3a9-3a31.png)

1. Enter the **[!UICONTROL Parameter Name]** which you want to snatch from the referrer URL and click **[!UICONTROL Save]**.

   ![](assets/image2014-9-15-13-3a9-3a56.png)

   >[!TIP]
   >
   >You can enter a **[!UICONTROL Default Value]** in case the referrer parameter is not found.

1. Click **[!UICONTROL Finish]**.

   ![](assets/image2014-9-15-13-3a10-3a26.png)

1. Click **[!UICONTROL Approve and Close]**.

   ![](assets/image2014-9-15-13-3a10-3a43.png)
