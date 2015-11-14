---
layout: page
title: Ted Xiao
tagline: Selected Musings
---
{% include JB/setup %}
## About
This is a simple blog made by Ted Xiao, a student a UC Berkeley.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
