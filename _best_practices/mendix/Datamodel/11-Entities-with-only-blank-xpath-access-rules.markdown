---

layout: post
title:  "Entities with only blank xpath access rules"
categories: Datamodel
prio: 2
rulenumber: 11
rulename: 
ruleset: Security

---

**Why**
Entity does only have blank access rules. Most of the times this means the configuration is not correct, not secure. Even if you put the XPath on your forms, this will not be secure.

![11.png](https://github.com/Omnext/omnext.github.io/blob/master/assets/11.png)

**How to fix**
Make sure every entity has contrained access rules, and if not, make sure that's correct.