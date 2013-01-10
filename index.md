---
layout: page
title: 半导体　统计　投机
tagline: 一个老工程师的博客
---
{% include JB/setup %}


欢迎来到我的个人页面

## Update Author Attributes

    $ rm -rf _posts/core-samples

## 最新文章  

<ul class="posts">
  {% for post in site.posts limit:5 %}
    <li><span>{{ post.date | date_to_utc | date: '%Y-%m-%d' }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Englisth Pages
For non-Chinese reader, please read [Englisth Pages](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
