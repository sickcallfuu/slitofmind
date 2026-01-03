---
title: "{{ replace .Name "-" " " | title }}"
date: "{{ (.Date | time.AsTime).Format "2006-01-02" }}"
lastmod:
categories:
tags:
rss_ignore: false
draft: false
---

