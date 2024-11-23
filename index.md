---
layout: default
title: Home
---

![Wile the Wile Labs Sheep]({{site.baseurl}}/assets/images/wile.png)

{% assign latest_post = site.posts.first %}

# {{ latest_post.title }}

<small>Posted on {{ latest_post.date | date: "%B %d, %Y" }}</small>

<p>{{ latest_post.excerpt | strip_html }}</p>

<a href="{{ latest_post.url }}">Read more</a>






