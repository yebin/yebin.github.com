---
layout: page
title: 
description: 叶斌的 Jekyll 首页 index
---
{% include JB/setup %}


<ul class="posts">
  {% for post in site.posts limit:3 %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>{{ post.excerpt }}