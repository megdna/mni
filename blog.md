---
layout: post
permalink: /blog
title: Blog
description: This is a list of posts.
image: assets/images/blue.jpg
---
<div class="notice">Subscribe to <a href="{{ site.baseurl }}/feed" target="_blank">Feed</a></div>

{% for post in site.posts %}
<article>
  <h4><a href="{{ post.url | prepend: site.baseurl | prepend: site.url }}">{{ post.title }}</a></h4>
  <p>{{ post.description }}</p>
  <cite>{{ post.date | date_to_string }}</cite>
</article>
{% endfor %}