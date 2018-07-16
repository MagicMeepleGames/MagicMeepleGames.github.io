---
title: Test
layout: default
category: hidden
order: 2
---
<div class="subcontainer">
<div class="home-grid">
    <div class="tweet-stream home-grid-col">
        <h2>Tweets by <a href="https://twitter.com/MagicMeeple">@MagicMeeple</a></h2>
        <a class="twitter-timeline" href="https://twitter.com/MagicMeeple?ref_src=twsrc%5Etfw" data-chrome="transparent noheader nofooter" width="100%" data-tweet-limit="3"></a>
        <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    </div>
    <div class="friends-of-the-meeple home-grid-col">
        <h2>Friends Of The Meeple</h2>
        <div class="carousel">
          <span class="prev-arrow"> ◀ </span>
          <span class="next-arrow"> ▶ </span>
          <div class="prev"></div>
          <div class="next"></div>
          <ol>
            {% for friend in site.data.friends %}
            <li style="background-image: url('/assets/images/FriendsOftheMeeple/{{{ friend.filename }}')" data-caption="{{ friend.name }}">
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