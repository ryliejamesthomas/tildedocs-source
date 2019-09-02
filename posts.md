---
layout: index.liquid
---

## {{ page.title }}
{% for post in collections.posts.pages %}
* [{{ post.title }}]({{ post.permalink }})
{% endfor %}
