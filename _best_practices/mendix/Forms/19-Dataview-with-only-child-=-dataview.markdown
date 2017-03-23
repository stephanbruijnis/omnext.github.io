---

layout: post
title:  "Dataview with only child = dataview"
categories: Forms
prio: 4
rulenumber: 19
rulename: DataviewWithOnlyADataview
ruleset: Performance

---

**Why**
Multiple nested dataviews instead of using a N-deep path creates unnecessary calls to from your form to the Mendix Runtime. This will effect page loading performance negatively.

![19.png](https://github.com/Omnext/omnext.github.io/blob/master/assets/19.png)

**How to fix**
Just put in the child dataview directly and retrieve over multiple associations