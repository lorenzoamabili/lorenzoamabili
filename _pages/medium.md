---
layout: archive
title: "Medium"
permalink: /medium/
author_profile: true
---

{% if author.medium %}
  You can also find my articles on <u><a href="{{author.medium}}">my Medium profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.medium reversed %}
  {% include archive-single.html %}
{% endfor %}
