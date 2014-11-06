---
title: Posts by category
---
<h1>{{ page.title }}</h1>

{% assign group_type = 'categories' %}
{% assign ungrouped_title = 'Uncategorized' %}
{% include groups.html %}
