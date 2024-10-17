---
layout: page
title: Blog
---

Posts:

{% for post in site.posts %}
* {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}

<p>Subscribe <a href="{{ '/atom.xml' | relative_url }}" class="rss-subscribe">via RSS</a>.</p>