---
layout: page
title: Yan's World
tagline: 关注移动设备开发
---
{% include JB/setup %}
    
## Blog Posts


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



