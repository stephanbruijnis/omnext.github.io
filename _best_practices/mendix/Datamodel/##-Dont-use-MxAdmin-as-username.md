---

layout: post
title:  "Don't use MxAdmin as username for Administrator"
categories: Datamodel
prio: 3
rulenumber: ##
rulename: RenameMxAdmin
ruleset: Security

---

**Why**
Don't use a common username, such as Admin, MxAdmin or Administrator. This is likely to get hit by passive multi-host attacks just scanning. After several unsuccessful login attempts the user will be blocked and MxAdmin will be unavailable (even to the real Administrator) during that time window.

![MxAdmin.PNG]({{ site.url }}/assets/MxAdmin.PNG)

**How to fix**
Rename the Adminstrator username to something other than Admin or MxAdmin
