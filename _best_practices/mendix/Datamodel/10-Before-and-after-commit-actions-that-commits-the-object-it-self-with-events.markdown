---

layout: post
title:  "Before and after commit actions that commits the object it self with events"
categories: Datamodel
prio: 1
rulenumber: 10
rulename: AvoidCommitInBeforeAndAfterCommitAction
ruleset: Error

---

**Why**
Before and after commit actions that commits the object it self with event. The result is an infinity loop in the microflow

![10.png](https://github.com/Omnext/omnext.github.io/blob/master/assets/10.png)

**How to fix**
Don't commit in BCo actions and commit without events in ACo actions.