---
layout: default
title: Research_Assistant
---
{% for post in site.posts %}
{% if post.tags contains "research_assistant" %}
## [{{ post.date | date: "%Y" }}: {{ post.title}}]({{ post.url }}) 
[![]({{ post.logo }})]({{ post.url }})
{: style="text-align: center;" }
{% endif %}
{% endfor %}
