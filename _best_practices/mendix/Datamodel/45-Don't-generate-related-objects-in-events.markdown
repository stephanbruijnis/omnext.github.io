---

layout: post
title:  "Don't generate related objects in events"
categories: Datamodel
prio: 
rulenumber: 45
rulename: 
ruleset: 

---

**Why**
Het is onwenselijk om after create van een parent object de child objects er bij te genereren of om dit te doen in een microflow die het scherm openen met de geneste views. Gebruiker daarvoor altijd de GetOrCreate constructies

![45.png]({{ site.url }}/assets/45.png)

**How to fix**
