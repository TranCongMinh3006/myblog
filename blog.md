---
layout: page
title: Blog 
permalink: /blog/
---
<h1>Các bài viết gần đây</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="/myblog{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
