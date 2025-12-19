---
layout: home
permalink: /home/
---

---
layout: default
title: Writings
permalink: /home/
---

<div class="center">
  <h2>Posts</h2>

  <ul>
    {% for post in site.posts %}
      <li>
        <small>{{ post.date | date: "%b %d, %Y" }}</small><br>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </li>
      <br>
    {% endfor %}
  </ul>
</div>
