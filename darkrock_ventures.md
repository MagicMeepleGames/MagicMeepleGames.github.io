---
title: Darkrock Ventures
layout: product-details
category: games
order: 1
published: true
---
test
{% assign p = site.data.products[page.title] %}
<h1>{{ p.title }} - {{ p.availability }}</h1>
<div class="details-box-image" style="background-image: url({{ p.box-image }})">
</div>
<div class="details-game-contents-image" style="background-image: url({{ p.game-contents-image }})">
</div>
<div class="credits">
<ul>
<li>Designer: {{ p.designer }}.</li>
<li>Artist: {{ p.artist }}.</li>
<li>Developer: {{ p.developer }}.</li>
<li>Publisher: {{ p.publisher }}.</li>
</ul>
</div>
<div class="price">
<p>{{ p.product-code }} {{ p.current-msrp }}</p>
</div>
<div class="gameplay">
<p>Ages {{ p.ages-official }} ({{ p.ages-community }}) For {{ p.min-players }} to {{ p.max-players }} players. Play time 
{{ p.play-time }}. Setup time {{ p.setup-time }}. Time to teach and learn {{ p.teach-learn-time }}. Complexity {{ p.complexity }}.</p>
</div>
<div class="short-description">
<p>{{ p.short-description }}</p>
</div>
<div class="short-description">
<p>{{ p.long-description }}</p>
</div>
<div class="expanded-by">
<p>Expansions included: {{ p.expansions-included }}</p>
<p>Expansions sold separately: {{ p.expansions-sold-seperately }} </p>
</div>
<div class="links">
<ul>
<li>Rules: {{ p.link-to-rules }}</li>
<li>Boardgamegeek: {{ p.link-to-bgg }}</li>
<li>Kickstarter: {{ p.link-to-kickstarter }}</li>
</ul>
</div>
