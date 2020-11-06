---
title: "{{ delimit (.Name | title | slice | append "周一" "晴") " " }}"
date: {{ .Date }}
draft: false
disable_share: true
---
