---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
archives: "{{ dateFormat "2006" now }}"
tags: []
author: John SMITH
description: John SMITH's article
images:
- img/logo.png
---
