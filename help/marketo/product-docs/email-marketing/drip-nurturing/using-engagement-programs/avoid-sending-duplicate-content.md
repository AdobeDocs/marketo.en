---
unique-page-id: 10096409
description: Learn about scenarios that prevent or allow duplicate emails in engagement programs. Use program membership and CEE rules to avoid repeats.
title: Avoid Sending Duplicate Content
exl-id: fd7118e8-6e34-4973-8aa5-effb774447fd
feature: Engagement Programs
TQID: https://experienceleague.adobe.com/vJ0HguG6ad182v-Jkf-0DF6zAosaJG5B-me3ghxnYIM
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: e64968b2-4ee5-47f9-8cae-0588f184b9eb
    internal-label: Programs
---
# Avoid Sending Duplicate Content {#avoid-sending-duplicate-content}

Have you ever received the same email twice? Annoying, is not it?

Here are seven possible scenarios and results to be aware of to prevent sending someone the same message twice with engagement programs.

## Scenarios {#scenarios}

| The email is sent from |The person is |Person gets email |
|---|---|---|
| A campaign in a separate, stand-alone, default program  |Not a member of the default program |Yes |
| A campaign in a separate, stand-alone, default program |A member of the default program |No |
| A campaign within a default program that's triggered from a cast within the **same** CEE program |A member of the default program |No |
| A campaign within a default program that's triggered from a cast within the **same** CEE program |Not a member of the default program |Yes |
| A campaign within a default program that's triggered from a cast within a **different** CEE program |A member of the default program |No |
| A campaign within a default program that's triggered from a cast within a **different** CEE program |Not a member of the default program |Yes |
| A **different** CEE program using a smart stream |A member of both CEE programs |No |
