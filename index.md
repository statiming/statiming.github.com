---
layout: page
title: 随机漫步
tagline: 一个时序工程师的工作与梦想
---
{% include JB/setup %}

欢迎来到

## Update Author Attributes

    $ rm -rf _posts/core-samples

## 最新文章

<ul class="posts">
  {% for post in site.posts limit:5 %}
    <li><span>{{ post.date | date_to_utc | date: '%Y-%m-%d' }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Englisth Pages
For non-Chinese reader, please read [Englisth Pages](http://statiming.github.com/en)
