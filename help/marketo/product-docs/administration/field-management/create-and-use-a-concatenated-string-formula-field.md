---
unique-page-id: 2360337
description: Create and Use a Concatenated String (Formula) Field - Marketo Docs - Product Documentation
title: Create and Use a Concatenated String (Formula) Field
---

# Create and Use a Concatenated String (Formula) Field {#create-and-use-a-concatenated-string-formula-field}

You can combine values from multiple fields or build a conditional value using a Marketo Formula field.

1. Go to **Admin** and click **Field Management**.

   ![](assets/image2014-9-19-9-3a44-3a58.png)

1. Click **New Custom Field**.

   ![](assets/image2014-9-19-9-3a45-3a8.png)

1. Select **Formula** for the **Type**.

   ![](assets/image2014-9-19-9-3a45-3a17.png)

1. Enter a **Name** for your field then click **Create**.

   ![](assets/image2014-9-19-9-3a46-3a0.png)

1. Find and select your formula field then click **Edit Rules**.

   ![](assets/image2014-9-19-9-3a46-3a13.png)

1. Add two choices and define them like the screenshot below.

   ![](assets/image2014-9-19-9-3a46-3a25.png)

   >[!TIP]
   >
   >Learn more about [tokens for flow steps](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md).

1. Now you can add the formula field as a token in an email.

   ![](assets/seven.png)

>[!NOTE]
>
>Formula fields can be used in landing pages, emails and smart list columns (they are not exported). Emails with formula fields can **not** be sent using a batch campaign. Please use an [email script token](/help/marketo/product-docs/email-marketing/general/using-tokens/create-an-email-script-token.md) in this scenario.

Good work! Now you have a smart field that knows what salutation to include based on gender. Have fun with this and get creative.
