---
layout: default
title: News
---


<h1>{{ page.title }}</h1>

<ul class="posts">
{% for post in site.posts %}
<li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

# Blog
<a href="https://mariherigstad.wordpress.com"><img src="/assets/blog_banner.jpg" alt="Blog" align="middle" style="width: 410px;"/> </a>

