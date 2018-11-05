---
title: 'FABington'
subtitle: 'A MakerSpace at the intersection of art, technology, and entrepreneurship.'
date: 2016-05-01 00:00:00
location: 'Jenkintown, PA'
featured_image: '/images/aac/DSC00447.jpg'
tags: [fabrication, design, furniture]
published: false
---
**Principal | {{page.principal}} <br>
Role | {{page.role}}**<br>
<div class="gallery" data-columns="3">
{% for img in site.static_files%}
  {% if img.path contains '/images/aac' %}
    <img src="{{ img.path }}"/>
  {% endif %}
{% endfor %}
</div>
