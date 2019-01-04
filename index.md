---
title: Projects
layout: default
category: pages
order: 1
published: true
---
{% include progressbar.html heroimage="/incoming-transmission/Oxygen Converter.jpg" logo="/incoming-transmission/incoming-transmission-logo-500px.png" alt="Incoming Transmission" percent="30%" status="Pre-production File Prep - Click To Sign Up For Updates!" link="incoming-transmission" %}

{% include progressbar.html heroimage="/overworld/overworld-closeup-500px.png" logo="/overworld/overworld-logo-500px.png" alt="Overworld" percent="94%" status="Shipping" link="https://magicmeeple.pledgemanager.com/projects/overworld-16-bit-tile-placement-and-exploration-bo/participate/" link="overworld" %}

{% include progressbar.html heroimage="/fire-of-eidolon/fire-of-eidolon-closeup-500px.png" logo="/fire-of-eidolon/fire-of-eidolon-logo-500px.png" alt="Fire Of Eidolon" percent="100%" status="In stock now! Click here!" link="fire-of-eidolon" %}

{% include progressbar.html heroimage="/darkrock-ventures/Darkrock-Ventures-Centerboard-Red-Closeup.jpg" logo="/darkrock-ventures/darkrock_ventures-500px.png" alt="Darkrock Ventures" percent="100%" status="In stock now! Click here!" link="darkrock-ventures" %}

<div class="subcontainer">
<div class="home-grid">
    <div class="tweet-stream home-grid-col">
        <h2>Tweets by <a href="https://twitter.com/MagicMeeple">@MagicMeeple</a>:</h2>
        <a class="twitter-timeline" href="https://twitter.com/MagicMeeple?ref_src=twsrc%5Etfw" data-chrome="transparent noheader nofooter" width="100%" data-tweet-limit="3"></a>
        <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    </div>
    <div class="friends-of-the-meeple home-grid-col">
        <h2>Newsletter:</h2>
        <p><a href="https://my.sendinblue.com/users/subscribe/js_id/3n0j4/id/1">Subscribe</a> to receive the Magic Meeple Games newsletter in your email!</p>
        <h2>Current Kickstarter Campaign:</h2>
        <iframe src="https://www.kickstarter.com/projects/magicmeeplegames/incoming-transmission-16-bit-deduction-family-boar/widget/card.html?v=2" width="310" height="420" frameborder="0" scrolling="no"></iframe>
        <h2>Friends Of The Meeple:</h2>
        <div class="carousel">
            <span class="prev-arrow"> ◀ </span>
            <span class="next-arrow"> ▶ </span>
            <div class="prev"></div>
            <div class="next"></div>
            <ol>
                {% for friend in site.data.friends %}
                <li style="background-image: url('/assets/images/FriendsOftheMeeple/{{ friend.filename }}')" data-caption="{{ friend.name }}">
                    <a href="{{ friend.url }}" target="_blank"></a>
                </li>
                {% endfor %}
            </ol>
        </div>
    </div>
</div>
</div>
<script>
carousel = (function(){
    var container = document.querySelector('.carousel');
    var next = container.querySelector('.next');
    var prev = container.querySelector('.prev');
    var counter = 0;
    var items = container.querySelectorAll('.carousel ol>li');
    var amount = items.length;
    var current = items[0];
    container.classList.add('active');
    function navigate(direction) {
        current.classList.remove('current');
        counter = counter + direction;
        counter = (direction === -1 && counter < 0) ? amount - 1 : counter; 
        counter = (direction === 1 && !items[counter]) ? 0 : counter;
        current = items[counter];
        current.classList.add('current');
    }
    next.addEventListener('click', function(ev) {
        navigate(1);
    });
    prev.addEventListener('click', function(ev) {
        navigate(-1);
    });
    navigate(0);
})();
</script>
