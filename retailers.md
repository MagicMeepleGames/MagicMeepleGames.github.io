---
title: Retailers
layout: default
category: other
order: 6
---

# Retailer Resources

<div class="left column">

<div id="retailer-list">
<div class="table-controls-row">
  <h2>Retailers Who Carry Magic Meeple Games</h2>
  <h3>Filter on: <input class="search" /> Sort by:</h3>
  <div class="sort-controls">
    <button class="sort" data-sort="name">Name</button>
    <button class="sort" data-sort="city">City</button>
    <button class="sort" data-sort="state">State/Prov</button>
    <button class="sort" data-sort="zip">Postcode</button>
  </div>
</div>
<ul class="list">
{% for r in site.data.retailers %}
{% include retailer.html %}
{% endfor %}
</ul>
</div>

</div>

<div class="right column">

<h2>Resources For Retailers</h2>
<p>Here are some PDF resources retailers can use to help sell our products!</p>

<div class="gallery">
  <div class="retailer-resources">
    <a class="retailer-resources-link" href="https://drive.google.com/file/d/1b2r833YbXVO_J7UxJ61W7Uddit0_6aHR/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/overworld-shelf-hanger-with-margin.png')">
    </div>
    <div class="gallery-caption">
      Overworld shelf hanger with margins. 11"x8.5" PDF
    </div>
  </div>
  <div class="retailer-resources">
    <a class="retailer-resources-link" href="https://drive.google.com/file/d/1Mck_kc4BPL8WfHXcuhp5uGaTAbtAVp3G/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/overworld-shelf-hanger.png')">
    </div>
    <div class="gallery-caption">
      Overworld shelf hanger without margins. 11"x8.5" PDF
    </div>
  </div>
  <div class="retailer-resources">
    <a class="retailer-resources-link" href="https://drive.google.com/file/d/14S7C87UxIw6OfCMVrdL8FCNo0dH4SmSq/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/overworld-flyer-with-margins.png')">
    </div>
    <div class="gallery-caption">
      Overworld flyer with margins. 8.5"x11" PDF
    </div>
  </div>
  <div class="retailer-resources">
    <a class="retailer-resources-link" href="https://drive.google.com/file/d/16vk8RJLm0GxKOyxqV_PI4JL8jWACo4pw/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/overworld-flyer.png')">
    </div>
    <div class="gallery-caption">
      Overworld flyer without margins. 8.5"x11" PDF
    </div>
  </div>
  <div class="retailer-resources">
    <a class="retailer-resources-link" href="https://drive.google.com/file/d/1r6LsR1Zc-yYEt2lbbu5qlO8r0zw3acBy/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/overworld-quick-start-poster-with-margins.png')">
    </div>
    <div class="gallery-caption">
      Overworld quick start poster with margins. 8.5"x11" PDF
    </div>
  </div>
  <div class="retailer-resources">
    <a class="retailer-resources-link"  href="https://drive.google.com/file/d/1rdMkOXryKU6nX-XVS-byjaQgw557ijH-/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/overworld-quick-start-poster.png')">
    </div>
    <div class="gallery-caption">
      Overworld quick start poster without margins. 8.5"x11" PDF
    </div>
  </div>
  <div class="retailer-resources">
    <a href="https://drive.google.com/file/d/1VYtY3CD51TDHckQR6Xf_c1Dney1dfqFI/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/fire-of-eidolon-flyer.png')">
    </div>
    <div class="gallery-caption">
      Fire Of Eidolon flyer without margins. 11"x8.5" PDF
    </div>
  </div>
  <div class="retailer-resources">
    <a href="https://drive.google.com/file/d/14mjX0LJsTekBYkbzr6cMcK07Qlv8wCWq/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/fire-of-eidolon-flyer-with-margins.png')">
    </div>
    <div class="gallery-caption">
      Fire Of Eidolon flyer with margins. 11"x8.5" PDF
    </div>
  </div>
  <div class="retailer-resources">
    <a href="https://drive.google.com/file/d/1E4_006Y81XqbkSmVu9In_xvFM_hbpmOI/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/fire-of-eidolon-shelf-hanger.png')">
    </div>
    <div class="gallery-caption">
      Fire Of Eidolon shelf hanger without margins. 11"x8.5" JPG
    </div>
  </div>
  <div class="retailer-resources">
    <a href="https://drive.google.com/file/d/1OHrO6Th7edcEYvqf4INXMDbLLrimjmXb/view?usp=sharing">
    </a>
    <div class="thumbnail" style="background-image: url('/assets/images/retailer-kit-thumbnails/darkrock-ventures-shelf-hanger.jpg')">
    </div>
    <div class="gallery-caption">
      Darkrock Ventures shelf hanger without margins. 11"x8.5" JPG
    </div>
  </div>
</div>
<script src="//cdnjs.cloudflare.com/ajax/libs/list.js/1.5.0/list.min.js"></script>
<script>
document.addEventListener("DOMContentLoaded", function() { 
var options = {
    valueNames: [ 'name', 'city', 'state', 'zip' ]
};
var retailerList = new List('retailer-list', options);
console.dir(retailerList);
});
</script>

</div>
