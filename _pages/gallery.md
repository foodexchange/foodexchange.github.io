---
layout: default
title: gallery
permalink: /gallery/
images:
  - image_path: ../images/beet-salad.jpeg
    title: Roasted beet and goat cheese salad
    
    
    
---

<p>Gallery of things we made</p>


<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}" title="{{ image.title}}"/></li>
  {% endfor %}
</ul>

