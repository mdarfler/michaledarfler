---
title: 'Popup Playground'
subtitle: 'Creating play in an abandoned lot'
date: 2012-11-01 00:00:00
location: 'Philadelphia, PA'
featured_image: '/images/phs-playground/289743_10151268441645820_734404815_o.jpg'
tags: [fabrication, design, construction]
---
Some text goes here.

<div class="gallery" data-columns="3">
{% for img in site.static_files%}
  {% if img.path contains '/images/phs-playground' %}
    <img src="{{ img.path }}"/>
  {% endif %}
{% endfor %}
</div>
