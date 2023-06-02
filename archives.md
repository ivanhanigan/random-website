---
layout: default
title: Archives
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/random-website/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>