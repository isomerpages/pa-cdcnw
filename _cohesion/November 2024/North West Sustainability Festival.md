---
title: North West Sustainability Festival
permalink: /cohesion/november-2024/sust-fest/
variant: markdown
description: ""
third_nav_title: November 2024
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
  <a href="https://northwest.cdc.gov.sg/cohesion/november-2024/at-a-glance/">
    <img style="width: 100%; max-width: 100px; position: relative; float: left;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%;" src="https://northwest.cdc.gov.sg/images/Cohesion/January%202024/sustainable_communities.png">
  <img style="width: 100%;" src="/images/Cohesion/November%202024/title_5_tips.png">
</div>


<div style="padding: 20px 0px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;">If you want to make sustainability a way of life, the kitchen is a good place to start! In November, the North West Sustainability Festival 2024 served up a three-day extravaganza themed "Sustainability in Every Bite". Green workshops and demos by celebrity chefs, brought fresh ideas and useful tips on how residents can incorporate green habits in the kitchen.
<br><br>
Check out the top sustainability tips attendees picked up!
</p>
</div>

<div style="padding: 0px 0px;">
  <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;">
    1. Turn ugly foods into yummy foods
  </p> 
  <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 10px 0px 20px;
    margin: 0px;">One of the simplest ways to embrace sustainability is to go for "ugly" produce - yes, those wonky vegetables or oddball fruits that usually don’t make it to the shelves just because they don't look perfect. Contestants in the "Ugly Food Cook-Off: Save Me, I am Ugly but Tasty!" cooking contest found out that looking beyond the blemishes, these visually unappealing foods can be just as tasty and are packed with all the good stuff!
  </p>
</div>

<div class="" style="max-width: 100%; padding: 0px 0px 30px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/November%202024/quote1.gif">
</div>


<div style="padding: 0px 0px;">
  <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;">
    2. Embrace zero-waste kitchen hacks
  </p> 
  <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 10px 0px 20px; margin: 0px;">Meanwhile, the message from the "Zero Waste Cook-Off: From Waste to Taste" cooking contest was that every bit of food should count. To bring those zero-waste vibes into your kitchen, start by using the whole ingredient! For example, if you have a whole chicken, you can roast or steam it and save the bones for stock. Or if you have leftovers from other dishes, use them the next day instead of tossing them.
  </p>
</div>

<div class="" style="max-width: 100%; padding: 0px 0px 30px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/November%202024/quote2.gif">
</div>

<div style="padding: 0px 0px;">
  <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;">
    3. Don't toss food just because it has "expired"
  </p> 
  <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 10px 0px 20px; margin: 0px;">Think twice before throwing out food past its best before date on the label. It's all about knowing the difference between "best before", "use by" or "expiry date", plus understanding how different types of foods – like fresh produce, canned foods, and packaged foods – are made so you can assess their edibility. How long your food can last also depends on how you store it.
  </p>
</div>

<div class="" style="max-width: 100%; padding: 0px 0px 30px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/November%202024/quote3.jpg">
</div>

<div style="padding: 0px 0px;">
  <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;">
    4. Use beeswax wraps to cut down on plastic waste
  </p> 
  <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 10px 0px 20px; margin: 0px;">Did you know that there's an alternative to plastic wrap for covering food and bowls? Beeswax wrap is washable, reusable, and tear-resistant, making it the perfect eco-friendly choice to store your foods. You can even make your own and have fun doing so!
  </p>
</div>

<div class="" style="max-width: 100%; padding: 0px 0px 30px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/November%202024/quote4.gif">
</div>

<div style="padding: 0px 0px;">
  <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;">
    5. Make your fruit enzyme cleaners using fruit peel waste
  </p> 
  <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 10px 0px 20px; margin: 0px;">Here's another cool tip that participants at the "Multipurpose Fruit Enzymes Cleaner" workshop picked up: save your fruit peels and turn them into a natural cleaner for your kitchen! Mix them up to make a DIY enzyme that's eco-friendly and chemical free. You'll not only clean your space but also cut down on waste at the same time.
  </p>
