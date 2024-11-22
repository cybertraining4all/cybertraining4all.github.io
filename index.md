---
layout: default
menus: header
---

<div class="hero-container">
  <img src="assets/hacker.png" alt="hacker" style="width:100%;">
  <div class="hero-content">
   <div  style="20px;">
    <h1>Cyber Security Training</h1>
    <p>Learn new skills and help build your team's effectiveness. This site helps buildings skill for all levels from executives to students.</p>
    </div>
  </div>
</div>

<div style="text-algin:center;width:100%">
<div style="display: table;margin:auto;padding:20px;">
  <div style="display: table-row">
  <a href="students">
   <div class="hero-container" style="display: table-cell; margin:10px" >
    <img src="assets/students.jpg" alt="hacker" style="width:300px;">
    <div class="hero-content">
      <h2 style="15px;">Students</h2>
    </div>
   </div>
   </a>
  <a href="executive">   
   <div class="hero-container" style="display: table-cell;">
    <img src="assets/executives.jpg" alt="hacker" style="width:300px;">
    <div class="hero-content">
     <h2 style="15px;">Executives</h2>
    </div>
   </div>
   </a>
  <a href="employees">   
   <div class="hero-container" style="display: table-cell;">
    <img src="assets/employees.jpg" alt="hacker" style="width:300px;">
    <div class="hero-content">
      <h2 style="15px;">Employees</h2>
    </div>
   </div>
   </a>
  </div>
</div>
</div>

<p>
---
<p>

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date| date: "%Y-%m-%d" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>