---
title: Shop
layout: default
category: pages
order: 5
---

{% for product in site.data.products %}
# {{ product.name }} ${{ product.price }}
{% include product.html name=product.name price=product.price %}
{% endfor %}
