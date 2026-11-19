---
description: Description.
title: Email Open Tracking at Person Level
feature: Email Setup
TQID: 'https://experienceleague.adobe.com/kF-5V-G6-xr3uV-NQBTmFNfhQnk-r-RYt-v0HvJ-4Go'
product_v2:
  - id: b27e5950-9033-45ac-9f86-eb22e567f615
    internal-label: Marketo Engage
feature_v2:
  - id: a7170d27-32ab-462b-a333-269abc654483
    internal-label: Smart Campaigns
  - id: d1d0a9cd-295d-4976-8c39-ddae266f240e
    internal-label: Administration
  - id: b3b8a63f-51fc-40f6-a7d2-a31c5d49fb45
    internal-label: Configuration
subfeature_v2:
  - id: a03c57fb-0705-4a0d-b463-bbc931d4cefa
    internal-label: Email setup
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
---
# Email Open Tracking at Person Level {#email-open-tracking-at-person-level}

Control whether Adobe Marketo Engage tracks email opens and clicks for each person. Person-level Email Tracking Overrides lets you apply a default at the instance level, then change that default for individual people. Open tracking and click tracking are controlled independently.

Use this feature when your privacy requirements or organizational policies require consent before email engagement is tracked.

>[!IMPORTANT]
> 
>This feature provides controls that can help support your compliance obligations; it does not determine which laws apply or which people need to provide consent. Work with your legal and privacy teams to decide how to configure tracking and how to collect and retain consent.

## How tracking decisions work

Three settings work together:

| Setting | Level | What it does |
|---|---|---|
| **Person-level Email Tracking Overrides** | Instance | Turns the feature on or off. When off, Marketo Engage ignores the instance default and person override fields and uses normal tracking behavior. |
| **Email Tracking Off by Default** | Instance | Sets the default for open and click tracking. When disabled, tracking is on by default. When enabled, tracking is off by default. |
| **Override Open Tracking Default** and **Override Click Tracking Default** | Person | Boolean person fields. A value of `true` applies the opposite of the instance default for that type of tracking. A value of `false` or an empty value follows the instance default. |

The override fields do not mean "opt in" or "opt out" by themselves. **`true` always means "the opposite of the instance default."**

### Tracking decision table

Marketo Engage applies this decision separately to email opens and email clicks.

| Feature | Instance default | Person override is `false` or empty | Person override is `true` |
|---|---|---|---|
| On | Tracking on by default | Tracked | Not tracked |
| On | Tracking off by default | Not tracked | Tracked |
| Off | Not applicable | Normal tracking; override and default are ignored | Normal tracking; override and default are ignored |

### Example

Suppose the feature is on and the instance default is tracking on. A person has **Override Open Tracking Default** set to `true`, while **Override Click Tracking Default** is empty. Marketo Engage does not track that person's email opens, but it continues to track their email clicks.

## Choose a tracking model

Choose the model that matches your consent and privacy requirements before enabling the feature or populating person fields.

| Model | Instance default | Set the override to `true` when | Typical use |
|---|---|---|---|
| Opt-out | Tracking on by default | A person objects to tracking | Track most people, but stop tracking for people who object. |
| Opt-in (consent) | Tracking off by default | A person gives consent to tracking | Require consent before tracking, including for recipients covered by applicable CNIL or Garante guidance. |

>[!CAUTION]
> 
>Choose your model before you populate the override fields, and avoid changing the instance default afterward. Because `true` means "the opposite of the default," changing the default reverses the effect of every existing override value. For example, switching from tracking on by default to tracking off by default can cause people who previously objected to tracking to become tracked. If you must change the default, update the override values for all affected people before the change takes effect.

## Turn on the feature

Person-level Email Tracking Overrides is off by default. To enable it, contact Adobe Customer Support and specify:

1. That you want to enable **Person-level Email Tracking Overrides**.
2. Whether the instance default should be **tracking on by default** or **tracking off by default**.

>[!TIP]
> 
>Populate the override fields for existing people before you ask Adobe to enable the feature. This helps ensure the intended tracking behavior applies from the first email prepared after enablement.

## Set override values for people

The override fields are Boolean person fields. Set them using the method that fits your workflow:

| Method | Notes |
|---|---|
| Change Data Value flow step | Use a smart campaign to set a field when a person meets your criteria, such as submitting a consent checkbox on a form. |
| Forms | Map a checkbox or hidden field on a Marketo Engage form to the person field. |
| List import | Include the field as a column in the import file. |
| REST API | Use the API field names `overrideOpenTrackingDefault` and `overrideClickTrackingDefault`. |

