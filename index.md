---
layout: page
title: HOMEPAGE
tagline: Supporting tagline
---
{% include JB/setup %}


## My POSTS


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>









