---
layout: default
title: Projects
---
# Projects
{% for post in site.posts %}
{% if post.tags contains "project" %}


* [{{ post.title}}]({{ post.url }})
\\
{% endif %}
{% endfor %}
