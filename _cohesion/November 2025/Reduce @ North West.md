---
title: Reduce @ North West
permalink: /cohesion/november-2025/reduce-nw/
variant: markdown
description: ""
third_nav_title: November 2025
---
<style>

p {
  font-family: 'Lato', sans-serif;
  font-size: 16px;
  line-height: 26px;
}

h1, h2, h3, h4, h5, h6, li {
  font-family: 'Lato', sans-serif;
  line-height: initial;
}

.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}

.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12 {float: left !important;}

.col-4 img {width: 98% !important;}



.videoframe {
  position: relative;
  padding-top: calc(1 / 1 * 100%);
}

.videoframe iframe{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

.video-container {position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden; }

.video-container iframe, .video-container object, .video-container embed { position: absolute; top: 0; left: 0; width: 100%; height: 100%; }

video[poster]{
width:100%;
object-fit: cover;
}

.slide-txt {font-size:  20px; color: #FFFFFF; font-weight: 600; padding: 10px 65px; margin-top: 0px; line-height: initial !important;}

.w-100 {max-width: 100% !important;}

@media only screen and (max-width: 767px) {
  [class*="col-"] {
    width: 100%;
  }

  .slider--cover .slider__inner {
    height: 600px !important;
  }

.slide-txt {font-size:  16px; color: #FFFFFF; font-weight: 600; padding: 10px 25px; margin-top: 0px; line-height: initial !important;}  
}



.timeline {
  border-left: 4px solid #cee2d7;
  border-bottom-right-radius: 4px;
  border-top-right-radius: 4px;
  background: rgba(255, 255, 255, 0.03);
  margin: 50px auto;
  letter-spacing: 0.5px;
  position: relative;
  line-height: 1.4em;
  font-size: 1.03em;
  padding: 50px;
  list-style: none;
  text-align: left;
  font-weight: 100;

}
.timeline h1,
.timeline h2,
.timeline h3 {
  letter-spacing: 1.5px;
  font-weight: 100;
  font-size: 1.4em;
}
.timeline .event {
  border-bottom: 1px dashed rgba(255, 255, 255, 0.1);
  padding-bottom: 25px;
  margin-bottom: 50px;
  position: relative;
  list-style: none;
}
.timeline .event:last-of-type {
  padding-bottom: 0;
  margin-bottom: 0;
  border: none;
}
.timeline .event:before,
.timeline .event:after {
  position: absolute;
  display: block;
  top: 0;
}
.timeline .event:before {
  left: -217.5px;
  color: rgba(255, 255, 255, 0.4);
  content: attr(data-date);
  text-align: right;
  font-weight: 100;
  font-size: 0.9em;
  min-width: 120px;
}
.timeline .event:after {
  box-shadow: 0 0 0 4px #0c6c37;
  left: -57.85px;
  background: #0c6c37;
  border-radius: 50%;
  height: 11px;
  width: 11px;
  content: "";
  top: 5px;
}

.carousel, .carousel2 {
    position: relative;
    margin-top: 26px;
}

.carousel-inner, .carousel-inner2 {
    position: relative;
    overflow: hidden;
    width: 100%;
}

.carousel-open:checked + .carousel-item, .carousel-open:checked + .carousel-item2 {
    position: static;
    opacity: 100;
}

.carousel-item, .carousel-item2 {
    position: absolute;
    opacity: 0;
    -webkit-transition: opacity 0.6s ease-out;
    transition: opacity 0.6s ease-out;
}

.carousel-item img, .carousel-item2 img {
    display: block;
    height: auto;
    max-width: 100%;
}

.carousel-control, .carousel-control2 {
    background: rgba(0, 0, 0, 0.28);
    border-radius: 50%;
    color: #fff;
    cursor: pointer;
    display: none;
    font-size: 40px;
    height: 40px;
    line-height: 35px;
    position: absolute;
    top: 50%;
    -webkit-transform: translate(0, -50%);
    cursor: pointer;
    -ms-transform: translate(0, -50%);
    transform: translate(0, -50%);
    text-align: center;
    width: 40px;
    z-index: 10;
}

.carousel-control.prev, .carousel-control2.prev {
    left: 2%;
}

.carousel-control.next, .carousel-control2.next  {
    right: 2%;
}

.carousel-control:hover, .carousel-control2:hover {
    background: rgba(0, 0, 0, 0.8);
    color: #aaaaaa;
}

#carousel-1:checked ~ .control-1,
#carousel-2:checked ~ .control-2,
#carousel-3:checked ~ .control-3,
#carousel-4:checked ~ .control-4,
#carousel-12:checked ~ .control-1,
#carousel-22:checked ~ .control-2,
#carousel-32:checked ~ .control-3,
#carousel-13:checked ~ .control-1,
#carousel-23:checked ~ .control-2,
#carousel-33:checked ~ .control-3  {
    display: block;
}

.carousel-indicators {
    list-style: none;
    margin: 0;
    padding: 0;
    position: absolute;
    bottom: 2%;
    left: 0;
    right: 0;
    text-align: center;
    z-index: 10;
    display: none;
}

.carousel-indicators li {
    display: inline-block;
    margin: 0 5px;
}

.carousel-bullet {
    color: #fff;
    cursor: pointer;
    display: block;
    font-size: 35px;
}

.carousel-bullet:hover {
    color: #aaaaaa;
}

#carousel-1:checked ~ .control-1 ~ .carousel-indicators li:nth-child(1) .carousel-bullet,
#carousel-2:checked ~ .control-2 ~ .carousel-indicators li:nth-child(2) .carousel-bullet,
#carousel-3:checked ~ .control-3 ~ .carousel-indicators li:nth-child(3) .carousel-bullet,
#carousel-3:checked ~ .control-3 ~ .carousel-indicators li:nth-child(4) .carousel-bullet  {
    color: #428bca;
}

.slider {
  position: relative;
  max-width: 100%;
  max-height: 100%;
  margin: 0 auto;
}
.slider:hover .slider__radiobox-label--prev,
.slider:hover .slider__radiobox-label--next {
  opacity: 1;
}
.slider:hover .slider__radiobox-label--prev {
  left: 2%;
}
.slider:hover .slider__radiobox-label--next {
  right: 2%;
}
.slider--cover {
  width: 100vw;
}
.slider--fixed {
  width: 600px;
  height: 400px;
}
.slider--proportional {
  width: 100%;
  height: auto;
}

.slider__inner {
  position: relative;
  margin: 0 auto;
  overflow: hidden;
  background: #ddd;
}
.slider--cover .slider__inner {
  width: 100%;
  height: 300px;
}
.slider--fixed .slider__inner {
  width: 100%;
  height: 100%;
}
.slider--proportional .slider__inner {
  width: 100%;
  height: 0;
}
.slider--proportional-4x3 .slider__inner {
  padding-top: 75%;
}
.slider--proportional-5x4 .slider__inner {
  padding-top: 80%;
}
.slider--proportional-16x9 .slider__inner {
  padding-top: 56.25%;
}

.slider__slides {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1;
  width: 400%;
  height: 100%;
  overflow-y: hidden;
  transition: margin-left 0.4s;
}

.slider__slide {
  display: block;
  float: left;
  position: relative;
  width: 25%;
  height: 100%;
}
.slider__slide img {
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
     object-fit: cover;
}

.slider__radiobox-label {
  display: block;
  position: absolute;
  z-index: 2;
  cursor: pointer;
}
.slider__radiobox-label--item {
  bottom: 6%;
  left: 50%;
  transform: translateX(-50%);
  padding: 6px;
  border-radius: 50%;
  background: white;
  opacity: 0.3;
  transition: opacity 0.2s;
}
.slider__radiobox-label--item:hover {
  opacity: 0.5;
}
.slider__radiobox-label--item-1 {
  margin-left: -36px;
}
.slider__radiobox-label--item-2 {
  margin-left: -12px;
}
.slider__radiobox-label--item-3 {
  margin-left: 12px;
}
.slider__radiobox-label--item-4 {
  margin-left: 36px;
}
.slider__radiobox-label--prev, .slider__radiobox-label--next {
  display: none;
  top: 50%;
  transform: translateY(-50%);
  height: 0;
  border: 10px solid #FFF;
  border-top-color: transparent;
  border-bottom-color: transparent;
  opacity: 0;
  transition: left 0.2s, right 0.2s, opacity 0.2s;
}
.slider__radiobox-label--prev {
  left: -2%;
  border-left: 0;
  border-right-width: 17px;
}
.slider__radiobox-label--next {
  right: -2%;
  border-right: 0;
  border-left-width: 17px;
}

.slider__radiobox {
  display: none;
}
.slider__radiobox--1:checked ~ .slider__slides {
  margin-left: 0;
}
.slider__radiobox--2:checked ~ .slider__slides {
  margin-left: -100%;
}
.slider__radiobox--3:checked ~ .slider__slides {
  margin-left: -200%;
}
.slider__radiobox--4:checked ~ .slider__slides {
  margin-left: -300%;
}
.slider__radiobox--1:checked + .slider__radiobox-label--item-1, .slider__radiobox--2:checked + .slider__radiobox-label--item-2, .slider__radiobox--3:checked + .slider__radiobox-label--item-3, .slider__radiobox--4:checked + .slider__radiobox-label--item-4 {
  opacity: 1;
}
.slider__radiobox--1:checked ~ .slider__radiobox-label--prev-4, .slider__radiobox--1:checked ~ .slider__radiobox-label--next-2, .slider__radiobox--2:checked ~ .slider__radiobox-label--prev-1, .slider__radiobox--2:checked ~ .slider__radiobox-label--next-3, .slider__radiobox--3:checked ~ .slider__radiobox-label--prev-2, .slider__radiobox--3:checked ~ .slider__radiobox-label--next-4, .slider__radiobox--4:checked ~ .slider__radiobox-label--prev-3, .slider__radiobox--4:checked ~ .slider__radiobox-label--next-1 {
  display: block;
}

.rounded20 {
  -webkit-border-radius: 20px;
  -moz-border-radius: 20px;
  border-radius: 20px;
}

.instagram-media {margin: auto !important;}


</style>


<article style="max-width: 800px; width: 100%; margin: auto;">

<div style="width: 100%;">
  <a href="https://northwest.cdc.gov.sg/cohesion/november-2025/at-a-glance/">
    <img style="width: 100%; max-width: 100px; position: relative; float: left;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%;" src="https://northwest.cdc.gov.sg/images/Cohesion/January%202024/sustainable_communities.png">
  <img style="width: 100%;" src="/images/Cohesion/Nov%202025/title_low_waste.png">
</div>


<div style="padding: 15px 0px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Thoughtful choices can keep your festivities eco-friendly and low-waste! Whether it's family gatherings, a potluck party with neighbours or community socials, celebrate, feast, and gift the green way. 
</p>
</div>

<div class="" style="max-width: 100%; padding: 0px 0px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/tips_01.jpg">
</div>

<div style="width: 100%; background: #69B288;">
  <div style="width: 92%; background: #FFFFFF; margin: auto;" class="rounded20">
    <div style="width: 100%; padding: 0px 0px;">
      
      <div style="padding: 40px 20px 10px;">
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;"><b>1. Gift with purpose</b></p> 
      <img style="width: 100%; padding: 10px 0px 0px;" class="" src="/images/Cohesion/Nov%202025/tip1.jpg">
      <p style="font-size: 16px; line-height: 26px; text-align: justify;">Are gifts a part of your festive tradition? Skip store-bought items with lots of packaging. Instead, choose low-waste options like DIY creations, homemade treats, or practical items that your recipient truly needs. To reduce packaging waste, wrap gifts in recycled paper or put them in reusable bags. </p>
      </div>

      <div style="padding: 10px 20px;">
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;"><b>2. Reuse decorations</b></p> 
      <img style="width: 100%; padding: 10px 0px  0px;" class="" src="/images/Cohesion/Nov%202025/tip2.jpg">
      <p style="font-size: 16px; line-height: 26px; text-align: justify;">Reuse what you already have, upcycle ornaments or craft your own décor from recycled materials. Borrow extra decorations from friends or family instead of buying new. Avoid balloons and plastic decor.</p>
      </div>

      <div style="padding: 10px 20px;">
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;"><b>3. Feast with less waste</b></p> 
      <img style="width: 100%; padding: 10px 0px 0px;" class="" src="/images/Cohesion/Nov%202025/tip3.jpg">
      <p style="font-size: 16px; line-height: 26px; text-align: justify;">Plan your menu without creating the waste. Try to use every part of your ingredients – for example, veggie peels, meat bones or scraps can become soups or tasty new dishes. Need ideas? Check out zero-waste recipes online. Or why not go for a low-waste potluck with coordinated dishes, and have everyone bring reusable containers for leftovers. </p>
      </div>

      <div style="padding: 10px 20px;">
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;"><b>4. Skip disposables</b></p> 
      <img style="width: 100%; padding: 10px 0px 0px;" class="" src="/images/Cohesion/Nov%202025/tip4.jpg">
      <p style="font-size: 16px; line-height: 26px; text-align: justify;">Avoid single-use party supplies like disposable plates, cups and cutlery. Use reusable tableware or have your guests bring their own plates, instead of buying new.</p>
      </div>

      <div style="padding: 10px 20px;">
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;"><b>5. Sort smart</b></p> 
      <img style="width: 100%; padding: 10px 0px 0px;" class="" src="/images/Cohesion/Nov%202025/tip5.jpg">
      <p style="font-size: 16px; line-height: 26px; text-align: justify;">Set up clearly labelled sorting stations for recycling, compost, and trash to help your guests dispose of waste properly after the festivities. Take this chance to educate your guests on what goes where to make sorting easier. This will help keep waste to a minimum.</p>
      </div>

      <div style="padding: 10px 20px;">
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;"><b>6. Switch to LED lights</b></p> 
      <img style="width: 100%; padding: 10px 0px 0px;" class="" src="/images/Cohesion/Nov%202025/tip6.jpg">
      <p style="font-size: 16px; line-height: 26px; text-align: justify;">Light up your festive celebrations the smart and sustainable way by choosing LED lights! They use less energy, last longer, and save you money. Tip: Cut your energy use with LED lights and join Reduce @ North West for a chance to win shopping vouchers!</p>
      </div>

    </div>
  </div>
</div>

<div class="" style="max-width: 100%; padding: 0px 0px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/tips_03.jpg">
</div>


<div style="padding: 50px 0px 15px;">
  <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;"><b>Going green starts with small, simple actions</b></p> 
</div>

<div class="" style="max-width: 100%; padding: 0px 0px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/quote_vanessa.jpg">
</div>





<div style="background: #196C37; margin: 30px 0px 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px; -moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;">
  <div style="text-align: left; display: flex; margin: 0px auto; padding: 20px 35px 18px; color: #FFFFFF; font-size: 18px; font-weight: bold; font-family: Arial, 'sans-serif;';">
          <b style="font-weight: bold; color: #FFFFFF;">Go Green in the North West</b>
  </div>
</div>

<div style="padding: 20px 30px 20px; background: #DCEAE3; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">

  <div class="w-100">
    <p style="font-size: 16px; line-height: 18px; padding: 10px 5px 25px; margin: 0px 0px;">
      If you're inspired to live more sustainably, there are plenty of programmes designed to help you do just that, right here in #OurNorthWest! 
    </p>
    <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/categories.png">
  </div>

  <div style="display: inline-block; padding: 20px 0px;" class="w-100">

    <div style="padding: 4px 0px;" class="col-12">
      <div class="col-4">
        <a target="_new" href="https://northwest.cdc.gov.sg/programmes/advocating-green-living/north-west-sustainability-festival/">
        <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/box1.png"></a>
      </div>
      <div class="col-4">
        <a target="_new" href="https://northwest.cdc.gov.sg/programmes/bonding-the-people/recycle-at-northwest/">
        <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/box2.png"></a>
      </div>
      <div class="col-4">
        <a target="_new" href="https://northwest.cdc.gov.sg/programmes/bonding-the-people/waterways-cleanup-northwest/">
        <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/box3.png"></a>
      </div>
    </div>

    <div style="padding: 4px 0px;" class="col-12">
      <div class="col-4">
        <a target="_new" href="https://northwest.cdc.gov.sg/programmes/bonding-the-people/greenhomes-at-northwest/">
        <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/box4.png"></a>
      </div>
      <div class="col-4">
        
        <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/box5.png">
      </div>
      <div class="col-4">
        <a target="_new" href="https://northwest.cdc.gov.sg/programmes/bonding-the-people/reduce-at-northwest/">
        <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/box6.png"></a>
      </div>
    </div>

    <div style="padding: 4px 0px;" class="col-12">
      <div class="col-4">
        <a target="_new" href="https://northwest.cdc.gov.sg/programmes/advocating-green-living/budding-greenies-at-north-west/">
        <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/box7.png"></a>
      </div>
      <div class="col-4">
        <a target="_new" href="https://northwest.cdc.gov.sg/programmes/advocating-green-living/greenbootcamp-nw/">
        <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/box8.png"></a>
      </div>
      <div class="col-4">
        <a target="_new" href="https://northwest.cdc.gov.sg/programmes/bonding-the-people/northwest-giraffe-fund/">
        <img style="width: 100%;" class="" src="/images/Cohesion/Nov%202025/box9.png"></a>
      </div>
    </div>

  </div>

  <div class="w-100">
    <p style="color: #086B37; font-size: 18px; font-weight: bold; line-height: 18px; padding: 10px 5px; margin: 0px 0px;">
      Kick Start Your Sustainability Journey in #OurNorthWest Today!
    </p>
    <p style="font-size: 16px; line-height: 18px; padding: 10px 5px 25px; margin: 0px 0px;">
      Follow our <a style="font-weight: bold; color: #086B37" target="_new" href="https://www.facebook.com/nwcdc">Facebook</a> and <a style="font-weight: bold; color: #086B37" target="_new" href="https://www.instagram.com/northwestcdc/">Instagram</a> to stay up to date on our latest green initiatives in the North West! 
    </p>
  </div>





  <div class="rounded20" style="max-width: 100%; background: #EAF3EE; padding: 10px 20px;">
    <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px; margin: 0px;">
      <em style="font-weight: normal; color: #196C37">More about this topic:</em></p>
    <hr style="margin: 10px 0px; color: #196C37;">
    <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px 0px 5px; margin: 0px; color: #196C37">
      &gt; &nbsp;<a target="new" style="font-family: 'Lato', sans-serif; font-size: 16px; line-height: 26px; font-weight: bold; color: #196C37; text-decoration: underline;" href="https://northwest.cdc.gov.sg/cohesion/september-2025/sust-fest/"><span style="text-decoration: underline;">Going Green in Style</span>
      </a>
    </p>
  </div>

</div>




<div style="padding: 20px 0px 0px; display: flex;" class="col-">&nbsp;</div>

<div style="width: 100%; background: #FB5C1F; border-radius: 30px; padding: 0px 0px; display: flex;">
  <div style="width: 100%; padding: 30px 10px 8px; text-align: center; margin: auto;">
    <h1 style="font-family:  Arial; font-size: xx-large; font-weight: bold; color: #FFFFFF; letter-spacing: normal !important;"><em>Keep updated with our latest stories!</em></h1>
    <a style="text-decoration: none;" target="_new" href="https://go.gov.sg/subscribe-cohesion">
      <div style="font-family:  Arial; font-size: large; font-weight: bold; background: #FFFFFF; color: #FB5C1F; padding: 10px 15px; max-width: 320px; margin: auto; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; text-decoration: none;"><em>Subscribe to Cohesion Magazine</em>
      </div>
    </a>

    <div style="width: 100%;">
    <div style="width: 100%; padding: 15px 10px; text-align: center;   display: flex; justify-content: center; align-items: center;">
      <span style="font-family: Arial; font-weight: bold; font-size: large; color: #FFFFFF;">Follow us on</span>
      <a target="_new" href="https://www.facebook.com/nwcdc/" style="line-height: normal !important; margin-bottom: 0px !important;"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-facebook.png"></a>
      <a target="_new" href="https://www.instagram.com/northwestcdc" style="line-height: normal !important; margin-bottom: 0px !important;"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-instagram.png"></a>
      <a target="_new" href="https://t.me/northwestcdc" style="line-height: normal !important; margin-bottom: 0px !important;"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/telegram.png"></a>
      <a target="_new" href="https://www.youtube.com/northwestcdc" style="line-height: normal !important; margin-bottom: 0px !important;"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-youtube.png"></a>
    </div>
    </div>

    <div style="width: 100%; text-align: right;"><img style="width: 25px; display: inline-block !important;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-arrow.png"></div>
  </div>
</div>

<div style="max-width: 800px; width: 100%; margin: auto; text-align: center;">
  <div style="width: 100%; padding: 20px 0px;">
  <h2 style="font-size: xx-large; font-weight: bold; color: #D5262B;"><em>Our Team</em></h2>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Adviser: Mayor Alex Yam</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Editorial Team: Garick Kea, Sim Chuan San, Steve Luo, Eric Liu, Charlene&nbsp;Koh, Gavin&nbsp;Chan</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Please send feedback, suggestions and comments to <a href="mailto:northwest_cdc@pa.gov.sg" target="_new" style="color: #E95E26; text-decoration: underline;">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Some articles in Cohesion are contributed by volunteers and<br>are not necessarily opinions/comments by North&nbsp;West&nbsp;CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Reproduction in whole or in part is prohibited without prior permission from North&nbsp;West&nbsp;CDC.</p>
  </div>
</div>




</article>

