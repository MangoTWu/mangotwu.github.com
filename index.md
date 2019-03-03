---
layout: page
title: Hello!
tagline: Welcome to my blog
---
{% include JB/setup %}

你好！我是吴谢，一名在校大学生，社交网站[hustbook](https://www.hustbook.com/)的创建者。

你可以在这里找到我：

- [GitHub](https://github.com/MangoTWu)

------

Here's posts list.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
