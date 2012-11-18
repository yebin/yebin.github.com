---
layout: page
title: bīn Yè
description: 叶斌的 Jekyll 首页 index
---
{% include JB/setup %}

<img style="width:650px;float:center" alt="Roy Flying Doctor Service 飞行演练" src="http://yebin-wordpress.stor.sinaapp.com/uploads/2012/06/rfds.jpg"/>

* [Profile](https://plus.google.com/117301919963727743144/about)

**Latest Blog: **

<ul class="posts">
  {% for post in site.posts limit:1 %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>{{ post.excerpt }}
<div id='containerSlider'>
 <div id='contentslider-text'>
<p>About</p>
<p>叶斌&#65292;医生&#65292;执业者&#65292;干医疗经理的活&#12290;我喜欢我的职业&#65292;留意生活中每天精彩的片段与灵感&#12290;</p>
 </div>
  <div id='contentSlider'>
   <div id='slider'>
<script language='JavaScript'>
images = new Array(4);
images[0] = &quot;<img alt='渥太华 Notre Dame Cathedral Basilica 天主教堂' src='http://ww2.sinaimg.cn/mw690/737917b2gw1dw2gdlvjwgj.jpg'/>&quot;;
images[1] = &quot;<img alt='渥太华国会山' src='http://ww3.sinaimg.cn/mw690/737917b2gw1dw45qmusoyj.jpg'/>&quot;;
images[2] = &quot;<img alt='Hobart Sandy Bay 2011年9月 全科医学考察与培训' src='http://ww2.sinaimg.cn/mw690/737917b2gw1dw83rluqm9j.jpg'/>&quot;;
images[3] = &quot;<img alt='澳洲皇家飞行医生服务' src='http://ww3.sinaimg.cn/bmiddle/737917b2gw1dw7vozwpm7j.jpg'/>&quot;;
index = Math.floor(Math.random() * images.length);
document.write(images[index]);
</script>
   </div>