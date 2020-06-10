---
layout: default
title: "Portfolio"
menu_item: "portfolio"
---


<div class="portfolio">
  {% for item in site.categories.portfolio %}
  <a href="{{ item.url }}">
    <img class="portfolio-item" alt="{{ item.title }}" src="{{ item.preview_image_url }}"/>
  </a>
  {% endfor %}
</div>
