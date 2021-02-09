---
layout: page
title: Blog
---

This is my blog, where I write articles every now and then about various topics that I find interesting for a PhD student of computer science and related fields. 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>