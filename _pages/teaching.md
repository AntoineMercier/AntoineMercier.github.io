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
### Structural geology and tectonics
* Lecture course (L3) - Géologie structurale : les roches de failles.
* Tutorial classes (L2) - Tectonique et géomorphologie.

### GIS and cartography
* Tutorial classe (L3) - Cartographie et SIG : projet "les risques naturels en France".
* Tutorial classe (M1) - Introduction aux systèmes d'informations géographiques.

## Online tutorials for students: 
{% include base_path %}
{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
