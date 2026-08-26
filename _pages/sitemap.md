---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

## Pages

- [About](/)
- [Publications](/publications/)
- [Projects](/portfolio/)
- [CV](/cv/)

## Publications

{% for post in site.publications reversed %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## Projects

{% for post in site.portfolio %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

