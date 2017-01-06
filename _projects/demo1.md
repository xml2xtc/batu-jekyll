---
title: Demo 1
categories:
- advertising
position: 0
layout: default
thumbnail_image: "/images/thumbnail1.jpg"
---

{% for image in page.images %}
  <img src="{{ image.path }}" class="{{ image.class }}">
{% endfor %}
