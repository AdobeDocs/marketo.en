---
title: understanding-my-tokens
description: Understanding My Tokens
---

# Understanding My Tokens

<br>&nbsp;

My Tokens are custom variables that you can create and use in your programs or campaign folders. They look like this: `{{_my.Name of Token_}}`

## Examples

* `{{my.Event Date}}`
* `{{my.Webinar Speaker}}`

To access and create My Tokens, select your program or campaign folder and go to the My Tokens tab. Drag and drop any token onto your Local Tokens canvas.

   ![Image One](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-1.png)

>[!CAUTION]
>
>Names of My Tokens can't be changed after they've been saved, so choose carefully.

>[!NOTE]
>
>My Tokens will not resolve when sending an email from Sales Insight on either Microsoft Dynamics or Salesforce; only standard tokens will populate (Lead, Company, etc.). Default values for tokens will work, however.

>[!NOTE]
>
>Link tokens won't work in text-only emails.

## Nesting Tokens

When you make a new token, it can be referenced by other objects in the tree. You can override global variables at lower levels in the tree. There's a naming structure for where the token was created for easy management.

* **Local Token:** The token was created directly in that program or folder.
* **[Overridden Token:](/help/sky/override-an-inherited-my-token.md)** The token was inherited, but an exception was made in this program or folder.
* **Inherited Token:** The token was created up the tree somewhere in a higher-level program or folder.

You can find these three types under the [!UICONTROL **My Tokens**] tab in your program or campaign folder.

   ![Image Two](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-2.png)

Moving programs and folders affects tokens, too. Always check to make sure that references aren't broken during the move.

>[!NOTE]
>
>If the email sent from an engagement program is a child email of a default program (i.e., not local to your engagement program), any My Tokens used in the email are resolved from the default program in which the child email resides.

## Token Usage

Select any token, then click the usage icon in the top right corner to see a list of assets that contain that token.

   ![Image Three](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-3.png)

   ![Image Four](/help/sky/assets/my-tokens/understanding-my-tokens/understanding-my-tokens-4.png)

**Deep Dive**

Learn more about each of the My Tokens:

* [CRM Campaign](/help/sky/my-token-crm-campaign.md)
* [Date](/help/sky/my-token-date.md)
* [Calendar File](/help/sky/my-token-calendar-file.md)
* [Image](/help/sky/my-token-image.md)
* [Link](/help/sky/my-token-link.md)
* [Number](/help/sky/my-token-number.md)
* [Rich Text](/help/sky/my-token-rich-text.md)
* [Score](/help/sky/my-token-score.md)
* [Email Script](/help/sky/my-token-email-script.md)
* [Text](/help/sky/my-token-text.md)
