---
unique-page-id: 11373011
description: Transitioning to Email Editor 2.0 - Marketo Docs - Product Documentation
title: Transitioning to Email Editor 2.0
---

# Transitioning to Email Editor 2.0 {#transitioning-to-email-editor}

As of the [June '19 release](../../../../release-notes/2016/release-notes-spring-16.md), all Marketo subscriptions have been transitioned to Email Editor 2.0. [Learn more](https://nation.marketo.com/docs/DOC-7038) about the Email Editor 1.0 deprecation.

Emails and email templates within your subscription should have a version number. The version can be found in the asset’s summary page.

![](assets/five-5.png)

##### By default, all of your existing emails and email templates will be marked as v1.0 if they were created either prior to the Spring ’16 Release, or after the release when Email Editor 2.0 is disabled. With Email Editor 2.0 now automatically enabled, you will see the following behavior: {#by-default-all-of-your-existing-emails-and-email-templates-will-be-marked-as-v-if-they-were-created-either-prior-to-the-spring-release-or-after-the-release-when-email-editor-is-disabled-with-email-editor-now-automatically-enabled-you-will-see-the-following-behavior}

* When you create a new email, the [Email Template Picker](email-template-picker-overview.md) will display and you'll be able to choose a v2.0 email template. 
* Whenever you create or edit an email with Email Editor 2.0, the resulting email will **always** be marked as v2.0 (even if you used a v1.0 email template).

##### If your subscription has v1.0 emails before the move to Email Editor 2.0, you will experience the following behavior based on the asset's current state: {#if-your-subscription-has-v-emails-before-the-move-to-email-editor-you-will-experience-the-following-behavior-based-on-the-assets-current-state}

**Approved** - Clicking “Edit Draft” will create a v2.0 draft of the approved email. If you then approve the v2.0 draft, the approved state of the email becomes v2.0 and there is no way to revert back to v1.0.  
**Draft** - Clicking “Edit Draft” will automatically mark that draft as v2.0. At this point, it will not be possible to discard and revert to v1.0 because there is no approved version of the asset.   
**Approved with Draft** - Clicking “Edit Draft” will then automatically mark that draft as v2.0. Because of this, there is also no way to revert the draft back to v1.0.

##### If your subscription has v1.0 email templates before the move to Email Editor 2.0, you will experience the following behavior: {#if-your-subscription-has-v-email-templates-before-the-move-to-email-editor-you-will-experience-the-following-behavior}

**Approved** - Clicking “Edit Draft” will create a v2.0 draft of the existing email template.   
**Draft** - Clicking “Edit Draft” will automatically mark that draft as v2.0. At this point, it would not be possible to discard and revert to v1.0 because there is no approved version of the asset.   
**Approved with Draft** - Clicking “Edit Draft” will automatically mark that draft as v2.0. Because of this, there is also no way to revert the draft back to v1.0.

##### If you approve an email template that was previously v1.0 (in any of the above states), you will see the following behavior: {#if-you-approve-an-email-template-that-was-previously-v-in-any-of-the-above-states-you-will-see-the-following-behavior}

For existing v1.0 emails that were using the (previously v1.0) template:  
**Approved v1.0 email** - A v2.0 draft will be created for this email, still using the newly approved v2.0 template. It will also receive any template changes.  
**Draft v1.0 email** - The draft will remain v1.0 until you click “Edit Draft." After that, it will be automatically marked as v2.0 and receive any template changes.  
**Approved with Draft v1.0 email** - The draft will remain v1.0 until you click “Edit Draft." After that, it will be automatically marked as v2.0 and receive any template changes.

For existing v2.0 emails that were using the (previously v1.0) template:  
**Approved v2.0 email** - A v2.0 draft will be created for this email, still “using” the newly approved template, and will receive any template changes.  
**Draft v2.0 email** - The draft will remain as is (v2.0) and receive any template changes.  
**Approved with Draft v2.0 email** - The draft will remain as is (v2.0) and receive any template changes.

>[!CAUTION]
>
>If you ever approve the v2.0 draft of a v1.0 email template, the template will become v2.0. There is **no way** to revert it back to v1.0.

##### Things to Note {#things-to-note}

* Approved emails are **never** changed.

* Approved email templates are **never** changed.

* In a few **rare** cases, a v1.0 Email can't be opened in Email Editor 2.0. If this occurs, discard the draft and contact Marketo Support.

>[!NOTE]
>
>**Related Articles**
>
>* [Email Editor 2.0 Overview](http://docs.marketo.com/display/docs/assets/email-editor-v2.0-overview)
>* [Email Template Syntax](email-template-syntax.md)
>

