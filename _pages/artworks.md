---
layout: archive
title: "Artworks"
permalink: /artworks/
author_profile: true
---

{% include base_path %}

{% for post in site.artworks reversed %}
  {% include archive-single.html %}
{% endfor %}