Set each field according to the person's consent. If your consent language treats opens and clicks separately, configure each field independently.

## What changes in the email

When Marketo Engage decides not to track a person, it changes the email content it sends to that person.

| Tracking turned off for | What changes | What still works |
|---|---|---|
| Opens | The email does not include the open-tracking pixel. No **Open Email** activity is recorded. | Other email functionality, including click tracking if it remains enabled. |
| Clicks | Links go directly to their destinations instead of through the Marketo Engage tracking domain. The hidden tracking link is not added. No **Click Email** activity is recorded. | Unsubscribe links, the email footer opt-out link, `list-unsubscribe`, and **View as Web Page** links continue to work. Using these links does not record a **Click Email** activity. |

## Which emails are affected

| Email type | Overrides applied? |
|---|---|
| Batch emails, such as emails sent from a batch smart campaign or an email program | Yes |
| Trigger emails, such as emails sent from a trigger smart campaign | Yes |
| Emails with A/B tests or champion/challenger variants | Yes. Tracking is decided separately for each person, regardless of the variant they receive. |
| View as Web Page | Yes. The web version follows the person's current settings. A change can take up to one hour to appear. |
| Operational emails | No. They follow normal tracking behavior. |
| Sample (test) emails | No. They follow normal tracking behavior. |
| Email previews | No change. Previews are not tracked. |
| Alert emails | No change. Alerts are not tracked. |
| SMS messages | No. This feature applies to email only. |

## When Marketo Engage makes the tracking decision

Marketo Engage reads a person's override values when it prepares the email for sending.

- **Scheduled or delayed delivery:** If an email is prepared now and delivered later—for example, with Head Start or Recipient Time Zone—the values at preparation time apply. A change made after preparation does not change that email.
- **Already-delivered emails:** Changing a person's override does not change emails they have already received. Clicks on links in previously sent emails can still be tracked if those links were prepared with tracking enabled.
- **Future emails:** A change applies to emails Marketo Engage prepares after the change.

If a person withdraws consent, update their override value as soon as possible so the change applies to the next email prepared for them.

## Impact on reporting, Smart Lists, and scoring

When Marketo Engage does not track a person, it does not record **Open Email** or **Click Email** activities for them. As a result:

- **Smart Campaigns:** Filters and triggers such as **Opened Email** and **Clicked Link in Email** do not match or fire for that person when the corresponding activity is not tracked.
- **Reports and dashboards:** Email open rates, click rates, and link performance reflect tracked people only. Engagement metrics can decrease as more people are not tracked.
- **Scoring and program success:** Rules and program success steps based on opens or clicks do not apply to people whose activities are not tracked. Review these rules so people are not scored or advanced unfairly.
- **Web activity association:** When click tracking is off, email links do not carry the Marketo Engage tracking token. If the person is not already known to Munchkin, a website visit from that email is not associated with the person through the link.

**Sent, delivered, bounced, and unsubscribed activities are not affected.**

## How this works with other tracking settings

Person-level Email Tracking Overrides can turn tracking off for a person. It does not turn tracking on when another setting has already disabled it. For example, links marked with the `mktNoTrack` class remain untracked even when the person's settings allow click tracking.

## Turn off the feature

If Adobe disables the feature for your instance, emails prepared after the change return to normal tracking behavior. The override values remain on person records but are ignored. If the feature is enabled again later, the stored values apply again.

## Frequently asked questions

### Can I track opens but not clicks for a person, or the reverse?

Yes. Open and click tracking are decided independently. Set only the override field for the type of tracking you want to change.

### Does this feature stop me from sending emails to a person?

No. It controls tracking only. To stop sending marketing emails to a person, use the existing unsubscribe and consent features.

### Do people who are not tracked still see working unsubscribe links?

Yes. Unsubscribe links and **View as Web Page** links continue to work for all people.

### Why does a person who opted out still have a Click Email activity?

They may have clicked a link in an email that was prepared before their override value changed. Changes apply to emails prepared after the change.

### Do I need to change my email templates?

No. Marketo Engage applies the tracking decision when it builds each email. You do not need to change your templates or emails.

## Related articles

- Understanding Operational Emails
- Change Data Value Flow Step
- Disable Tracking for a Link in an Email
- Head Start
- Recipient Time Zone
- Email Performance Report
