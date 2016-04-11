---
layout: page
title: Blog
permalink: /blog/
---
## Archive

<ul>
  {% for post in site.posts %}
    <li>
      {{ post.date | date: "%Y-%m-%d" }} &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


