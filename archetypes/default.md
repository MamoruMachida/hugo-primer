---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
categories:
tags:
keywords:
archives:
- "{{ dateFormat "2006-01" .Date }}"
---
