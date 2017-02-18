---

layout: post
title:  "Apply GetOrCreateMicroflows"
categories: Forms
prio: 
rulenumber: 44
rulename: 
ruleset: 

---

**Why**
Een best practice voor geneste dataviews waar mogelijk nog geen object voor aanwezig is zijn de GetOrCreate microflows. Die microflow retrieved bij bijvoorbeeld een persoon het adres uit associatie. Als die er is wordt die gereturned en anders wordt er een nieuw object gemaakt en gereturned.

![44.png]({{ site.url }}/assets/44.png)

**How to fix**
