---
layout: page
title: �뵼�塡ͳ�ơ�Ͷ��
tagline: һ���Ϲ���ʦ�Ĳ���
---
{% include JB/setup %}


��ӭ�����ҵĸ���ҳ��

## Update Author Attributes

    $ rm -rf _posts/core-samples

## ��������  

<ul class="posts">
  {% for post in site.posts limit:5 %}
    <li><span>{{ post.date | date_to_utc | date: '%Y-%m-%d' }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Englisth Pages
For non-Chinese reader, please read [Englisth Pages](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
