---

layout: post
title:  "Commit actions with a loop"
categories: Microflows
prio: 3
rulenumber: 29
rulename: AvoidCommitInLoop
ruleset: Performance

---

**Why**
Commiting objects within a loop will fire a SQL Update query for each iteration.  This will decrease performance.

![29.png](https://github.com/Omnext/omnext.github.io/blob/master/assets/29.png)

**How to fix**
Consider to commit the objects outside the loop. Therefor you have to add it to a list within the loop.