---
layout: article
title: Ryedale Aquarist Society Open Event 2027
title_html: Ryedale Aquarist Society<br>Open Event 2027
show_title: true
excerpt: Sunday June 13th 2027 - Free Entry -
excerpt_html: Sunday June 13th 2027<br>- Free Entry -
description: All details for the Ryedale Aquarist Society Open Event 2027
header_logo: /assets/images/open-event-logo.png
---

<div class="countdown" data-countdown="2027-06-13T10:00:00+01:00" role="timer" aria-label="Time until the Open Event">
  <div><span class="countdown__value" data-unit="days">--</span><span class="countdown__label">Days</span></div>
  <div><span class="countdown__value" data-unit="hours">--</span><span class="countdown__label">Hrs</span></div>
  <div><span class="countdown__value" data-unit="minutes">--</span><span class="countdown__label">Mins</span></div>
  <div><span class="countdown__value" data-unit="seconds">--</span><span class="countdown__label">Secs</span></div>
</div>

<div class="event-highlights">

<ul class="fish-list">
  <li>Live Tropical Fish Show</li>
  <li>Aquarium Fish for Sale</li>
  <li>Aquarium Goods for Sale</li>
  <li>Tombola with big prizes</li>
  <li>Hot and Cold Food</li>
  <li>Cakes and Sweets</li>
  <li>Drinks on Draught</li>
  <li>Excellent social scene</li>
</ul>

<video class="event-video" controls preload="metadata" poster="{{ '/assets/videos/open-event-2026-poster.jpg' | relative_url }}">
  <source src="{{ '/assets/videos/open-event-2026.mp4' | relative_url }}#t=2" type="video/mp4">
  <a href="{{ '/assets/videos/open-event-2026.mp4' | relative_url }}">Footage from our 2026 event</a>
</video>

</div>

Save the date, come and join us for a great family day out!

<div class="event-gallery">
  <a href="{{ '/assets/images/gallery/denison-barb-large.jpg' | relative_url }}"><img src="{{ '/assets/images/gallery/denison-barb.jpg' | relative_url }}" alt="A photograph of a Denison Barb in a small show tank. The fish faces to the right and is side on."></a>
  <a href="{{ '/assets/images/gallery/turquoise-rainbowfish-large.jpg' | relative_url }}"><img src="{{ '/assets/images/gallery/turquoise-rainbowfish.jpg' | relative_url }}" alt="A photograph of a turquoise rainbowfish in a small show tank. The fish faces to the right and is side on."></a>
</div>

<script>
  (function () {
    var box = document.querySelector('[data-countdown]');
    if (!box) {
      return;
    }
    var target = new Date(box.getAttribute('data-countdown')).getTime();
    var parts = {};
    box.querySelectorAll('[data-unit]').forEach(function (el) {
      parts[el.getAttribute('data-unit')] = el;
    });
    function pad(n) {
      return n < 10 ? '0' + n : String(n);
    }
    function tick() {
      var left = Math.max(0, Math.floor((target - Date.now()) / 1000));
      parts.days.textContent = Math.floor(left / 86400);
      parts.hours.textContent = pad(Math.floor(left % 86400 / 3600));
      parts.minutes.textContent = pad(Math.floor(left % 3600 / 60));
      parts.seconds.textContent = pad(left % 60);
    }
    tick();
    setInterval(tick, 1000);
  })();
</script>
