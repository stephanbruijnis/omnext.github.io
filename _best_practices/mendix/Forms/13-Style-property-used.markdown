---

layout: post
title:  "Style property used"
categories: Forms
prio: 5
rulenumber: 13
rulename: StylePropertyUsed
ruleset: Maintainability

---

**Why**
Try to avoid using the style property because this will make the life of your UI designer a lot more complicated as it will be harder to overrule there styles from CSS file level.

![13.png]({{ site.url }}/assets/13.png)

**How to fix**
Use generic classes instead with are defined by the theme