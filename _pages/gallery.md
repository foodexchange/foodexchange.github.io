---
layout: default
title: gallery
permalink: /gallery/
images:
  - image_path: ../images/[filename]
    title: [Name of item]
    
    
    
---

<p>Header text</p>


<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}" title="{{ image.title}}"/></li>
  {% endfor %}
</ul>

