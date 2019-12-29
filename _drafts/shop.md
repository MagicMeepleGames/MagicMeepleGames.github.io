---
title: Shop
layout: shop
category: pages
order: 8
---
# Shop

## You can order our games direct from us. Our online store is always open!

<div class="products">
{% for p in site.data.products %}
{% include product.html %}
{% endfor %}
</div>
