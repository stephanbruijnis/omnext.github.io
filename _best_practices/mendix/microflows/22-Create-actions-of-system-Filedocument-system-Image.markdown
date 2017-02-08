---

layout: post
title:  "Create actions of system.Filedocument, system.Image"
categories: microflows
prio: 3
rulenumber: 22
rulename: AvoidCreateFileDocOrImage
ruleset: Security

---

**Why**
Avoid creating filedocument or images. Because your security options on both objects are very limited

**How to fix**
Inherit always from system domain objects before using them. In that way you can configure your own security
