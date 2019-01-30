---
title: Contact Us
layout: default
category: pages
order: 4
---

<script type="text/javascript">var submitted=false;</script>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {window.location='sent.html';}"></iframe>

<form class="form" action="https://docs.google.com/forms/d/e/1FAIpQLSedW_sHoUVpwC_j7bvXpsbaqq8pn7vfZjwqkp8D_S9NJZgMFA/formResponse" target="hidden_iframe" onsubmit="submitted=true;" method="POST" id="mG61Hd">

<h1>Contact Magic Meeple Games</h1>

<p>We'll need all fields filled in, please. Give us five business days for an email response, OK? It will be our pleasure to talk to you!</p>

<h2>Overworld Final Delivery:</h2>

<h2>Your Email: <input type="email" tabindex="1" max-length="70" name="emailAddress" required /></h2>

<h2>Your Name: <input type="text" tabindex="2" max-length="70" name="entry.1924108681" required /></h2>

<h2>Your Topic:</h2>

<div class="radio-button-group">

<p class="radio-btn"><input type="radio" name="entry.1466018481" id="topic-parts-replacement" value="Parts Replacement" tabindex="3"><label for="topic-parts-replacement">Parts Replacement</label></p>

<p class="radio-btn"><input type="radio" name="entry.1466018481" id="topic-rules-question" value="Rules Question" tabindex="4"><label for="topic-rules-question">Rules Question</label></p>

<p class="radio-btn"><input type="radio" name="entry.1466018481" id="topic-retailer-contact" value="Retailer Contact" tabindex="5"><label for="topic-retailer-contact">Retailer Contact</label></p>

<p class="radio-btn"><input type="radio" name="entry.1466018481" id="topic-other" value="Other" tabindex="6" checked><label for="topic-other">Other</label></p>

<input type="radio" name="entry.444857849" id="quick" value="quick" hidden>
<input type="radio" name="entry.444857849" id="slow" value="slow" hidden>

</div>

<h2>Your Message:</h2>

<p><textarea name="entry.1856670343" tabindex="7" rows="7" style="width: 90%" required ></textarea><label for="entry.1620700245" style="visibility: hidden; height: 0; padding: 0;">Leave empty:</label><input type="text" max-length="70" name="entry.1620700245" style="visibility: hidden; height: 0; padding: 0;" /></p>

<p><input id="send" type="submit" value="Send" tabindex="8"/></p>

<script type="text/javascript">
  $(document).ready(function () {
    var quick = document.getElementById('quick'),
        slow = document.getElementById('slow'),
        email_field = document.getElementsByName('emailAddress')[0],
        name_field = document.getElementsByName('entry.1924108681')[0],
        start_time = new Date(),
        milliseconds = 0,
        measure = function (e) {
          elapsed_time = new Date();
          milliseconds = elapsed_time - start_time;
          if (milliseconds > 999) {
            slow.checked = true;
            e.target.removeEventListener('change', measure, false);
          } else {
            quick.checked = true;
          }
        };
    email_field.addEventListener('change', measure, false);
    name_field.addEventListener('change', measure, false);
  });
</script>
</form>