</div>

<div class="" style="max-width: 100%; padding: 0px 0px 30px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/November%202024/quote5.gif">
</div>

<div style="padding: 20px 0px;">
  <p style="font-size: 20px; font-weight: bold; text-align: left; color: #086B37; margin: 0px 0px;">
    Here are more eco-friendly tips from celebrity chefs who conducted cooking demos at the Sustainability Festival. 
  </p> 
  <p style="font-size: 16px; line-height: 26px; text-align: justify;">Local Celebrity Ben Yeo demonstrates how to create his King Oyster Mushroom in Gong Bao Sauce using homegrown oyster mushrooms. 
  </p>
</div>

<div class="" style="max-width: 100%; padding: 0px 0px 0px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/November%202024/quote6.gif">
  <img style="width: 100%;" class="" src="/images/Cohesion/November%202024/quote6b.jpg">
</div>

<div style="padding: 20px 0px 0px;">
  <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 10px 0px 20px; margin: 0px;">Chef Benson Tong demonstrates how to cook plant-based dishes with low or no-added chemicals.
  </p>
</div>

<div style="max-width: 100%; padding: 0px 0px 30px;">
  <img style="width: 100%; -webkit-border-top-left-radius: 20px;
-webkit-border-top-right-radius: 20px;
-moz-border-radius-topleft: 20px;
-moz-border-radius-topright: 20px;
border-top-left-radius: 20px;
border-top-right-radius: 20px;" class="" src="/images/Cohesion/November%202024/quote7.gif">
  <img style="width: 100%;" class="" src="/images/Cohesion/November%202024/quote7b.jpg">
</div>


<div class="" style="max-width: 100%; padding: 2px 25px; background: #196C37; -webkit-border-top-left-radius: 20px; -webkit-border-top-right-radius: 20px; -moz-border-radius-topleft: 20px; -moz-border-radius-topright: 20px; border-top-left-radius: 20px; border-top-right-radius: 20px; color: #FFFFFF;">
  <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; padding: 15px 0px;">Take the #GetGreen Challenge</p>
</div>


<div class="" style="max-width: 100%; padding: 10px 25px 20px; background: #DCEAE3; -webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px; display: inline-block;">
  <p style="font-size: 16px; line-height: 26px; text-align: justify;">Feeling motivated to live more sustainably? Take your sustainability efforts further by tapping  on the <a style="text-decoration: underline; font-weight: bold; color: #086B37;" target="new" href="https://northwest.cdc.gov.sg/cohesion/july-2023/getgreen-challenge/">green&nbsp;programmes</a> available in your community! Find out more here.
  </p>



<div class="w-100 rounded20">
<div style="max-width: 100%;">
  <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/green-bingo.jpg" class="" style="width: 100%; margin-top: 0px;">
