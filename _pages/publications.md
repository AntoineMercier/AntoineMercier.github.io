---
layout: archive
title: "Publications"
permalink: /publications/
header:
  image: /assets/images/image_pyramides.jpg
  image_description: "Les Pyramides calcaires  - Val Veny; Italy"
  aption: "Photo credit: ©Antoine Mercier"
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
