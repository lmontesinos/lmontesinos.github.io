---
layout: page
title: "Projects"
permalink: /projects/
eyebrow: "Selected work"
subtitle: "A curated selection of projects representing my current and recent research directions."
---

<div class="grid two">
{% for project in site.projects %}
  <article class="project-card">
    <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
    <p>{{ project.summary }}</p>
    {% if project.keywords %}
      <ul class="tag-list">
        {% for keyword in project.keywords %}
          <li>{{ keyword }}</li>
        {% endfor %}
      </ul>
    {% endif %}
  </article>
{% endfor %}
</div>
