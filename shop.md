---
title: Shop
layout: default
category: pages
order: 5
---

## You can order our games direct from us. Our online store is always open!

{% for p in site.data.products %}
{% capture box-image-filename %}assets/images/{{ p.box-image-filename }}{% endcapture %}
{% assign id = p.id %}
{% assign name = p.name %}
{% assign price = p.price %}
{% assign weight = p.weight %}
{% assign url = p.url %}
{% assign description = p.description %}
{% include product.html id=id box-image-filename=box-image-filename name=name price=price weight=weight url=url description=description %}
{% endfor %}
