---
layout: page
title: Connect Science with Living in Style
permalink: /blog/
---

<p>I kept some of the top hit articles here. For more posts in Chinese, click <a href="https://www.dealmoon.com/u/353625?type=guide">here</a>.</p>

<div class="posts-list">
  {% for post in site.posts %}
    <div class="post-preview">
      {% if post.thumbnail-img %}
        <a href="{{ post.url | relative_url }}" class="post-image">
          <img src="{{ post.thumbnail-img }}" alt="{{ post.title }}">
        </a>
      {% endif %}
      <h2 class="post-title">
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h2>
      <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
      <p class="post-subtitle">{{ post.excerpt }}</p>
    </div>
  {% endfor %}
</div>
