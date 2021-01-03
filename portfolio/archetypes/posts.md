---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
author: David Novogrodsky
year: "{{ dateFormat "2006" .Date }}"
month: "{{ dateFormat "2006/01" .Date }}"
categories:
- Test
- Test02
tags:
- test01
- test02
---
Lorem is where the summary is now.

<!-- more -->

The rest of the post.
