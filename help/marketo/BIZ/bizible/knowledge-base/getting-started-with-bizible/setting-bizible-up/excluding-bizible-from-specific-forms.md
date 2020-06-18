---
unique-page-id: 18874783
description: Excluding Bizible from Specific Forms - Bizible - Product Documentation
title: Excluding Bizible from Specific Forms
---

# Excluding Bizible from Specific Forms {#excluding-bizible-from-specific-forms}

Excluding Bizible from Specific Forms - Bizible - Product Documentation

By default, Bizible attaches to all forms on your site. However, not all form submissions necessarily should be tracked or included in an attribution model. This is because not all form fills are considered to be "good." An example of this is an unsubscribe page/form. Furthermore, login forms typically are not tracked as it would dilute the attribution model.&nbsp;

#### How to Add Bizible-exclude Code:  {#excludingbiziblefromspecificforms-howtoaddbizible-excludecode}

`To prevent Bizible from tracking specific forms, simply add "Bizible-Exclude" as a 'class' on your form. The code is as follows:`

* `<form id="myForm" action="/Home/TestPage" method="POST" class="Bizible-Exclude">`*
