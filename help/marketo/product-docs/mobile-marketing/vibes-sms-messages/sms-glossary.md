---
description: SMS Glossary - Marketo Docs - Product Documentation
title: SMS Glossary
feature: Mobile Marketing
---
# SMS Glossary {#sms-glossary}

Below are some common terms you'll encounter when using Vibes SMS messages with Marketo Engage.

<table>
<thead>
  <tr>
    <th>Term</th>
    <th>Definition</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Acquisition Campaign</td>
    <td>A campaign made to acquire new subscribers to your subscription lists. A subscriber can be added to an acquisition campaign through a Marketo webform or by texting a keyword.</td>
  </tr>
  <tr>
    <td>Campaign Manager</td>
    <td>Found in the Vibes platform, Campaign Manager is where you can set up a subscription list and acquisiton campaign. Users with a full Vibes platform license have access to additional campaign types.</td>
  </tr>
  <tr>
    <td>Company Key</td>
    <td>The company_key is a unique alphanumeric identifier for your platform account. If you have multiple company accounts in the Vibes platform (such as child accounts), you may have multiple company_keys. Each instance of Marketo Engage may be mapped to only one Vibes company_key.</td>
  </tr>
  <tr>
    <td>CTA (call to action)</td>
    <td>Digital or physical signage or verbal script for acquiring subscribers into a recurring text message program or subscription list. Can be placed online, on social media, in emails, in print, etc.</td>
  </tr>
  <tr>
    <td>Custom Short Domain</td>
    <td>If you're using the Vibes link shortener, the shortened URL will, by default, appear under the Vibes short URL: https://vbs.cm/xxxxxx. A custom short domain is a domain unique to your brand. <a href="https://developer-platform.vibes.com/docs/creating-a-custom-short-domain">Learn more about custom short domains</a>.<p>
    This only applies to messages sent from the Vibes platform, specifically the acquisition campaign messages and short code default messages.<p>
    The Marketo URL shortener is recommended in order to have click data in your Marketo program.</td>
  </tr>
  <tr>
    <td>Default Messages</td>
    <td>Mandatory messages for the short code to reply to HELP, STOP, and unrecognized message requests.</td>
  </tr>
  <tr>
    <td>Disconnect</td>
    <td>Disconnects are a form of opt-out due to the mobile number being removed from a carrier network. Reasons for a disconnect include: an account has been fully closed, a prepaid account ran out of funds, or the number was removed from the carrier network for other unknown reasons. Mobile numbers that are disconnected and not ported to another mobile carrier are unsubscribed from all subscription lists in the Vibes platform.</td>
  </tr>
  <tr>
    <td>Double Opt-in</td>
    <td>A method of acquisition that requires a potential subscriber to confirm their consent to being added to a subscription list with a response command, like "Y" or their zip code. Using a double opt-in prompt can help you comply with state and federal text messaging guidelines.</td>
  </tr>
  <tr>
    <td>Event</td>
    <td>An event is a defined occurrence that can be submitted to the Vibes platform and used to trigger API-triggered actions, including message sends. Each event contains data specific to the event, including an event_type, which is used to determine which API-triggered message campaign it corresponds with. The Event API can be triggered via Webhook in Marketo Engage. Learn more with our <a href="https://developer-platform.vibes.com/reference/event-api">Event API reference</a>.</td>
  </tr>
  <tr>
    <td>Keyword</td>
    <td>A short word or alphanumeric string sent by the consumer to the short code to initiate a mobile experience.</td>
  </tr>
  <tr>
    <td>Long Code (10DLC)</td>
    <td>A sender ID from which two-way messages are sent between the brand and the consumer. US long codes are 10 numeric digits.</td>
  </tr>
  <tr>
    <td>MDN</td>
    <td>Mobile Directory Number, or a person's phone number. MDN and mobile phone numbers are not unique indentifiers in Marketo.</td>
  </tr>
  <tr>
    <td>Mobile Database</td>
    <td>The Mobile Database is the database where Vibes stores subscriber data. Each subscriber has a unique "person record," where the mobile number and any associated custom fields are populated.</td>
  </tr>
  <tr>
    <td>Participant</td>
    <td>A person who has one or more mobile interactions (such as sending a text message) with your mobile program, but has not subscribed to a subscription list.</td>
  </tr>
  <tr>
    <td>Person Record</td>
    <td>A person record is a collection of data for a specific mobile phone number. Each person record is also assigned a unique person_key for identification. Marketo IDs are linked to Vibes using the external_person_id field. Learn more about person records in <a href="https://developer-platform.vibes.com/reference/person-api">Vibes Person API documentation</a>.</td>
  </tr>
  <tr>
    <td>Short Code</td>
    <td>A sender ID from which two-way messages are sent between the brand and the consumer. US short codes are 5-6 numeric digits. Canadian short codes are 4-6 numeric digits. The Marketo LaunchPoint integration to Vibes supports one short code per instance.</td>
  </tr>
  <tr>
    <td>SMS</td>
    <td>Short Message Service. This is a message that includes only text.</td>
  </tr>
  <tr>
    <td>Subscription Lists</td>
    <td>A list of mobile numbers (and their corresponding person records) that provided consent to receive recurring messages from your program.</td>
  </tr>
  <tr>
    <td>Subscriber</td>
    <td>A mobile number that's subscribed to a subscription list(s).</td>
  </tr>
  <tr>
    <td>Vibes Platform</td>
    <td>The website you log in to to manage your campaigns. Go to <a href="https://nexus.us.vibes.com/">https://nexus.us.vibes.com/</a> to access the Vibes platform.</td>
  </tr>
</tbody>
</table>
