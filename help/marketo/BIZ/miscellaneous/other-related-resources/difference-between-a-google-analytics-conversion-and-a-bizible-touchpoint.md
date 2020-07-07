---
unique-page-id: 18874648
description: Difference between a Google Analytics Conversion and a Bizible Touchpoint - Bizible - Product Documentation
title: Difference between a Google Analytics Conversion and a Bizible Touchpoint
---

# Difference between a Google Analytics Conversion and a Bizible Touchpoint {#difference-between-a-google-analytics-conversion-and-a-bizible-touchpoint}

Difference between a Google Analytics Conversion and a Bizible Touchpoint - Bizible - Product Documentation

Learn what a Google Analytics (GA) goal is and how it differentiates from a Bizible Touchpoint.

**What are Google Analytic's Conversions?**

Google Analytics conversions are completely determined by how a marketer or a web developer codes 'goal' completions on a particular website. Goals, according to Google could be thought of as "making a purchase (for an ecommerce site), completing a game level (for a mobile gaming app), or submitting a contact information form (for a marketing or lead generation site)." Most of the time, marketers see goals/conversions as someone filling out an informational form.

However, goals can't be coded to manage very specific behavior. Rather, there are Goal Types that a web developer can configure. Below are some of those examples:

<table> 
 <colgroup> 
  <col> 
  <col> 
  <col> 
 </colgroup> 
 <tbody> 
  <tr> 
   <td><strong>Goal Type</strong></td> 
   <td><p><strong>Description</strong></p></td> 
   <td><strong>Example</strong></td> 
  </tr> 
  <tr> 
   <td><p>Destination</p></td> 
   <td>A specific location loads</td> 
   <td><em>Thank you for registering!</em> web page or app screen</td> 
  </tr> 
  <tr> 
   <td>Duration</td> 
   <td>Sessions that lasts a specific amount of time or longer</td> 
   <td>10 minutes or longer spent on a support site</td> 
  </tr> 
  <tr> 
   <td>Pages/Screens per session</td> 
   <td>A user views a specific number of pages or screens</td> 
   <td>5 pages or screens have been loaded</td> 
  </tr> 
  <tr> 
   <td>Event</td> 
   <td>An action defined as an Event is triggered</td> 
   <td>Social recommendation, video play, ad click</td> 
  </tr> 
 </tbody> 
</table>

Most marketers configure their conversions as "Destination Goals," meaning that they usually create a thank you page after a form to consider that a formal conversion.

What this means, is that Google will consider Thank You page views as a conversion. From a Google Analytics standpoint, this is a realization most marketers are OK with.

However, Bizible Touchpoints act very differently.

**How do Bizible Touchpoints differ?**

Bizible's JavaScript tracks session data and form submissions on all forms of a particular site. There's no need to code goals from a Bizible standpoint. This process is automatic. For form submissions, Bizible reports a form completion every time an anonymous user fills out information fields on a particular form and also clicks on the form submission button. Bizible doesn't need a thank you page to record the form submission.

Bizible will create a form touchpoint when:

* A lead/contact that is associated to those conversions appear in your CRM.
* The Bizible JS is present on the web pages containing the form.
* A form is submitted within a 30 min session.

Bizible will ignore Destination Google Analytic conversions when:

* A bot submits forms on a website (these bots usually don't make it into a client's CRM).
* A user submits more forms after their first form submission. Bizible will only push the first conversion from that session.
* The user clicks on the form submission multiple times. Bizible will only consider the first form submission.
* The user re-loads the thank you page multiple times.
* The user is using any Ad Blocking tools.

As you can see there are fundamental differences between what GA and Bizible consider a conversion to be. Therefore, it will be very likely that the number of conversions and the number of form Touchpoints will differ.

