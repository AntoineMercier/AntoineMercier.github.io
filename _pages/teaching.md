---
layout: archive
title: "Teaching"
permalink: /teaching/
header:
  image: /assets/images/grande_ecaille.jpg
  image_description: "La grande écaille  - Mont-Blanc ; France"
  caption: "La grande écaille, SE Mont-Blanc, France - ©Antoine Mercier"
author_profile: true
toc: true
toc_label: "Table of Contents"
toc_icon: "fas fa-hammer"
---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
