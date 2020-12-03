---
layout: archive
title: "Teaching"
permalink: /teaching/
classes: wide
header:
  image: /assets/images/iceland_solheimajokull.jpg
  image_description: "Sólheimajökull glacier, Iceland"
  caption: "Sólheimajökull glacier, south Iceland - ©Antoine Mercier"
author_profile: true
---
## Courses and tutorial classes: 
### L3
* Lecture course - Géologie structurale : les roches de failles.
* Tutorial classe - Cartographie et SIG : projet "les risques naturels en France".

## Online tutorials for students: 
{% include base_path %}
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
