---
title: Shop
layout: default
category: pages
order: 5
---

{% for product in site.data.products %}
{% include product.html name={{ product.name }} price={{ product.price }} %}
{% endfor %}
