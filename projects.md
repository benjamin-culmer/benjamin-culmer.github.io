---
layout: default
title: Projects
---
# Projects
{% for post in site.posts %}


* [{{ post.title}}]({{ post.url }})
{% endfor %}
