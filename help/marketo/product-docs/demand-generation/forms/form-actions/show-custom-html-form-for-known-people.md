---
unique-page-id: 2359644
description: Show Custom HTML Form for Known People - Marketo Docs - Product Documentation
title: Show Custom HTML Form for Known People
exl-id: 668216ea-7c2b-4204-81a5-56547c3baf1d
---
# Show Custom HTML Form for Known People {#show-custom-html-form-for-known-people}

If a visitor is cookied (known person who provided an email address in the past), then why bother with the form? Just give them the download button. Here's how.

1. Go to **[!UICONTROL Marketing Activities]**.

   ![](assets/login-marketing-activities-5.png)

1. Under **[!UICONTROL Marketing Activities]**, select your form and click **[!UICONTROL Edit Form]**.

   ![](assets/image2014-9-15-12-3a24-3a6.png)

1. Under **[!UICONTROL Form Settings]**, click on **[!UICONTROL Settings]**.

   ![](assets/image2014-9-15-12-3a24-3a36.png)

1. Set If **[!UICONTROL Known Visitor, Show]**: to **[!UICONTROL Custom HTML]**.

   ![](assets/image2014-9-15-12-3a24-3a59.png)

1. Click the ![--](assets/image2014-9-25-14-3a1-3a26.png) to edit the **[!UICONTROL Custom HTML]** that will be shown to known people.

   ![](assets/image2014-9-15-12-3a25-3a38.png)

1. There's some default content, but feel free to change it up.

   ![](assets/image2014-9-15-12-3a25-3a49.png)

   Available tokens:

   | Token |Description |
   |---|---|
   | `{{lead.FirstName}}` |This will display the person's first name. |
   | `{{lead.LastName}}` |This will display the person's last name. |
   | `{{form.Button:default=Download}}` |This will display the form button. Replace the area after the `=` to change the button text. |
   | `{{form.NotYou:default=Not you?}}` |This will display a link in case the person is someone else. Replace the area after the `=` to change the link text. |

   >[!CAUTION]
   >
   >Only the four tokens above can be used. Any other token will not work here.

1. Click **[!UICONTROL Finish]**.

   ![](assets/image2014-9-15-12-3a27-3a25.png)

1. Click **[!UICONTROL Approve and Close]**.

   >[!NOTE]
   >
   >The form must be approved to be used on landing pages.

   ![](assets/image2014-9-15-12-3a27-3a53.png)

   >[!NOTE]
   >
   >Remember to [approve the landing page draft](/help/marketo/product-docs/demand-generation/landing-pages/understanding-landing-pages/approve-unapprove-or-delete-a-landing-page.md) created by the form changes.

   Piece of cake! Check out what a person would see if they came back to the same form:

   ![](assets/image2014-9-15-12-3a28-3a12.png)

   >[!TIP]
   >
   >You can direct the click of the button to the asset by setting the form follow-up page to the file's URL.
