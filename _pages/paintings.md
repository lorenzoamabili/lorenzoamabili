---
layout: archive
title: "Paintings"
permalink: /paintings/
author_profile: true
---

{% include base_path %}

{% for post in site.paintings reversed %}
  {% include archive-single.html %}
{% endfor %}
