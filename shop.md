---
title: Shop
layout: default
category: pages
order: 5
---

{% for product in site.data.products %}
{{ product.name }}
{% endfor %}
