---
layout: default
title: Blog
permalink: /blog/
---

<h1>All Blog Posts</h1>

<ul>
  {% for post in site.posts %}
    <li style="margin-bottom: 0.75em;">
      <a href="{{ post.url }}" style="font-weight: bold;">{{ post.title }}</a><br />
      <span style="color: #666;">{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
  {% endfor %}
</ul>
