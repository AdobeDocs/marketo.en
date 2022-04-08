---
unique-page-id: 10096409
description: Avoid Sending Duplicate Content - Marketo Docs - Product Documentation
title: Avoid Sending Duplicate Content
exl-id: fd7118e8-6e34-4973-8aa5-effb774447fd
---
# Avoid Sending Duplicate Content {#avoid-sending-duplicate-content}

Have you ever received the same email twice? Annoying, isn't it?

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
