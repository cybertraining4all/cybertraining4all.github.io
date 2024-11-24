---
layout: default
title: Students
menus: header
---

# Posts


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date| date: "%Y-%m-%d" }} - <h3>{{ post.title }}</h3></a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>