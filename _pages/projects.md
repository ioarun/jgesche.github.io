---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: false
---

<div class="grid__wrapper">
  {% for post in site.portfolio %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>