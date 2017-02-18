---

layout: post
title:  "Multiple dataviews with same datasource microflow within one form"
categories: Forms
prio: 3
rulenumber: 16
rulename: SameMicroflowUsedInForm
ruleset: Performance

---

**Why**
This will result in unnecessary call from your form to the Mendix Runtime. This will slow down the page loading.

![16.png]({{ site.url }}/assets/16.png)

**How to fix**
Restructure the form to avoid calling multiple times the same microflow