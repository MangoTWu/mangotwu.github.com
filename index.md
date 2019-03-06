---
layout: page
title: Hello!
tagline: Welcome to my blog
---
{% include JB/setup %}

# 献给这个世界上我最爱的周楠宝贝

------

Here's posts list.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
