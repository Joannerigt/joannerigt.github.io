---
layout: default
title: "Skills"
menu_item: "skills"
---
<div class="skills">
  {% for skill in site.data.skills %}
    <img class="skill" src="{{ skill.image_path }}" alt="{{ skill.name }}">
  {% endfor %}
</div>
