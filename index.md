---
layout: page
title: bīn Yè
description: 叶斌的 Jekyll 首页 index
---
{% include JB/setup %}

<img style="width:650px;float:center" alt="Roy Flying Doctor Service 飞行演练" src="http://yebin-wordpress.stor.sinaapp.com/uploads/2012/06/rfds.jpg"/>

* [Profile](https://plus.google.com/u/0/111730946330475204627/about)
* [about](http://www.yebin.info/page/about)

**Latest Blog: **

<ul class="posts">
  {% for post in site.posts limit:3 %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>{{ post.excerpt }}