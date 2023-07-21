---
unique-page-id: 10094188
description: Approve a Custom Object - Marketo Docs - Product Documentation
title: Approve a Custom Object
exl-id: 8bae94df-91fe-4722-8c75-c26df882c65d
feature: Custom Objects
---
# Approve a Custom Object {#approve-a-custom-object}

You must approve a custom object before you can use it. The process is slightly different for new custom objects and ones that you've edited.

## Approve a New Custom Object {#approve-a-new-custom-object}

You've created a brand new custom object. Here's how to approve it.

1. Go to the **Admin** area.

   ![](assets/approve-a-custom-object-1.png)

1. Click **Marketo Custom Objects**.

   ![](assets/approve-a-custom-object-2.png)

1. Select an object that's in a Draft state.

   ![](assets/approve-a-custom-object-3.png)

1. Click the **Custom Object Actions** drop-down and select **Approve Object**.

   ![](assets/approve-a-custom-object-4.png)

1. The state changes to Approved.

   ![](assets/approve-a-custom-object-5.png)

   >[!NOTE]
   >
   >A custom object used in a _one-to-many structure_ must have at least one dedupe field, a link field, a linked object name, and a linked field name to be approved.
   >
   >A custom object used in a _many-to-many structure_ **doesn't** need a link field, linked object name, or a linked field name when you approve it (because they live in the intermediary object).
   >
   >A custom object used as an _intermediary object_ requires a link field, linked object name, and linked field name but **doesn't** require a dedupe field.
   >
   >See [Understanding Marketo Custom Objects](/help/marketo/product-docs/administration/marketo-custom-objects/understanding-marketo-custom-objects.md) for more information.

That's it! Now, you can select your custom object in the constraints of your filters and triggers to use in your campaigns.

## Approve an Edited Custom Object {#approve-an-edited-custom-object}

After you edit an approved custom object, you must approve the draft to return the custom object to an Approved state.

1. When you edit an already approved custom object, it receives an Approved with Draft state.

   ![](assets/approve-a-custom-object-6.png)

1. When you're ready to approve the draft, click the **Custom Object Actions** drop-down and select **Approve Object**.

   ![](assets/approve-a-custom-object-7.png)

1. A preview displays the items that were changed in the draft. Click **Approve**.

   ![](assets/approve-a-custom-object-8.png)
