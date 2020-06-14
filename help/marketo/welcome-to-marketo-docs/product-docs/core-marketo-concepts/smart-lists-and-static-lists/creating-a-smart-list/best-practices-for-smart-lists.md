---
unique-page-id: 7512524
description: Best Practices for Smart Lists - Marketo Docs - Product Documentation
title: Best Practices for Smart Lists
---

# Best Practices for Smart Lists {#best-practices-for-smart-lists}

Best Practices for Smart Lists - Marketo Docs - Product Documentation

Smart lists are the most powerful query tool in the marketing universe. They find the people you are looking for with magical speed and ease.

To make them easy to work with and optimize performance, we've created a list of good practices. Enjoy!

>[!NOTE]
>
>**Each customer is different.** The bigger the database, the more processing happens. The more activities you have stored, the longer it takes to search through them.
>
>If you are experiencing slowness, try the tips below. If the issue persists, contact Marketo [Support](http://support.marketo.com).

##### 1. Limit history - History filters (a.k.a. Activity filters) are among the most resource intensive, time-consuming operations. If you must use them, try to limit the date range to as short as possible, which would reduce the searchable data set. {#bestpracticesforsmartlists-limithistory-historyfilters(a.k.a.activityfilters)areamongthemostresourceintensive-time-consumingoperations.ifyoumustusethem-trytolimitthedaterangetoasshortaspossible-whichwouldreducethesearchabledataset.}

##### 2. Limit nested smart lists - When creating a new smart list, limit the amount of "Member of Smart List" filters used. This is called nesting smart lists, and each smart list referenced will increase processing time. Instead, either reference static lists or utilize [segmentation](../../../../../welcome-to-marketo-docs/product-docs/personalization/segmentation-and-snippets/segmentation/create-a-segmentation.md). {#bestpracticesforsmartlists-limitnestedsmartlists-whencreatinganewsmartlist-limittheamountof"memberofsmartlist"filtersused.thisiscallednestingsmartlists-andeachsmartlistreferencedwillincreaseprocessingtime.instead-eitherreferencestaticlistsorutilizesegment}

##### 3. Use positive over negative operators - While "not" filters are available, they have to search the entire data set in your instance, which can be extremely time-consuming. Positive "is" filters are able to leverage more effective search algorithms. {#bestpracticesforsmartlists-usepositiveovernegativeoperators-while"not"filtersareavailable-theyhavetosearchtheentiredatasetinyourinstance-whichcanbeextremelytime-consuming.positive"is"filtersareabletoleveragemoreeffectivesearchalgorithms.}

##### 4. Avoid "contains" - If you only have partial data, "starts with" qualifiers will yield much faster results than "contains." "Is" will run even faster. Avoid using "contains" with multi-values; the two together can slow down a campaign even further. {#bestpracticesforsmartlists-avoid"contains"-ifyouonlyhavepartialdata-"startswith"qualifierswillyieldmuchfasterresultsthan"contains.""is"willrunevenfaster.avoidusing"contains"withmulti-values-thetwotogethercanslowdownacampaignevenfurther.}

##### 5. Use Random Sample by itself - Random Sample is a special filter. Use it by itself to put your people into pre-made lists. Then just use "Member of List" to make your smart list super fast. Random Sample will NOT work with nested Smart Lists. The Random Sample filter will not work if it is the Smart List being referenced for the “Member of Smart List” filter.  {#bestpracticesforsmartlists-userandomsamplebyitself-randomsampleisaspecialfilter.useitbyitselftoputyourpeopleintopre-madelists.thenjustuse"memberoflist"tomakeyoursmartlistsuperfast.randomsamplewillnotworkwithnestedsmartlists.therandomsamplefilterwillnotwor}

##### 6. Be thrifty with inactivity filters - Filters like "Not Filled Out Form" can be really useful, but require much more processing power. {#bestpracticesforsmartlists-bethriftywithinactivityfilters-filterslike"notfilledoutform"canbereallyuseful-butrequiremuchmoreprocessingpower.}

##### 7. Be thrifty with pasting in multiple values - Multi-select is designed for pasting in dozens or possibly hundreds of values. Put in too many, however, and it will slow way down. {#bestpracticesforsmartlists-bethriftywithpastinginmultiplevalues-multi-selectisdesignedforpastingindozensorpossiblyhundredsofvalues.putintoomany-however-anditwillslowwaydown.}

##### 8. Be thrifty when adding constraints - These are the tiny details of a rule and related values. The more constraints you add, the slower the processing time. {#bestpracticesforsmartlists-bethriftywhenaddingconstraints-thesearethetinydetailsofaruleandrelatedvalues.themoreconstraintsyouadd-theslowertheprocessingtime.}

##### 9. Simplify your campaigns - 100+ independent rules (we have seen it!) are obviously going to take some time to process. Keep it simple and you will notice the speed gains - plus it will be easier for you to understand. {#bestpracticesforsmartlists-simplifyyourcampaigns-100+independentrules(wehaveseenit!)areobviouslygoingtotakesometimetoprocess.keepitsimpleandyouwillnoticethespeedgains-plusitwillbeeasierforyoutounderstand.}

##### 10. Include the @ symbol before the domain name when using the Email Address filter - This makes it use a faster query. Example: Instead of using *email contains 'somedomain.com*', use *email contains '@somedomain.com*.' If you're using multiple email address with "contains," ALL of them must start with "@." {#bestpracticesforsmartlists-includethe@symbolbeforethedomainnamewhenusingtheemailaddressfilter-thismakesituseafasterquery.example-insteadofusingemailcontains'somedomain.com'-useemailcontains'@somedomain.com.'ifyou'reusingmultipleemailaddresswith"contains-"}

>[!TIP]
>
>Marketo can be used in many ways and certain techniques are better for you and your business. Consider [Marketo professional services](http://pages2.marketo.com/72-hour-survival-guide.html) to make your investment shine.

