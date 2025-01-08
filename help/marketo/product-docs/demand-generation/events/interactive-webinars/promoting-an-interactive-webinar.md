---
description: Promoting an Interactive Webinar - Marketo Docs - Product Documentation
title: Promoting an Interactive Webinar
feature: Interactive Webinars
exl-id: d26f91ce-3a95-4247-9a52-085260bb15e8
---
# Promoting an Interactive Webinar {#promoting-an-interactive-webinar}

Promoting an Interactive Webinar is similar to promoting a partner webinar via Launchpoint. When creating an Interactive Webinar event program, you can add members either by running a campaign or importing members to the program. To check the members that have been added to the Interactive Webinars Event Program, click the **[!UICONTROL Members]** tab.

![](assets/promoting-an-interactive-webinar-1.png)

After the members have been added or imported, you can create an email campaign inside the Interactive Webinar event program to send an invitation to all the program members, and change their status to "invited" once the email has been delivered.

>[!NOTE]
>
>If you want to add a co-host or presenter as an audience member to the Interactive Webinar Event Program, you must use a different email ID for them, otherwise they'll receive a "this email is already registered" error.

The email can contain specific details of the program, as well as include a Landing Page URL that would redirect the recipient to a specific page where more information regarding the webinar (e.g., content, presenter info, etc.) can be added. This Landing Page can be created as a local asset in the Interactive Webinars Event Program.

You can solicit registration for this webinar by enabling a form on the Landing Page and linking the form clicks to enabled registration in the Interactive Webinar Event Program. A campaign can then be created that uses form submissions as a trigger and changes the Program Status from "invited" to "registered."

>[!NOTE]
>
>The transition from "invited" to "registered" is not automatic in Interactive Webinars, as there can be multiple triggers that create the transition.

Once a member has been in the "registered" program status in an Interactive Webinar Event Program, a registration is automatically made to the webinar created in Adobe Connect. Registration data such as First Name, Last Name and Email ID then gets transferred to Adobe Connect. This means that once the user joins the webinar as a participant, the information will be available to the presenter or host during the webinar.

Within a few minutes of registration, the Webinar URL for the member gets populated in the Members Tab. If you're not able to locate the column for Webinar URL, make sure that column has been added to your view. This is a personalized URL for each registered member to be able to enter the webinar at scheduled time without requiring any authentication. Tokens exchanged internally take care of the authentication for the members.

You can use the `{{member.webinar url}}` [token](/help/marketo/product-docs/demand-generation/landing-pages/personalizing-landing-pages/tokens-overview.md){target="_blank"} to include the Webinar URL to individual members in an email campaign to communicate that they've been registered in the event and to use the joining URL to enter the webinar at the scheduled time. Calendar tokens can be used in the same email campaign to ensure that the webinar schedule can be added to the members' calendars.

Links are available on the right side of the Overview tab in your Event Program to create a Landing Page as well as an email campaign. The rest of the promotions related to an event remain the same as partner webinars using the Launchpoint integration.

![](assets/promoting-an-interactive-webinar-2.png)

Interactive Webinars allows you to solicit registration before, during, or after a webinar. In all cases, you would simply need to share the Webinar URL with the lead. Clicking the link before the webinar begins sends them to a pre-webinar Landing Page. Clicking it during the webinar takes them to the webinar in progress. Clicking it after the webinar takes them to a recording of the webinar.

## Interactive Webinars Tokens {#interactive-webinars-tokens}

Use tokens to promote Interactive Webinars in emails and Landing Pages without having to manually add webinar details. This improves overall efficiency as any changes made to the webinar metadata (such as webinar title, start date, etc.) will automatically reflect in your assets.

![](assets/promoting-an-interactive-webinar-3.png)

**List of tokens**

<table><thead>
  <tr>
    <th>Token</th>
    <th>Definition</th>
  </tr></thead>
<tbody>
  <tr>
    <td>program.webinarCapacity</td>
    <td>The maximum number of attendees that can participate in the Interactive Webinar.</td>
  </tr>
  <tr>
    <td>program.webinarDuration</td>
    <td>The duration for which the Interactive Webinar is scheduled.</td>
  </tr>
  <tr>
    <td>program.webinarEndDate</td>
    <td>The end date for the scheduled Interactive Webinar.</td>
  </tr>
  <tr>
    <td>program.webinarEndTime</td>
    <td>The scheduled end time of the Interactive Webinar.</td>
  </tr>
  <tr>
    <td>program.webinarGenericURL</td>
    <td>The generic recording URL that can be shared with the audience post-webinar. This URL is not for attending the webinar live and does not track the activity of the audience.</td>
  </tr>
  <tr>
    <td>program.webinarLanguage</td>
    <td>The language in which the webinar is to be conducted.</td>
  </tr>
  <tr>
    <td>program.webinarStartDate</td>
    <td>The start date of the scheduled Interactive Webinar.</td>
  </tr>
  <tr>
    <td>program.webinarStartTime</td>
    <td>The scheduled start time of the Interactive Webinar.</td>
  </tr>
  <tr>
    <td>program.webinarTimezone</td>
    <td>The time zone in which the Interactive Webinar is scheduled.</td>
  </tr>
  <tr>
    <td>program.webinarTitle</td>
    <td>The title of the Interactive Webinar that is visible to the audience on the Webinar Entry Screens.</td>
  </tr>
</tbody></table>
