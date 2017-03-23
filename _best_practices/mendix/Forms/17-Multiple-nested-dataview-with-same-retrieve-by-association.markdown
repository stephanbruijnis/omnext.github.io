---

layout: post
title:  "Multiple nested dataview with same retrieve by association"
categories: Forms
prio: 3
rulenumber: 17
rulename: SameRetrieveByAssocUsedInForm
ruleset: Performance

---

**Why**
This will result in unnecessary call from your form to the Mendix Runtime. This will slow down the page loading.

![17.png]({{ site.url }}/assets/17.png)

**How to fix**
Restructure the form to avoid calling multiple times the same association