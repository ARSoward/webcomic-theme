---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
image: "img/{{ lower (replace .Name "-" "_")   | title }}-chapter.jpg"
draft: false
---
