---

layout: post
title:  "Inform users about errors, all at once"
categories: User experience
prio: 
rulenumber: 49
rulename: 
ruleset: 

---

**Why**
Gebruikers zitten er niet op te wachten dat server side validaties één voor één worden teruggegeven. Werkt daarom met een boolean: IsGevalideerd, loop alle validaties af en bepaal aan het eind van de validatie MF o.b.v. IsGevalideerd of er wel of niet verder gegaan wordt met de MF.

![49.png]({{ site.url }}/assets/49.png)

**How to fix**
