---
layout: page
title: TamLab
tagline: <i>The art of thinking, working and developping right</i>
---
{% include JB/setup %}

<div id="myCarousel" class="carousel slide" style="width:600px;height:450px;line-height:450px;text-align:center;">
  <!-- Carousel items -->
  <div class="carousel-inner">
    <div class="active item"><img style="vertical-align:middle;display:inline-block;" src="http://nodejs.org/images/logos/nodejs-1024x768.png" /></div>
    <div class="item"><img style="vertical-align:middle;display:inline-block;" src="https://lh6.googleusercontent.com/-hU-IXoDdlA4/ThmqTIhc7EI/AAAAAAAAAuw/6xfeIQtmXDA/s800/martin_odersky_et_moi.jpg" /></div>
    <div class="item"><img style="vertical-align:middle;display:inline-block;" src="http://www.mind2machine.com/wp-content/uploads/2012/04/html5-logo-1.jpg" /></div>
  </div>
  <!-- Carousel nav -->
  <a class="carousel-control left" href="#myCarousel" data-slide="prev">&lsaquo;</a>
  <a class="carousel-control right" href="#myCarousel" data-slide="next">&rsaquo;</a>
</div>
<script type="text/javascript">
    $('.carousel').carousel({interval: 3000});
</script>

## Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
