---
layout: archive
title: "Teaching"
permalink: /teaching/
header:
  image: /assets/images/grande_ecaille.jpg
  image_description: "La grande écaille, Mont-Blanc, France"
  caption: "La grande écaille, SE Mont-Blanc, France - ©Antoine Mercier"
author_profile: true
---

## Courses and tutorial classes: 

### L3
* Lecture course - Géologie structurale : les roches de failles.
* Tutorial classe - Cartographie et SIG : projet "les risques naturels en France".

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
