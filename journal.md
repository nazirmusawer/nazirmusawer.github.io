---
layout: default
title: Journal
permalink: /journal/
---

<ul class="postlist">
  {% for post in site.posts %}
    <li>
      <a class="plink" href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
