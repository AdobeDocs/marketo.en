---
unique-page-id: 1900577
description: Create an Email Script Token - Marketo Docs - Product Documentation
title: Create an Email Script Token
---

# Create an Email Script Token {#create-an-email-script-token}

For advanced developers, you can use  [Velocity scripts](http://velocity.apache.org/engine/1.7/user-guide.html) in your emails. Here's how to do it.

1. Go to **Marketing Activities**.

   ![](assets/ma.png)

1. Find and select any program (Event, Default, or Engagement, etc).

   ![](assets/image2014-9-17-22-3a21-3a24.png)

1. Under the **My Tokens** tab, drag in an **Email Script** token.

   ![](assets/image2014-9-17-22-3a21-3a29.png)

1. Name your email script token and **click to edit** its content.

   ![](assets/image2014-9-17-22-3a21-3a46.png)

1. Use the tree on the right to drag in **Person, Opportunity**, or **Custom Object** tokens.

   ![](assets/five-2.png)

   >[!NOTE]
   >
   >When accessing an array (opportunity or custom object) you are limited to the most recent 10 items associated to the person.

1. Notice the token becomes checked/active after you drag it into the script editor.

   ![](assets/image2014-9-17-22-3a22-3a33.png)

   >[!NOTE]
   >
   >**Reminder**
   >
   >
   >If you are typing in tokens free-form ensure to check/activate all corresponding tokens in the tree or they will be treated as plain text and won't work.

1. Write your script in Velocity. Here are some useful resources:

    * [Marketo Developers Email Scripting Documentation](http://developers.marketo.com/email-scripting/)
    * [Velocity User Guide](http://velocity.apache.org/engine/devel/user-guide.html)
    * [Velocity Reference Guide](http://velocity.apache.org/engine/devel/vtl-reference-guide.html)
    * [Velocity Tools Javadoc](http://velocity.apache.org/tools/releases/2.0/javadoc/index.html)

1. Once your script is completed, click **Save**.

   ![](assets/image2014-9-17-22-3a23-3a1.png)

1. Click **Save** one more time.

   ![](assets/image2014-9-17-22-3a23-3a13.png)

Now you can use this token in your emails. It will run the script every time an email is sent.

>[!MORELIKETHIS]
>
>* [Add an Email Script Token to Your Email](add-an-email-script-token-to-your-email.md)
>

