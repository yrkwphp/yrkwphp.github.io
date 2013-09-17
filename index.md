---
layout: page
title: Hello World!
tagline: welcome yrkwphp
---
{% include JB/setup %}

<img src="http://atnd.org/event_images/0005/2261/BARgpPgCEAApdie_original.jpg?1368247746">

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
