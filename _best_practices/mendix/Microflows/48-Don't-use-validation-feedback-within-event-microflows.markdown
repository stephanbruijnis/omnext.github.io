---

layout: post
title:  "Don't use validation feedback within event microflows"
categories: Microflows
prio: 
rulenumber: 48
rulename: 
ruleset: 

---

**Why**
Server side valideren gebeurt niet in events maar in microflows die als custom save buttons op views worden gezet. Gebruik subflows indien validaties herbruikbaar moeten zijn.

![48.png]({{ site.url }}/assets/48.png)

**How to fix**
