---
layout: archive
title: "Code"
permalink: /code/
author_profile: true
classes: wide
---

{% for post in site.code reversed %}
  {% include archive-single.html %}
{% endfor %}
