---
layout: default
title: Projects
---
{% for post in site.posts %}
{% if post.tags contains "project" %}
## [{{ post.date | date: "%Y" }}: {{ post.title}}]({{ post.url }}) 
[![]({{ post.logo }})]({{ post.url }})
{: style="text-align: center;" }
{% endif %}
{% endfor %}
