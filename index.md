---
layout: page
title: Hello World!
tagline: 
---
{% include JB/setup %}


## Introduction

这是一个用jekyll在github建立的技术博客

## Posts


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



