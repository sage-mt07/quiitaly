---
layout: default
title: Home
---

# Welcome to My Blog

This is the homepage of my blog. Here, I share my thoughts, tutorials, and updates on various topics.

## Recent Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%Y-%m-%d" }}
    </li>
  {% endfor %}
</ul>

## About Me

I am a developer who loves to write about technology, programming, and other interesting topics. Feel free to explore my blog and leave comments!

---

### Categories

- [Programming](#)
- [Technology](#)
- [Life](#)