---

layout: post
title:  "Use batches for large list processing"
categories: Microflows
prio: 
rulenumber: 54
rulename: 
ruleset: 

---

**Why**
Overweeg het gebruik van batches als er in één microflow veel objecten worden opgeslagen. Dat kan door de objecten toe te voegen aan een lijst en aan het einde van de microflow in één keer de lijst te committen. Mendix zal dat dan optimaliseren. Afhankelijk van welke functionaliteiten er uitgevoerd moeten worden, is het een best practice om met lijsten van 2.000 tot maximaal 10.000 objecten te werken. Hoe zwaarder de actie die uitgevoerd wordt, hoe lager het maximum. Hieronder wordt een voorbeeld getoond hoe dit kan worden toegepast.

![54.png]({{ site.url }}/assets/54.png)

**How to fix**
