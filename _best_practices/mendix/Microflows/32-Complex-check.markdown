---

layout: post
title:  "Complex check"
categories: Microflows
prio: 4
rulenumber: 32
rulename: ExcessiveIfThenStatements
ruleset: Convention

---

**Why**
Using long if-then-else construction within one single split will make it harder to 'read' the microflow without having to click activities for details.

![32.png](https://github.com/Omnext/omnext.github.io/blob/master/assets/32.png)

**How to fix**
Please split the split into multiple splits for read-ability and documentation.