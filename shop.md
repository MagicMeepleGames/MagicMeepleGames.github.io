---
title: Shop
layout: default
category: pages
order: 5
---

{% for game in site.data.games %}
<button
    class="snipcart-add-item"
    data-item-id={{ game.id }}
    data-item-name={{ game.title }}
    data-item-price={{ game.price }}
    data-item-weight={{ game.weight }}
    data-item-url={{ game.url }}
    data-item-description={{ game.description }}
        Buy {{ game.title }}
</button>
{% endfor %}
