---
layout: default
title: Projects
---
{% for post in site.posts %}
## [{{ post.date | date: "%Y" }}: {{ post.title}}]({{ post.url }}) 
[![]({{ post.logo }})]({{ post.url }})
{: style="text-align: center;" }
{% endfor %}
