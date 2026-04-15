---
layout: page
title: Writing
permalink: /writing/
---

<div class="page-shell">
  <p class="page-intro">
    这里收集我想保留下来的文章、实验记录和阶段性判断。它们不一定成熟，但都来自真实的问题。
  </p>

  {% if site.posts.size > 0 %}
    <div class="writing-list">
      {% for post in site.posts %}
        <article class="note-card">
          <p class="post-date">{{ post.date | date: "%Y.%m.%d" }}</p>
          <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
          <p>{{ post.excerpt | strip_html | strip_newlines | truncate: 180 }}</p>
        </article>
      {% endfor %}
    </div>
  {% else %}
    <p class="empty-state">还没有文章发布。</p>
  {% endif %}
</div>
