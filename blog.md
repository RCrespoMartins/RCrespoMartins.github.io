---
layout: page
title: "Blog"
---

# Blog & Essays

A collection of essays, reflections, and notes.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span> — {{ post.date | date: "%B %Y" }}</span>
      <br>
      <small>Categories: {{ post.categories | join: ", " }} | Tags: {{ post.tags | join: ", " }}</small>
    </li>
  {% endfor %}
</ul>