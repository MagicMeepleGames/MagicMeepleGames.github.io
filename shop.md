---
title: Shop
layout: default
category: pages
order: 5
---

{% for product in site.data.products %}
{% include product.html name={{ product.name }} box-image-filename={{ product.box-image-filename }} price={{ product.price }} description={{product.description}} weight={{ product.weight }} url={{ product.url }} %}
{% endfor %}
