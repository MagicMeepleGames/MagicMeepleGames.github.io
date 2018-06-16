---
title: Darkrock Ventures
layout: product-details
category: games
order: 1
published: true
---
{% assign p = site.data.products[page.title] %}
{% include product-details-header.html name=p.name product-code=p.product-code designer=p.designer developer=p.developer artist=p.artist graphic-designer=p.graphic-designer publisher=p.publisher ages-official=p.ages-official ages-community=p.ages-community min-players=p.min-players max-players=p.max-players solo-mode=p.solo-mode cooperative-mode=p.cooperative-mode competitive-mode=p.competitive-mode play-time=p.play-time setup-time=p.setup-time teach-learn-time=p.teach-learn-time complexity=p.complexity short-description=p.short-description long-description=p.long-description box-image=p.box-image game-contents-image=p.game-contents-image closeup-front-image=p.closeup-front-image closeup-back-image=p.closeup-back-image current-msrp=p.current-msrp expansions-included=p.expansions-included expansions-sold-seperately=p.expansions-sold-seperately availability=p.availability link-to-rules=p.link-to-rules link-to-bgg=p.link-to-bgg link-to-kickstarter=p.link-to-kickstarter %}
