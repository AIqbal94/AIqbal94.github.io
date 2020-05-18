---
layout: post
title: "Remove zero sized files from Linux"
date: 2020-01-30
published: true
---

To remove multiple zero sized files from current directory in linux at once use;

```
find . -size 0 -delete
```
