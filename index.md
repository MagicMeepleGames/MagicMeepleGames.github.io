---
title: Projects
layout: default
category: pages
order: 1
---
{% include progressbar.html heroimage="Oxygen Converter.jpg" logo="/incoming-transmission/incoming-transmission-logo-500px.png" alt="Incoming Transmission" percent="10%" status="Pre-Kickstarter Review And Development" %}

{% include progressbar.html logo="/overworld/overworld-logo-500px.png" alt="Overworld" percent="90%" status="Prepress" link="https://magicmeeple.pledgemanager.com/projects/overworld-16-bit-tile-placement-and-exploration-bo/participate/" %}

{% include progressbar.html heroimage="/fire-of-eidolon/fire-of-eidolon-closeup-500px.png" logo="/fire-of-eidolon/fire-of-eidolon-logo-500px.png" alt="Fire Of Eidolon" percent="100%" status="In stock now! Click here!" link="/shop.html" %}

{% include progressbar.html logo="/darkrock-ventures/darkrock_ventures-500px.png" alt="Darkrock Ventures" percent="100%" status="In stock now! Click here!" link="/shop.html" %}

<div class="home-grid">
    <div class="tweet-stream home-grid-col">
        <h2>Tweets by <a href="https://twitter.com/MagicMeeple">@MagicMeeple</a></h2>
        <a class="twitter-timeline" href="https://twitter.com/MagicMeeple?ref_src=twsrc%5Etfw" data-chrome="transparent noheader nofooter" width="100%" data-tweet-limit="3"></a>
        <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    </div>
    <div class="friends-of-the-meeple home-grid-col">
        <h2>Friends Of The Meeple</h2>
        <marquee behavior="alternate">
            {% for friend in site.data.friends %}
            <a href="{{ friend.url }}"><img src="assets/images/FriendsOftheMeeple/{{ friend.filename }}" data-caption="{{ friend.name }}" target="_blank" ></a>
            {% endfor %}
        </marquee>
    </div>
</div>
