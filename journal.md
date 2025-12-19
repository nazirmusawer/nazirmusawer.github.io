---
layout: default
title: Journal
permalink: /journal/
---

<div class="center">
  <h2>Posts</h2>

  <ul class="postlist">
    {% for post in site.posts %}
      <li>
        <div class="date">{{ post.date | date: "%b %d, %Y" }}</div>
        <a class="plink" href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
</div>