</div>
<div class="col-" style="max-width: 100%;">
  
  <div class="col- col-4" style="float: left; background: #CFEAE3; min-height: 340px;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px;">
      <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/icon1%20house.png" style="width:  100%; max-width: 40px; max-height: 40px; height: 100%; float: left; padding: 0px 10px 0px 0px;">
      <p style="font-size: 12px; margin: 0px; line-height: initial; color: #157577;">Level: Beginner</p>
      <p style="font-size: 16px; margin: 0px; line-height: initial; font-weight: bold;"><a href="https://go.gov.sg/nw-greenhomes" target="_new" style="color: #157577; text-decoration: underline;">Green Homes @ North&nbsp;West</a></p>
      </div>
      <div>
        <p style="line-height: initial; color: #157577;">Opt for reusable alternatives instead of single-use products. Bring your own tote bag for shopping and container for food takeaways.</p>
      </div>
    </div>
  </div>

  <div class="col- col-4" style="float: left; background: #E4F0ED; min-height: 340px;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px;">
      <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/icon1%20house.png" style="width:  100%; max-width: 40px; max-height: 40px; height: 100%; float: left; padding: 0px 10px 0px 0px;">
      <p style="font-size: 12px; margin: 0px; line-height: initial; color: #157577;">Level: Beginner</p>
      <p style="font-size: 16px; margin: 0px; line-height: initial; font-weight: bold;"><a href="https://go.gov.sg/nw-greenhomes" target="_new" style="color: #157577; text-decoration: underline;">Green Homes @ North&nbsp;West</a></p>
      </div>
      <div>
        <p style="line-height: initial; color: #157577;">Switch to energy and water-saving appliances. Qualify as a green home and stand to win shopping vouchers.</p>

        <p style="line-height: initial; color: #157577;"><i><a href="https://www.youtube.com/watch?v=QqeCQUSLKfg" target="_new" style="color: #157577; text-decoration: underline;">Tip: Watch this video to make the switch!</a></i></p>
      </div>
    </div>
  </div>

  <div class="col- col-4" style="float: left; background: #CFEAE3; min-height: 340px;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px;">
      <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/icon2%20bottle.png" style="width:  100%; max-width: 40px; max-height: 40px; height: 100%; float: left; padding: 0px 10px 0px 0px;">
      <p style="font-size: 12px; margin: 0px; line-height: initial; color: #157577;">Level: Beginner</p>
      <p style="font-size: 16px; margin: 0px; line-height: initial; font-weight: bold;"><a href="https://go.gov.sg/nw-recycle" target="_new" style="color: #157577; text-decoration: underline;">Recycle @ North&nbsp;West</a></p>
      </div>
      <div>
        <p style="line-height: initial; color: #157577;">Reduce fashion waste by exchanging clothes. Swap and shop (Shwap!) for a new wardrobe instead.</p>
      </div>
    </div>
  </div>

  <div class="col- col-4" style="float: left; background: #E4F0ED; min-height: 340px;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px;">
      <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/icon2%20bottle.png" style="width:  100%; max-width: 40px; max-height: 40px; height: 100%; float: left; padding: 0px 10px 0px 0px;">
      <p style="font-size: 12px; margin: 0px; line-height: initial; color: #157577;">Level: Beginner</p>
      <p style="font-size: 16px; margin: 0px; line-height: initial; font-weight: bold;"><a href="https://go.gov.sg/nw-recycle" target="_new" style="color: #157577; text-decoration: underline;">Recycle @ North&nbsp;West</a></p>
      </div>
      <div>
        <p style="line-height: initial; color: #157577;">Get your family involved and set up a recycling corner at home.</p> 

        <p style="line-height: initial; color: #157577;"><i>Tip: Don't throw your toilet rolls, put it to good use! </i></p>
      </div>
    </div>
  </div>

  <div class="col- col-4" style="float: left; background: #CFEAE3; min-height: 340px; display: flex;">
    <div class="w-100" style="padding: 15px 15px; margin: auto;">
      <img style="width: 100%; margin: auto;" class="" src="/images/Cohesion/November%202024/sustainable.png">
    </div>    
  </div>

  <div class="col- col-4" style="float: left; background: #E4F0ED; min-height: 340px;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px;">
      <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/icon3%20plant%20pot.png" style="width:  100%; max-width: 40px; max-height: 40px; height: 100%; float: left; padding: 0px 10px 0px 0px;">
      <p style="font-size: 12px; margin: 0px; line-height: initial; color: #157577;">Level: Intermediate</p>
      <p style="font-size: 16px; margin: 0px; line-height: initial; font-weight: bold;"><a href="https://go.gov.sg/nw-reduce" target="_new" style="color: #157577; text-decoration: underline;">Reduce @ North&nbsp;West</a></p>
      </div>
      <div>
        <p style="line-height: initial; color: #157577;">Pledge to save electricity and reduce food wastage. Cut your utilities bill by at least 5% over 4 months and you could receive $50 in e-vouchers. </p> 

        <p style="line-height: initial; color: #157577;"><i><a href="https://go.gov.sg/reduce-sign-up" target="_new" style="color: #157577; text-decoration: underline;">Apply here</a></i></p>
      </div>
    </div>  
  </div>

  <div class="col- col-4" style="float: left; background: #CFEAE3; min-height: 340px;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px;">
      <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/icon4%20lightning.png" style="width:  100%; max-width: 40px; max-height: 40px; height: 100%; float: left; padding: 0px 10px 0px 0px;">
      <p style="font-size: 12px; margin: 0px; line-height: initial; color: #157577;">Level: Advanced</p>
      <p style="font-size: 16px; margin: 0px; line-height: initial; font-weight: bold;"><a href="https://go.gov.sg/nw-nwsf" target="_new" style="color: #157577; text-decoration: underline;">North West Sustainability Forum</a></p>
      </div>
      <div>
        <p style="line-height: initial; color: #157577;">Join the sustainability conversation. Connect with experts and learn how you can be a change driver for green living.</p> 

        <p style="line-height: initial; color: #157577;"><i>Follow our <a href="https://www.facebook.com/nwcdc" target="_new" style="color: #157577; text-decoration: underline;">Facebook page</a> to 
