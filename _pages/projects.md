---
layout: page
title: Research
permalink: /projects/
description: X-ray timing, compact objects, stellar populations, and nearby galaxies.
nav: true
nav_order: 2
display_categories: [current, research]
horizontal: true
---

<!-- Project cards are generated from the `_projects` collection. -->
<div class="projects">
{% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
{% endfor %}
</div>
