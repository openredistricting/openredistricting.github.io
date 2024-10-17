---
layout: page
title: Blog
---

Previous posts:

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}

<p>Subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>