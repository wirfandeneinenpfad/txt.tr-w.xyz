---
layout: page
title: Photography
permalink: /photos/

images:
	- image_path: /images/photos/berlin-1.jpg
    title: Apple Pie
    - image_path: /images/photos/berlin-2.jpg
    title: blub
---
## Photography

<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>