find out more about the upcoming forums.</i></p>
      </div>
    </div>      
  </div>

  <div class="col- col-4" style="float: left; background: #E4F0ED; min-height: 340px;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px;">
      <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/icon5%20heart%20plant.png" style="width:  100%; max-width: 40px; max-height: 40px; height: 100%; float: left; padding: 0px 10px 0px 0px;">
      <p style="font-size: 12px; margin: 0px; line-height: initial; color: #157577;">Level: Advanced</p>
      <p style="font-size: 16px; margin: 0px; line-height: initial; font-weight: bold;"><a href="https://go.gov.sg/nw-giraffe" target="_new" style="color: #157577; text-decoration: underline;">North West GIRAFFE Fund </a></p>
      </div>
      <div>
        <p style="line-height: initial; color: #157577;">Have a green idea? Submit your proposal and apply for funding to bring your environmentally-friendly project to life.</p> 

      </div>
    </div>  
  </div>

  <div class="col- col-4" style="float: left; background: #CFEAE3; min-height: 340px;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px;">
      <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/icon6%20light%20bulb%20.png" style="width:  100%; max-width: 40px; max-height: 40px; height: 100%; float: left; padding: 0px 10px 0px 0px;">
      <p style="font-size: 12px; margin: 0px; line-height: initial; color: #157577;">Level: Advanced</p>
      <p style="font-size: 16px; margin: 0px; line-height: initial; font-weight: bold;"><a href="https://northwest.cdc.gov.sg/programmes/advocating-green-living/greenbootcamp-nw/" target="_new" style="color: #157577; text-decoration: underline;">Green Bootcamp @ North&nbsp;West</a></p>
      </div>
      <div>
        <p style="line-height: initial; color: #157577;">Green Bootcamp provides a series of trainings and workshops to help you generate ideas and develop solutions to address environmental issues. </p> 

        <p style="line-height: initial; color: #157577;"><i>Look out for the next Green Bootcamp @ North West on our <a href="https://www.facebook.com/nwcdc" target="_new" style="color: #157577; text-decoration: underline;">Facebook page</a>.</i></p>
      </div>
    </div>  
  </div>

</div>
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
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Editorial Team: Garick Kea, Sim Chuan San, Steve Luo, Eric Liu, Melvin&nbsp;Tai, Charlene&nbsp;Koh</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Please send feedback, suggestions and comments to <a href="mailto:northwest_cdc@pa.gov.sg" target="_new" style="color: #E95E26; text-decoration: underline;">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Some articles in Cohesion are contributed by volunteers and<br>are not necessarily opinions/comments by North&nbsp;West&nbsp;CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px; padding: 0px 20px;">Reproduction in whole or in part is prohibited without prior permission from North&nbsp;West&nbsp;CDC.</p>
  </div>
</div>



</article>


