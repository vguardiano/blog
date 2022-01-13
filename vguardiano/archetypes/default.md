---
title: "{{ replace .Name "-" " " | title }}"
description:
date: {{ .Date | time.Format ":date_full" }}
image:
math: true
license:
hidden: false
comments: true
draft: false
---
