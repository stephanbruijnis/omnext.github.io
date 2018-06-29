---

layout: post
title:  "Anonymous users should have path to user"
categories: Datamodel
prio: 1
rulenumber: ##
rulename: AnonymousPathToUser
ruleset: Security

---

**Why**
Security: Anonymous users can be anyone with a link to your application, the specific entities (Specialisations of FileDocument, PendingLink and ForgotPassword) usually contain sensitve information and may cause serious security breaches and leaks of your application and data.


![MxAdmin.PNG]({{ site.url }}/assets/AnonymousPathToUser.PNG)

**How to fix**
Entity access should have [System.owner='[%CurrentUser%]'] or a path to = $currentUser] when anonymous users is configured in project and anonymous users have access to these entities: any specialization of System.FileDocument, Deeplink.PendingLink and ForgotPassword.ForgotPassword (preferable no access to the ForgotPassword persistable entities and fix it with NPE's)
