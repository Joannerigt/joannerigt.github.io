---
layout: default
title: "Portfolio"
menu_item: "portfolio"
---


<div class="ui three column stackable doubling grid portfolio">
  {% for item in site.categories.portfolio %}
  <a href="{{ item.url }}">
    <div class="column">
      <img class="ui fluid rounded image portfolio-item" alt="{{ item.title }}" src="{{ item.preview_image_url }}"/>
    </div>
  </a>
  {% endfor %}
</div>
