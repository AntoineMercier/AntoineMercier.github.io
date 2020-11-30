---
layout: archive
title: "Publications"
permalink: /publications/
header:
  image: /assets/images/image_pyramides.jpg
  image_description: "Les Pyramides calcaires  - Val Veny; Italy"
  caption: "Les Pyramides calcaires  - Val Veny, Italy - ©Philippe Hervé Leloup"
author_profile: true
---
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
---
