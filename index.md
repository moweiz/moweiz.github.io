---
layout: default
title: My Blog
---

# Welcome to My Tech Blog 🚀

I share blogs about gaming PCs, components, and buying guides.

## Latest Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
