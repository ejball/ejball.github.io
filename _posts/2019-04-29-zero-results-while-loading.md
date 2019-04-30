---
title: Zero results while loading
categories: code
tags: ui
---

One of my pet peeves with user interface implementations is showing **zero results while loading**. Basically, when user interface is first loading, or while the app is working on a requested operation, we should be careful to not give the impression that there are zero search results, or that they have no data, or that the operation failed, etc. Sometimes the operation takes a while, sometimes the browser is slow, et cetera, and we should not mislead the user while they wait. I understand why it's often easier to write the code that way, and we might not even be able to see the misleading user interface on our fast development machines with high speed Internet connections, but we should take the time to get it right and avoid unnecessarily confusing or panicking the user.
