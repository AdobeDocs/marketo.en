---
unique-page-id: 2360337
description: Create and Use a Concatenated String (Formula) Field - Marketo Docs - Product Documentation
title: Create and Use a Concatenated String (Formula) Field
exl-id: 779fbc56-a913-422a-a778-d86cc3ed7d48
---
# Create and Use a Concatenated String (Formula) Field {#create-and-use-a-concatenated-string-formula-field}

You can combine values from multiple fields or build a conditional value using a Marketo Formula field.

1. Go to the **[!UICONTROL Admin]** area.

   ![](assets/create-and-use-a-concatenated-string-formula-field-1.png)

1. Click **[!UICONTROL Field Management]**.

   ![](assets/create-and-use-a-concatenated-string-formula-field-2.png)

1. Click **[!UICONTROL New Custom Field]**.

   ![](assets/create-and-use-a-concatenated-string-formula-field-3.png)

1. Select **[!UICONTROL Formula]** for the **[!UICONTROL Type]**.

   ![](assets/create-and-use-a-concatenated-string-formula-field-4.png)

1. Enter a **[!UICONTROL Name]** for your field then click **[!UICONTROL Create]**.

   ![](assets/create-and-use-a-concatenated-string-formula-field-5.png)

1. Find and select your formula field then click **[!UICONTROL Edit Rules]**.

   ![](assets/create-and-use-a-concatenated-string-formula-field-6.png)

1. Add two choices and define them like the screenshot below.

   ![](assets/create-and-use-a-concatenated-string-formula-field-7.png)

   >[!TIP]
   >
   >Learn more about [tokens for flow steps](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md).

1. Now you can add the formula field as a token in an email.

   ![](assets/create-and-use-a-concatenated-string-formula-field-8.png)

>[!NOTE]
>
>Formula fields can be used in landing pages, emails and smart list columns (they are not exported). Emails with formula fields can _not_ be sent using a batch campaign. Please use an [email script token](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md) in this scenario.

Good work! Now you have a smart field that knows what salutation to include based on gender. Have fun with this and get creative.
