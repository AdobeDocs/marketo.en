---
unique-page-id: 10098134
description: Adding a Program to an Engagement Program Stream - Marketo Docs - Product Documentation
title: Adding a Program to an Engagement Program Stream
---

# Adding a Program to an Engagement Program Stream {#adding-a-program-to-an-engagement-program-stream}

Adding a Program to an Engagement Program Stream - Marketo Docs - Product Documentation

#### Why use a nested program in an engagement program stream? {#why-use-a-nested-program-in-an-engagement-program-stream}

It's easy to add an email to a stream in an engagement program, and it works fine. However, if your business needs are more complex, it may make sense to place the email inside a program. For example, you might want to:

* Send an email to a subgroup of people in the stream
* Send *different* emails to subgroups within the stream
* Include landing pages, forms, or other assets in the nurture
* Enable multi-touch attribution
* Add extra flow steps, such as alert emails

#### What happens when you use a program in a stream? {#what-happens-when-you-use-a-program-in-a-stream}

When using a nested program, the decision to send an email to a person is based on the program membership and program ID.

* If you're not a member of a program, you will receive any emails that are part of the program once 
* If you're a member of the program, you won't receive the email
* If you are no longer a member but received the email earlier through that program, you won't receive the email

When you use a program in a stream, it doesn't matter if you’ve received that specific email before. As long as the email was not sent out before *in that specific program*, you can receive it again.

It can get tricky mixing emails and programs in an engagement program. You might want to use one or the other.

>[!TIP]
>
>Be sure to use a **Member of Engagement Program** filter in your smart list.

#### What happens to people who don't meet the smart list criteria? {#what-happens-to-people-who-dont-meet-the-smart-list-criteria}

In the event that someone is filtered out of the smart list of a nested program’s smart campaign, they do not move on to the next piece of content during the current cast. They will move on to the next piece of content in the stream for the *following* cast.

#### What does a nested program contain? {#what-does-a-nested-program-contain}

A well-designed nested program contains emails, reports, and smart campaigns. It makes sense to keep these together.

The email you use can live in the program, in a different program, or even in the Design Studio. Where it lives will depend on how you want to use it.

Reporting changes with email location. So, for example, if the email is in the Design Studio, in the Email Performance Report, all metrics are shown in one line - the different casts are combined. However, in the Engagement Stream Performance Report, the different sends are displayed separately.

>[!CAUTION]
>
>If you want to resend something, it's safest to create a new program and smart campaign.

>[!NOTE]
>
>**Related Articles**
>
>* [Add Content to a Stream](add-content-to-a-stream.md)
>* [Understanding Programs](../../../../product-docs/core-marketo-concepts/programs/creating-programs/understanding-programs.md)
>

