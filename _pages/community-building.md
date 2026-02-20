---
layout: page
title: Community Building
permalink: /community-building/
description: Initiatives and programs that grow the Cryptolets community
nav: true
nav_order: 4
---

<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
