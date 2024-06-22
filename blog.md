---
layout: page
title: Science and Lifestyle
subtitle: Bridging the Gap
permalink: /blog/
---

#<h1 class="blog-page-title">Science and Lifestyle</h1>
#<p class="intro-subtitle">{{ page.subtitle }}</p>
<p class="intro-text">Explore the intersection of science and everyday living through some of the top viewed articles from my KOL blog. For more posts in my original KOL page in Chinese, click <a href="https://www.dealmoon.com/u/353625?type=guide">here</a>.</p>

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
