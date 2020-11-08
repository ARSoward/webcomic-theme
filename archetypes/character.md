---
name: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
image: "img/{{ lower (replace .Name "-" "_")   | title }}-character.jpg"
description: "enter a short bio for your character here."
draft: false
---