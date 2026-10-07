---
unique-page-id: 2359494
description: Learn how to run subject line A/B tests in email programs. Test different subject lines and choose a winner by performance.
title: Use "Subject Line" A/B Testing
exl-id: 99c2415e-886b-44fa-ba96-5d4ec371753e
feature: Email Programs, A/B Testing
TQID: 'https://experienceleague.adobe.com/jF6mldDXXbl9YOWTOfwgvxvbh-QmIH6sqnnELOv1lxQ'
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
# Use "Subject Line" A/B Testing {#use-subject-line-a-b-testing}

You can easily A/B test your emails. One of the most common tests is the **[!UICONTROL Subject Line]** test.

>[!PREREQUISITES]
>
>[Add an A/B Test](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/add-an-a-b-test.md)

1. Under the **[!UICONTROL Email tile]**, with your email selected, click **[!UICONTROL Add A/B Test]**.

![](assets/image2014-9-12-15-3a6-3a2.png)

1. The test editor window will open. Enter one or more new subject lines.

   >[!NOTE]
   >
   >Choice **A** will pre-populate with the information contained in the selected email.

   ![](assets/image2014-9-12-15-3a9-3a14.png)

   >[!TIP]
   >
   >You can click on the **+** to add more subject lines.

1. Use the slider to choose what percentage of the audience you want to receive your A/B test and click **[!UICONTROL Next]**.

   ![](assets/image2014-9-12-15-3a10-3a4.png)

   >[!CAUTION]
   >
   >**We recommend you avoid setting the sample size to 100%**. If you are using a static list, setting the sample size to 100% would send the email to everyone in the audience and the winner would go to no one. If you are using a smart list, setting the sample size to 100% would send the email to everyone in the audience _at that time_. And when the email program runs again at a later date, any new people who qualify for the smart list would also receive the email since they are now included in the audience.

   >[!NOTE]
   >
   >The different subject variations will take even parts of the Test Sample Size selected.

   Okay, we're almost there. Now we need to [define the A/B test winner criteria](/help/marketo/product-docs/email-marketing/email-programs/email-program-actions/email-test-a-b-test/define-the-a-b-test-winner-criteria.md).
