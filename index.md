---
layout: page
title: "The Mind of Mowry"
permalink: /
---

<p class="tagline">Fit life. Real growth. Honest thoughts.</p>

<div class="hero-box">
  <h2>Welcome</h2>
  <p>
    This is a space for the everyday moments that shape my life — fitness, discipline,
    personal growth, and the lessons I learn along the way.
  </p>
</div>

<h2>Latest posts</h2>
<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
