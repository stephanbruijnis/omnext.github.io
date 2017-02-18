---

layout: post
title:  "Retrieve first instead of list for empty checks"
categories: Microflows
prio: 
rulenumber: 46
rulename: 
ruleset: 

---

**Why**
Gebruik retrieve first in microflows als het doel enkel is om te checken of een object aanwezig is. Veel gemaakte fout is om een lijst te retrieven en dan de lijst op != empty te checken

![46.png]({{ site.url }}/assets/46.png)

**How to fix**
