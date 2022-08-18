---
description: Setting up reCAPTCHA v3 - Marketo Docs - Product Documentation
title: Setting up reCAPTCHA v3
hide: yes
hidefromtoc: yes
exl-id: 235a2688-59a8-4827-a929-a07f3ae06988
---
# Setting up reCAPTCHA v3 {#setting-up-recaptcha-v3}

Intro Text

## Initial reCAPTCHA v3 setup {#initial-recaptcha-v3-setup}

Text: Describe v3 - the following steps are performed outside of Marketo Engage.

1. Go to [https://www.google.com/recaptcha/about/](https://www.google.com/recaptcha/about/){target="_blank"} and click on v3 Admin Console.

1. Sign in/sign up with a Google account.

1. Click the Create button (+ sign) to create a new key.

1. Create a label to identify the key is to be used for Marketo Engage.

1. Choose type **reCAPTCHA v3**. Marketo Engage does not currently support reCAPTCHA v2.

1. Add each domain the Marketo Engage subscription uses. Domains not set here will return errors on forms where reCAPTCHA is enabled.

   * 123-ABC-456.mktoweb.com
   * app-pod.marketo.com
   * any landing page domain and alias configured in the subscription

1. Set an owner and additional email address that should receive any alerts about this service.

1. Accept the reCAPTCHA Terms of Service.

1. Click **Submit**.

>[!NOTE]
>
>Keep the site key and secret key handy for the Marketo Engage configuration.

## Setting up CAPTCHA in Marketo Engage {#setting-up-captcha-in-marketo-engage}

1. In Marketo, click **Admin**.

   ![](assets/setting-up-recaptcha-v3-1.png)

1. Select **CAPTCHA** in the tree.

   ![](assets/setting-up-recaptcha-v3-2.png)

1. Click **Edit** on CAPTCHA settings.

   ![](assets/setting-up-recaptcha-v3-3.png)

1. Click the CAPTCHA drop-down and choose reCAPTCHA v3.

   ![](assets/setting-up-recaptcha-v3-4.png)

1. Insert the Secret Key and Site Key. Click **Save** when done.

   ![](assets/setting-up-recaptcha-v3-5.png)
