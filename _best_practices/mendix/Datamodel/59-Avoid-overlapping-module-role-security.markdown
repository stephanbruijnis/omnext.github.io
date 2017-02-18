---

layout: post
title:  "Avoid overlapping module role security"
categories: Datamodel
prio: 
rulenumber: 59
rulename: 
ruleset: 

---

**Why**
Userroles stapelen. Vaak zit er een gelaagd security niveau in userroles. Userrole X mag alles wat Userrole Y mag + nog wat meer. Los dit op met module roles die je kunt stabelen in user roles.

![59.png]({{ site.url }}/assets/59.png)

**How to fix**
