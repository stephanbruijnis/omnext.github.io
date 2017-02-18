---

layout: post
title:  "Don't save for UI on change events"
categories: Forms
prio: 
rulenumber: 51
rulename: 
ruleset: 

---

**Why**
Als een microflow (bijv. onchange) aangeroepen wordt in een dataview, gebruik dan geen opslaan actie. De gebruiker wil zijn acties kunnen annuleren door op de ‘Cancel / annuleer’ knop te klikken.

![51.png]({{ site.url }}/assets/51.png)

**How to fix**
