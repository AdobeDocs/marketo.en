---
unique-page-id: 6848782
description: Make Your Unsubscribe Message Dynamic for Languages - Marketo Docs - Product Documentation
title: Make Your Unsubscribe Message Dynamic for Languages
---

# Make Your Unsubscribe Message Dynamic for Languages {#make-your-unsubscribe-message-dynamic-for-languages}

The default unsubscribe message and link are in English. You can use dynamic content to display it in different languages.

>[!NOTE]
>
>We set up this nice little tutorial below for you. It represents a best practice, but this can be accomplished other ways.

1. Prepare Your Data 
1. [Create a custom field](../../../../product-docs/administration/field-management/create-a-custom-field-in-marketo.md)named "Preferred Language." (Set it up in your CRM if you want this field to sync).

   >[!TIP]
   >
   >In the future, use this field when you [create a form](../../../../product-docs/demand-generation/forms/creating-a-form/create-a-form.md) to capture language preference.

1. Create Segmentation
1. Go to the **Database**. 
   ** ![](assets/db.png)

   **

1. In the **New** drop-down, click **New Segmentation**.

   ![](assets/two.png) 

1. Name the segmentation **Preferred Language**. Click **Add Segment**. Type in a language.

   ![](assets/image2015-3-9-8-3a33-3a44.png)

   >[!NOTE]
   >
   >The default segment will be English.

1. Continue to add segments until all of your languages are represented. Click **Create**.

   ![](assets/image2015-3-9-8-3a38-3a5.png)

1. Select a segment. 

   ![](assets/image2015-3-9-8-3a38-3a17.png)

1. Go to the **Smart List** tab. Enter **Preferred Language** into the search field. Drag and drop the filter onto the canvas.

   ![](assets/six.png)

1. Set the appropriate corresponding language.

   ![](assets/seven.png)

1. Repeat for all your different languages. Then, select the **Segmentation Actions** drop-down and click **Approve**.

   ![](assets/image2015-3-9-8-3a39-3a36.png)

1. Create a Snippet
1. Go to the **Design Studio**.

   ![](assets/ds.png)

1. In the **New** dropdown, click **New Snippet**.

   ** ![](assets/ten.png)

   **

1. Name the snippet **Unsubscribe Message**. Click **Create**.

   ![](assets/image2015-3-9-8-3a40-3a54.png)

1. Type your default unsubscribe message, highlight it, and click the hyperlink icon.

   ![](assets/image2015-3-9-8-3a41-3a47.png)

1. Copy and paste this token: **`{{system.unsubscribeLink}}`** into the **Link URL** field. Click **Insert**. 

   ![](assets/image2015-3-9-8-3a43-3a17.png)

1. Select **Segment By** in the Segmentation section.

   ![](assets/image2015-3-9-8-3a44-3a16.png)

1. From the Segmentation drop-down, type in **Preferred** and select **Preferred Language**. Click **Save**.

   ![](assets/image2015-3-9-8-3a44-3a32.png)

1. Select a segment from the tree. Type in your unsubscribe message in that language.

   ![](assets/image2015-3-9-8-3a45-3a43.png)

1. Copy and paste the same token: **`{{system.unsubscribeLink}}`** into the **Link URL** field. Click **Insert**. 

   ![](assets/image2015-3-9-8-3a47-3a4.png)

1. Repeat for all your segments. Then, go back to the Design Studio, click the **Snippet Actions** drop-down, and click **Approve**. 

   ![](assets/image2015-3-9-8-3a47-3a34.png)

   Awesome. Almost there. 

1. Use Snippet in an Email
1. Inside the email editor, click the editable element. Then click the gear icon and select **Replace with Snippet**. If you're selecting an editable snippet element, click the gear icon and select **Edit**.

   ![](assets/4.1.png)

1. Find and select your snippet from the drop-down and click **Save**.

   ![](assets/image2015-3-9-8-3a50-3a16.png)

1. To test it out, click **Back**...

   ![](assets/4.3.png)

1. ...then the **Dynamic** tab.

   ![](assets/4.4.png)

1. Click the different languages to see the snippet change.

   ![](assets/4.5.png)

   >[!TIP]
   >
   >Of course, you can edit the rest of your email for dynamic language too. While you are at it, do the same technique on the unsubscribe page.

1. Customizing Your Unsubscribe Page with Dynamic Content

   If you want your people to come to an unsubscribe page in their preferred language, you can use dynamic content on the landing page and the confirmation page.

   Navigate to the Design Studio.

   ![](assets/ds.png)

   Type in Unsubscribe in the search field. You should find your Unsubscribe pages.

   ![](assets/image2015-3-9-8-3a51-3a53.png)

   Click Edit Draft.

   ![](assets/image2015-3-9-8-3a52-3a23.png)

   Select Segment By.

   ![](assets/image2015-3-9-8-3a52-3a57.png)

   Find the Preferred Language segment. Click Save.

   ![](assets/image2015-3-9-8-3a53-3a54.png)

   Edit your content for each landing page, approve, and you're good to go!

   >[!NOTE]
   >
   >**Deep Dive**
   >
   >
   >Learn more about  [dynamic content](../../../../product-docs/personalization/segmentation-and-snippets/segmentation/understanding-dynamic-content.md) and all the cool stuff you can do.

