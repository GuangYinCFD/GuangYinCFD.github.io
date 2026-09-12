---
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

<ul>
{% for item in site.data.navigation.main %}
<li><a href="{{ item.url | relative_url }}">{{ item.title }}</a></li>
{% endfor %}
</ul>
