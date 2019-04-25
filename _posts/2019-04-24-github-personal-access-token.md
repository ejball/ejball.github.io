---
title: GitHub personal access token
categories: code
tags: tools
---

Today I struggled a bit trying to use a **GitHub personal access token** to push a commit to a GitHub Enterprise repository. I managed to get it to work right before I left for the day, which is always nice.

* make sure the repository URL uses HTTPS not SSH
* make sure the personal access token has `repo` permission
* use the personal access token as the username with an empty password
* make sure the user has write access to the repository
