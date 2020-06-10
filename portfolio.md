---
layout: default
title: "Portfolio"
menu_item: "portfolio"
---


<div class="ui three column stackable doubling centered grid portfolio">
  {% for item in site.categories.portfolio %}
  <a href="{{ item.url | relative_url }}">
    <div class="ui column portfolio-item">
      <img class="ui fluid rounded image" alt="{{ item.title }}" title="{{ item.name }}" src="{{ item.preview_image_url | relative_url }}"/>
    </div>
  </a>
  {% endfor %}
</div>


