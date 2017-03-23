---

layout: post
title:  "Error handling where the first action doesn’t equal a log message"
categories: Microflows
prio: 2
rulenumber: 25
rulename: NoLogMessageInErrorHandling
ruleset: Error handling

---

**Why**
Error handling without logging will make it very hard to debug errors for this case. You won't see anything in the log.

![25.png]({{ site.url }}/assets/25.png)

**How to fix**
Add a log message in custom error handling. Make sure to check the Add latest stacktrace box as well. ”