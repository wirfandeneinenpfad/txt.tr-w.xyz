---
layout: page
title: Photos
images:
	- image_path: /images/photos/berlin-1.jpg
    title: Apple Pie
---
<ul class="photo-gallery">
  {% for image in page.images %}
    <li><img src="{{ image.image_path }}" alt="{{ image.title}}"/></li>
  {% endfor %}
</ul>