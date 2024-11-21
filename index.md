---
layout: default
menus: header
---

<div class="container">
  <img src="assets/hacker.png" alt="hacker" style="width:100%;">
  <div class="content">
    <h1>Cyber Security Training</h1>
    <p>Learn new skills and help build your team's effectiveness. This site helps buildings skill for all levels from executives to students.</p>
  </div>
</div>

<table border="0">
 <tr>
    <td><b style="font-size:30px">Students</b></td>
    <td><b style="font-size:30px">Executive</b></td>
 </tr>
 <tr>
    <td>Lorem ipsum ...</td>
    <td>Lorem ipsum ...</td>
 </tr>
</table>


## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date| date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>