---
layout: page
permalink: /gallery
title: Gallery
---

{% for photo in site.data.gallery %}
<img src="{{photo.photo_url | absolute_url }}" class="align-center" alt="{{photo.caption}}">

---

{% endfor %}
