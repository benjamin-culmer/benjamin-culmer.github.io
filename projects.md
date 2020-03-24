---
layout: default
title: Projects
---
# Projects
{% for post in site.posts %}
# [{{ post.title}}]({{ post.url }})
![<img src={{ post.url }}]({{ post.logo }}) 
{: style="text-align: center;" }
{% endfor %}
