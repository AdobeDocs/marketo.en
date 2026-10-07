---
unique-page-id: 2359504
description: Learn how to run from-address A/B tests. Test different sender addresses and choose a winner by performance.
title: Use "From Address" A/B Testing
exl-id: 83e2994b-39ec-4c88-87b0-8f2501ea2bf1
feature: Email Programs, A/B Testing
TQID: 'https://experienceleague.adobe.com/rerG-Wyn1X53QQBDXFwyg74uEOznGcYcBis9EwX4vQU'
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
  - id: 69a7f8d6-582c-5b66-841e-32cf07fd164c
    internal-label: A/B Testing
  - id: c2dbad80-0f5c-4d96-a798-2a65f93b8721
    internal-label: Assets
subfeature_v2:
  - id: c0f0afc1-a5a8-4b01-8b43-cc38f9169499
    internal-label: Email programs
---
# Use "[!UICONTROL From Address]" A/B Testing {#use-from-address-a-b-testing}

You can easily A/B test your emails. One interesting test is the **[!UICONTROL From Address]** test. Here's how to set it up.

>[!PREREQUISITES]
>
>[Add an A/B Test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md)

1. Under the **[!UICONTROL Email]** tile, with your email selected, click on **[!UICONTROL Add A/B Test]**.

   ![](assets/image2014-9-12-15-3a32-3a8.png)

1. A new window opens, select **[!UICONTROL From Address]** for **[!UICONTROL Test Type]**.

   ![](assets/image2014-9-12-15-3a32-3a22.png)

1. If you have previous test information (like a subject test), you can safely click **[!UICONTROL Reset Test]**.

   ![](assets/image2014-9-12-15-3a32-3a28.png)

1. Enter the second **[!UICONTROL From Address]** information you want to test.

   >[!NOTE]
   >
   >Choice A will pre-populate with the information contained in the selected email.

   ![](assets/image2014-9-12-15-3a32-3a34.png)

   >[!TIP]
   >
   >You can click on the **+** to add as many From Addresses as you'd like.

1. Use the slider to choose what percentage of the audience you want in your A/B test and click **[!UICONTROL Next]**.

   ![](assets/image2014-9-12-15-3a33-3a41.png)

   >[!NOTE]
   >
   >The different variations will send to equal portions of the chosen Test Sample Size.

   >[!CAUTION]
   >
   >**We recommend you avoid setting the sample size to 100%**. If you are using a static list, setting the sample size to 100% sends the email to everyone in the audience and the winner goes to no one. If you are using a **smart** list, setting the sample size to 100% sends the email to everyone in the audience _at that time_. When the email program runs again at a later date, any new people who qualify for the smart list will also receive the email since they're now included in the audience.

   OK, we're almost there. Now we need to [define the A/B test winner criteria](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/define-the-a-b-test-winner-criteria.md).
