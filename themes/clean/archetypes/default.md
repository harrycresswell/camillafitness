---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
slug: "{{ replace .Name "-" "-" | markdownify }}"
expiryDate:
subtitle: 
---