---
layout: default
title: Students
menus: header
---

# Posts


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}"><h3>{{ post.date| date: "%Y-%m-%d" }} - {{ post.title }}</h3></a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>