---
title: Shop
layout: shop
category: pages
order: 5
---

## You can order our games direct from us. Our online store is always open!

<div class="snipcart-summary">
    Number of items: <span class="snipcart-total-items"></span>
    Total price: <span class="snipcart-total-price"></span>
    <a href="#" class="snipcart-user-email snipcart-user-profile"> Customer dashboard </a>
</div>
<div class="products">
{% for p in site.data.products %}
{% include product.html %}
{% endfor %}
</div>
