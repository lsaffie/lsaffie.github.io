---
title: Home
categories: 
---

# {{page.title }}

> Principles are ways of successfully dealing with reality to get what you want out of life.

Ray Dalio <https://www.principles.com/>

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
