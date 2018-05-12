---
layout: default
---

# homepage #

{% for post in site.posts %}
[{{ post.title }}]({{ post.url | absolute_url }})
{% endfor %}
