---
layout: page
title: Projects
permalink: /projects/
description: Open-source tools for understanding data and improving machine learning systems.
nav: true
nav_order: 3
---
<div class="project-list">
{% assign sorted_projects = site.projects | sort: 'importance' %}
{% for project in sorted_projects %}
<a class="project-card" href="{{ project.url | relative_url }}">
  <span class="eyebrow">{{ project.category }}</span>
  <h2>{{ project.title }} <span aria-hidden="true">↗</span></h2>
  <p>{{ project.description }}</p>
</a>
{% endfor %}
</div>
