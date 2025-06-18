---
solution: Marketo Engage
product: marketo
title: Spam Assassin
description: TEXT GOES HERE
level: Beginner, Intermediate
feature: Email Editor
hide: yes
hidefromtoc: yes
---
# Spam Assassin {#spam-assassin}

Using SpamAssassin in Marketo Engage, you can test your email content and see the likelihood of ISPs/Mailbox providers marking it as spam.

SpamAssassin analyzes your content and assigns a score based on various criteria. The lower the score, the better. It's important to maintain a low score as sending emails with a high score can negatively impact your overall deliverability.

## Access the Spam report {#access-the-spam-report}

1. From the Simulate screen, click the **Spam report** button.

SCREENSHOT

1. A spam report generates.

SCREENSHOT

1. Check the scores and descriptions for each item.

>[!IMPORTANT]
>
>If the overall score is higher than 5, your email may be blocked or marked as spam upon delivery.

1. If you consider the score to be too high, edit your content in the Email Designer and then re-run the Spam report until the score is where you want it to be.

SCREENSHOT

>[!NOTE]
>
>Spam score is derived via SpamAssassin, and rules are not owned by Adobe. More details about these rules can be found in the [SpamAssassin documentation](https://spamassassin.apache.org/#_blank). A full list of errors [can be seen here](https://spamassassin.apache.org/old/tests_3_0_x.html?utm_source=chatgpt.com).
