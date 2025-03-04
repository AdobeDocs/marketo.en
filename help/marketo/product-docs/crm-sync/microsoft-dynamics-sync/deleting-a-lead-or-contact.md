---
unique-page-id: 45417322
description: Deleting a Lead or Contact - Marketo Docs - Product Documentation
title: Deleting a Lead or Contact
exl-id: d561b424-6a2b-4abe-b9bd-81eb23f1a25b
feature: Microsoft Dynamics
---
# Deleting a Lead or Contact {#deleting-a-lead-or-contact}

There a few things to know when it comes to deleting leads/contacts in Microsoft Dynamics.

* Marketo Engage doesn't automatically delete people just because leads were deleted in Dynamics. Rather, a field "Microsoft is Deleted" flag is set to true. You can trigger off this field to delete the record in Marketo if desired.

* "Delete Person" flow action: This only deletes a person in Marketo (an option to also delete them in Dynamics is not available).

* If a lead is deleted in Marketo (but not in Dynamics) and is updated in Dynamics after that, it would create a new person in Marketo (same email address, new person ID).

* If a lead is deleted in Dynamics (but not in Marketo) and then subsequently runs through the "Sync Person to Microsoft" flow action, it would create a new lead in Dynamics.
