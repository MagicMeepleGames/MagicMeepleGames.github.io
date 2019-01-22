---
title: Shop
layout: shop
category: pages
order: 8
---
# Shop

## You can order our games direct from us. Our online store is always open!

<p class="snipcart-summary">
    <a href="#" class="snipcart-checkout">The shopping cart</a> has <span class="snipcart-total-items"></span> items, for a total of <span class="snipcart-total-price"></span>.
    You can buy as a guest, but also, you may create a <strong>totally optional</strong> <a href="#" class="snipcart-user-email snipcart-user-profile">user account</a>! You may buy from us <strong>with no account necessary</strong>!
</p>
<div class="products">
{% for p in site.data.products %}
{% include product.html %}
{% endfor %}
</div>
