---
layout: default
title: Coding for the life
---
{{ site.url }}{{ post.url }}
{% for post in site.posts %}
    [{{ post.date | date_to_string }} - {{post.title}}]({{ site.url }}{{ post.url }})
{% endfor %}
