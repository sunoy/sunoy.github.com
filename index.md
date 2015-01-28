---
layout: page
title: Sunoy Blog
tagline: For what its worth, its never too late.
---
{% include JB/setup %}

If they throw stones at you, dong't throw back, use them to build your own foundation instead.

## 生活点滴

This theme is still unfinished. If you'd like to be added as a contributor, [please fork]
(http://sunoy.blog)!
    
## 技术学习

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




