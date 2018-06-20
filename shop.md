---
title: Shop
layout: shop
category: pages
order: 5
---

## You can order our games direct from us. Our online store is always open!

<div class="snipcart-summary">
    <span class="cart"> </span> The cart has <span class="snipcart-total-items"></span> items, for a total of <span class="snipcart-total-price"></span>.
    You can buy as a guest, but also, you may create a <strong>totally optional</strong> <a href="#" class="snipcart-user-email snipcart-user-profile">user account</a>! Again, you may buy from us <strong>with no account necessary</strong>!
</div>
<div class="products">
{% for p in site.data.products %}
{% include product.html %}
{% endfor %}
</div>
