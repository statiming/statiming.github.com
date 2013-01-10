---
layout: page
title: 半导体　统计　投机
tagline: 一个老工程师的博客
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Update Author Attributes

    $ rm -rf _posts/core-samples

The theme should reference these variables whenever needed.
    

## Latest Posts

<ul class="posts">
  {% for post in site.posts limit 2 %}
    <li><span>{{ post.date | date_to_utc | date: '%Y-%m-%d' }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do
This theme is still unfinished.

