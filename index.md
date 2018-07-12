---
title: Projects
layout: default
category: pages
order: 1
---
{% include progressbar.html heroimage="/incoming-transmission/Oxygen Converter.jpg" logo="/incoming-transmission/incoming-transmission-logo-500px.png" alt="Incoming Transmission" percent="25%" status="Click Here To Back The Kickstarter Now!" link="https://www.kickstarter.com/projects/magicmeeplegames/incoming-transmission-16-bit-deduction-family-boar" %}

{% include progressbar.html heroimage="/overworld/overworld-closeup-500px.png" logo="/overworld/overworld-logo-500px.png" alt="Overworld" percent="90%" status="Prepress" link="https://magicmeeple.pledgemanager.com/projects/overworld-16-bit-tile-placement-and-exploration-bo/participate/" link="overworld" %}

{% include progressbar.html heroimage="/fire-of-eidolon/fire-of-eidolon-closeup-500px.png" logo="/fire-of-eidolon/fire-of-eidolon-logo-500px.png" alt="Fire Of Eidolon" percent="100%" status="In stock now! Click here!" link="fire-of-eidolon" %}

{% include progressbar.html heroimage="/darkrock-ventures/Darkrock-Ventures-Centerboard-Red-Closeup.jpg" logo="/darkrock-ventures/darkrock_ventures-500px.png" alt="Darkrock Ventures" percent="100%" status="In stock now! Click here!" link="darkrock-ventures" %}

<div class="subcontainer">
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
            <a href="{{ friend.url }}" target="_blank"><img src="assets/images/FriendsOftheMeeple/{{ friend.filename }}" data-caption="{{ friend.name }}" ></a>
            {% endfor %}
        </marquee>
    </div>
</div>
</div>