---
layout: page
title: Hello Everybody!
tagline: 
---
{% include JB/setup %}

Welcome to my site [Leeying](http://leeying.github.com)

Thanks for my colleague, my teacher: [Jijin Huang](http://jijin.github.com)

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



