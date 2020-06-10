---
layout: default
title: "Skills"
menu_item: "skills"
---
<div class="ui three column stackable centered grid skills">
  {% for skill in site.data.skills %}
    <div class="ui column">
      <img class="ui tiny image centered skill" src="{{ skill.image_path }}" alt="{{ skill.name }}" title="{{ skill.name }}">
    </div>
  {% endfor %}
</div>
