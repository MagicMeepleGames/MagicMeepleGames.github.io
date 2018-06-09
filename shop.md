---
title: Shop
layout: default
category: pages
order: 5
---

{% for thisproduct in site.data.products %}
{% include product.html name={{ thisproduct.name }} price={{ thisproduct.price }} %}
{% endfor %}
