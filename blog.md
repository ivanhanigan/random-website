---
layout: default
name: Blog
---

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="https://ivanhanigan.github.io/random-website{{ post.url }}">{{  post.title }}</a></h2>
      {{ post.excerpt }}
      {{ post.date | date_to_string }}
<P></P>
    </li>
  {% endfor %}
  

</ul>