---
title: Shop
layout: default
category: pages
order: 5
---

## You can order our games direct from us. Our online store is always open!

<div class="snipcart-summary">
    Number of items: <span class="snipcart-total-items"></span>
    Total price: <span class="snipcart-total-price"></span>
    <a href="#" class="snipcart-user-email snipcart-user-profile"> Customer dashboard </a>
</div>

{% for p in site.data.products %}
{% capture box-image-filename %}assets/images/{{ p.box-image-filename }}{% endcapture %}
{% assign id = p.id %}
{% assign name = p.name %}
{% assign current-msrp = p.current-msrp %}
{% assign weight = p.weight| plus:0 %}
{% assign url = p.url %}
{% assign play-time = p.play-time %}
{% assign short-description = p.short-description %}
{% include product.html id=id box-image=box-image name=name current-msrp=current-msrp weight=weight url=url description=short-description %}
{% endfor %}
