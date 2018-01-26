---
title: News Archive
layout: default
---

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="/json-framework{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

