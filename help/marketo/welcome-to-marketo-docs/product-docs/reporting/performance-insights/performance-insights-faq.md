---
unique-page-id: 12979858
description: Performance Insights FAQ - Marketo Docs - Product Documentation
title: Performance Insights FAQ
---

# Performance Insights FAQ {#performance-insights-faq}

Performance Insights FAQ - Marketo Docs - Product Documentation

### What's in this article? {#what-s-in-this-article}

[What is the definition of “success” in the Engagement tab?](#performanceinsightsfaq-whatisthedefinitionof“success”intheengagementtab?)  
[Will MPI work with any CRM?](#performanceinsightsfaq-willmpiworkwithanycrm?)  
[I do not have any other Marketing Analytics products (ARB, RCE, RCA, Program Analysis). Will MPI work for me?](#performanceinsightsfaq-idonothaveanyothermarketinganalyticsproducts(arb-rce-rca-programanalysis).willmpiworkforme?)  
[RCA shows me program performance data as well. Is there a difference between the data shown in MPI and RCA?](#performanceinsightsfaq-rcashowsmeprogramperformancedataaswell.isthereadifferencebetweenthedatashowninmpiandrca?)  
[I don’t want some of my programs (e.g. Operational) to show up in MPI. How do I control the visibility of specific programs?](#performanceinsightsfaq-idon’twantsomeofmyprograms(e.g.operational)toshowupinmpi.howdoicontrolthevisibilityofspecificprograms?)  
[I am running a multi-channel campaign for a new product launch. How can I view the performance for this campaign across all the different channels in one place?](#performanceinsightsfaq-iamrunningamulti-channelcampaignforanewproductlaunch.howcaniviewtheperformanceforthiscampaignacrossallthedifferentchannelsinoneplace?)  
[Will I have access to attribution settings if I do not have RCA?](#performanceinsightsfaq-willihaveaccesstoattributionsettingsifidonothaverca?)  
[I get an alert in MPI when I log in telling me that my attribution settings are incorrect. What’s wrong?](#performanceinsightsfaq-igetanalertinmpiwhenilogintellingmethatmyattributionsettingsareincorrect.what’swrong?)  
[Why am I missing some opportunities in MPI?](#performanceinsightsfaq-whyamimissingsomeopportunitiesinmpi?)  
[Why do I not see Custom Fields, Opportunity Type and ABM filters on the Engagement dashboard?](#performanceinsightsfaq-whydoinotseecustomfields-opportunitytypeandabmfiltersontheengagementdashboard?)  
[I want to use a custom Salesforce Opportunity field for revenue reporting instead of the standard Salesforce Opportunity Amount field. Will MPI allow me to do that?](#performanceinsightsfaq-iwanttouseacustomsalesforceopportunityfieldforrevenuereportinginsteadofthestandardsalesforceopportunityamountfield.willmpiallowmetodothat?)  
[If I don’t use opportunities, can I still use MPI?](#performanceinsightsfaq-ifidon’tuseopportunities-canistillusempi?)  
[Can I measure the success of account-based strategies in MPI?](#performanceinsightsfaq-canimeasurethesuccessofaccount-basedstrategiesinmpi?)  
[Is attribution instantly available when I purchase MPI?](#performanceinsightsfaq-isattributioninstantlyavailablewhenipurchasempi?)  
[What do I have to do to set up attribution?](#performanceinsightsfaq-whatdoihavetodotosetupattribution?)  
[What's the difference between MPI and the Program Analyzer?](#performanceinsightsfaq-what'sthedifferencebetweenmpiandtheprogramanalyzer?)  
[What's the difference between MPI and the Advanced Report Builder?](#performanceinsightsfaq-what'sthedifferencebetweenmpiandtheadvancedreportbuilder?)  
[What happened to the "Previous Year" option in Contribution's date filter?](#performanceinsightsfaq-whathappenedtothe"previousyear"optionincontribution'sdatefilter?)

#### What is the definition of “success” in the Engagement tab? {#performanceinsightsfaq-whatisthedefinitionof“success”intheengagementtab?}

Success is a measure of meaningful interaction in Marketo. The purpose of a program is to create a meaningful interaction with the person or prospect. Success is marked when a person reaches the status that achieves that goal. It can be attending a webinar, clicking a link in an email, or filling out a web form. Success varies depending on the program channel.

>[!NOTE]
>
>**Example**
>
>In a webinar program, there can be multiple statuses, such as: Invited, Registered, and Attended. Invited or Registered aren't meaningful interactions because people don't actually watch the webinar. Attended is considered success in this case.

#### Will MPI work with any CRM? {#performanceinsightsfaq-willmpiworkwithanycrm?}

Yes. Technically, MPI does not directly interact with the CRM for data synchronization. MPI utilizes data stored in the Marketo Analytics Data Warehouse. Since the CRM sync happens in the Lead Management application, any Marketo-supported CRM integrated with the Lead Management application will show data correctly. However, the CRM opportunity fields do need to be mapped correctly to the Marketo opportunity fields.

#### I do not have any other Marketing Analytics products (ARB, RCE, RCA, Program Analysis). Will MPI work for me? {#performanceinsightsfaq-idonothaveanyothermarketinganalyticsproducts(arb-rce-rca-programanalysis).willmpiworkforme?}

MPI is an independent add-on to the Lead Management application. It does not require the use of any other analytics products.

#### RCA shows me program performance data as well. Is there a difference between the data shown in MPI and RCA? {#performanceinsightsfaq-rcashowsmeprogramperformancedataaswell.isthereadifferencebetweenthedatashowninmpiandrca?}

No. MPI sources data from the same data warehouse as RCA. Therefore, you will not see any data differences between the two. RCA allows you to create your own reports on the fly. MPI gives you access to easy-to-understand visual dashboards.

#### I don’t want some of my programs (e.g. Operational) to show up in MPI. How do I control the visibility of specific programs? {#performanceinsightsfaq-idon’twantsomeofmyprograms(e.g.operational)toshowupinmpi.howdoicontrolthevisibilityofspecificprograms?}

You can control the visibility of your programs by setting the Analytics behavior of your programs to Operational. This will cause the program to be excluded from analytics calculations.

>[!NOTE]
>
>Learn more about setting analytics behavior [here](http://docs.marketo.com/display/public/DOCS/Edit+Analytics+Behavior+Settings).

#### I am running a multi-channel campaign for a new product launch. How can I view the performance for this campaign across all the different channels in one place? {#performanceinsightsfaq-iamrunningamulti-channelcampaignforanewproductlaunch.howcaniviewtheperformanceforthiscampaignacrossallthedifferentchannelsinoneplace?}

We recommend that, for programs part of such a campaign, you utilize program tags. Program tags are automatically synced to MPI, and you can filter them in all MPI dashboards to view your multi-channel campaign performance.

#### Will I have access to attribution settings if I do not have RCA? {#performanceinsightsfaq-willihaveaccesstoattributionsettingsifidonothaverca?}

You get access to attribution settings if you have MPI, regardless of whether you have RCA or not.

#### I get an alert in MPI when I log in telling me that my attribution settings are incorrect. What’s wrong? {#performanceinsightsfaq-igetanalertinmpiwhenilogintellingmethatmyattributionsettingsareincorrect.what’swrong?}

MPI calculates whether or not all your opportunities are being included in analytics. If not, you will be prompted to consider changing your attribution settings (Explicit, Implicit, Hybrid) to include more opportunities.

You may also be missing opportunities due to Program Cost missing in your programs. Please review the Analytics behavior of your programs. They can be:

1. Default - The default behavior is the program would be included in MPI ONLY if there is at least one period cost, even one with zero dollars assigned.
1. Inclusive - This option will ensure that the program is available in MPI regardless of whether or not you've included a period cost.
1. [Operational](http://docs.marketo.com/display/DOCS/Best+Practice%3A+How+to+Organize+your+Programs#BestPractice:HowtoOrganizeyourPrograms-OperationalPrograms) - This option results in the program not showing up in MPI.

>[!NOTE]
>
>Period Cost **has** to be set up for Success and New Names reporting in the Engagement dashboard. This dashboard utilizes Period Cost data to aggregate successes and new names. If Period Cost is not set up, the engagement dashboard will not report correctly regardless of the Analytics behavior settings above.

#### Why am I missing some opportunities in MPI? {#performanceinsightsfaq-whyamimissingsomeopportunitiesinmpi?}

Two key reasons you may be missing opportunities in MPI are:

1. Attribution setting is set to Explicit but opportunities do not have Contact Roles assigned
1. Period cost is not included in your programs

MPI calculates whether or not all your opportunities are being included in analytics. If not, you will be prompted to consider changing your attribution settings (Explicit, Implicit, Hybrid) to include more opportunities.

You may also be missing opportunities due to Program Cost missing in your programs. The alert will come up but does not point you to which programs are missing costs. Please review your program setup to include costs, to ensure all your programs and opportunities are included in MPI.

#### Why do I not see Custom Fields, Opportunity Type and ABM filters on the Engagement dashboard? {#performanceinsightsfaq-whydoinotseecustomfields-opportunitytypeandabmfiltersontheengagementdashboard?}

Custom Fields, Opportunity Type and ABM Filters are all attributes related to an opportunity. The Engagement dashboard allows you to measure your engagement and lead acquisition whether or not they are associated with an opportunity. Since the Engagement dashboard does not take opportunity into consideration, Custom Fields, Opportunity Type and ABM Filters do not apply.

#### I want to use a custom Salesforce Opportunity field for revenue reporting instead of the standard Salesforce Opportunity Amount field. Will MPI allow me to do that? {#performanceinsightsfaq-iwanttouseacustomsalesforceopportunityfieldforrevenuereportinginsteadofthestandardsalesforceopportunityamountfield.willmpiallowmetodothat?}

Yes. [Marketo Support](http://docs.marketo.com/cdn-cgi/l/email-protection#d9aaaca9a9b6abad99b4b8abb2bcadb6f7bab6b4) is able to remap Marketo’s Opportunity Amount field to a custom Salesforce Opportunity field as long as the field type is currency. Since MPI points to the Marketo Opportunity amount field, MPI can use the data from the remapped custom Salesforce field.

>[!NOTE]
>
>After remapping, MPI will show the data going forward. The historic amount will not be changed.

#### If I don’t use opportunities, can I still use MPI? {#performanceinsightsfaq-ifidon’tuseopportunities-canistillusempi?}

MPI is designed to allow you to measure program performance from the top of the funnel down to revenue impact. If you do not use opportunities, you'll still be able to:

* View performance of your nurture programs for audience engagement.
* View performance of your lead acquisition programs.
* View performance of multi-channel campaigns through program tags.
* See audience engagement trends for the last 12 months.
* Save and export performance data in PowerPoint.

#### Can I measure the success of account-based strategies in MPI? {#performanceinsightsfaq-canimeasurethesuccessofaccount-basedstrategiesinmpi?}

Yes. MPI integrates with [Marketo ABM](http://docs.marketo.com/display/DOCS/Account+Based+Marketing+Overview) to pull ABM account lists into MPI seamlessly. You can use the ABM Account List filter to choose the desired ABM list to filter data by.

#### Is attribution instantly available when I purchase MPI? {#performanceinsightsfaq-isattributioninstantlyavailablewhenipurchasempi?}

The Marketo Attribution capabilities are available to our customers when they purchase MPI. However, [proper setup](http://docs.marketo.com/x/mRPG) is required to ensure that opportunities and program data flow correctly into MPI.

#### What do I have to do to set up attribution? {#performanceinsightsfaq-whatdoihavetodotosetupattribution?}

1. Opportunity setup

    1. Ensure opportunities are synced with your CRM
    1. If your Attribution settings are set to Explicit, ensure contact roles on opportunities are populated
    1. We recommend changing Attribution setting to Hybrid
    1. Program Setup

        1. Include program cost in your programs
        1. Review the analytics behavior to indicate whether a program should be included in analytics
        1. Set the success criteria for every channel you have
        1. Tie Person to Programs

            1. Make sure Acquisition Program and Acquisition Date have been set for each person in your database in order for First Touch Attribution to work.
            1. Ensure your programs are setting success states for people in your database

>[!TIP]
>
>All setup steps required are detailed in [this article](http://docs.marketo.com/x/mRPG).

#### What's the difference between MPI and the Program Analyzer? {#performanceinsightsfaq-what'sthedifferencebetweenmpiandtheprogramanalyzer?}

The Program Analyzer allows you to compare your programs across as many as four measures. MPI allows you to analyze your channel and program contribution towards a chosen metric such as Success, New Opportunities Created, etc. It also allows you to view the 12-month channel trend based on one specific metric you've chosen.

#### What's the difference between MPI and the Advanced Report Builder? {#performanceinsightsfaq-what'sthedifferencebetweenmpiandtheadvancedreportbuilder?}

The Advanced Report Builder (sometimes referred to as RCE), is designed for self-serve (or ad hoc) reporting, typically done by Marketing Operations. MPI is designed to give Marketing leaders and marketers one-click access to performance analysis. Minimal setup is required.

#### What happened to the "Previous Year" option in Contribution's date filter? {#performanceinsightsfaq-whathappenedtothe"previousyear"optionincontribution'sdatefilter?}

We have temporarily removed the “Previous Year” selection. You still have the option of viewing the entire year’s performance data by using the Custom Date Range selection.
