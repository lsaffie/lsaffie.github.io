---
title: Posts
permalink: pretty
categories: readings
---

# {{page.title }}

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
