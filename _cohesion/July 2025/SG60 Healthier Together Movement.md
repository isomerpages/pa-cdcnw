---
title: SG60 Healthier Together Movement
permalink: /sg60-healthier-together-movement/
variant: markdown
description: ""
third_nav_title: July 2025
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

.float-left {float: left;}

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
#carousel-3:checked ~ .control-3 ~ .carousel-indicators li:nth-child(3) .carousel-bullet {
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
  <a href="https://northwest.cdc.gov.sg/cohesion/july-2025/at-a-glance/">
    <img style="width: 100%; max-width: 100px; position: relative; float: left;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%;" src="https://northwest.cdc.gov.sg/images/Cohesion/January%202024/healthy_communities.png">
  <img style="width: 100%;" alt="" src="/images/Cohesion/July%202025/title_healthier_together.jpg">
</div>

<div style="max-width: 100%; padding: 20px 0px 10px;" class="">
  <img src="/images/Cohesion/July%202025/healthier_together_kv.gif" class="rounded20" style="width: 100%;">
</div>

<div style="padding: 20px 0px 20px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;">The SG60 Healthier Together Movement was an awesome way to bring the North West community together – getting active while celebrating Singapore's 60th birthday! 
<br><br>
From 1 May to 1 June 2025, residents walked, ran, swam and cycled their way to better health! Together, we clocked over 88,502km of fitness activities! That's far beyond the original goal of 60,000km. Every KM count, and those who participated made this possible!</p>
</div>

<div style="max-width: 100%; padding: 20px 0px 10px;" class="">
  <img src="/images/Cohesion/July%202025/sg60_healthier_numbers.jpg" class="" style="width: 100%;">
</div>

<div style="padding: 20px 0px 0px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;"><span style="color: #F96B8D; font-weight: 900;">Bonus:</span> Achieving the goal also unlocked a $60,000 donation from Lih Ming Construction to support Club 100 @ North West!</p>
</div>

<div style="max-width: 100%; padding: 10px 0px 10px;" class="">
  <img src="/images/Cohesion/July%202025/WhatsApp_Image_2025_07_09_at_22_31_54.jpg" class="" style="width: 100%;">
</div>


<div style="padding: 20px 0px 20px;">
<p style="font-size: 20px; font-weight: bold; text-align: left; color: #FF5C83; margin: 10px 0px;">Meet one of our top fitness pace setters</p>

<p style="font-size: 16px; line-height: 26px; text-align: justify;">Be inspired by Simon Chua! With a distance of 680km, he secured the #2 spot for total distance covered in the Healthier Together Movement!</p>
</div>

<div style="max-width: 100%; padding: 0px 0px;" class="">
  <img src="/images/Cohesion/July%202025/quote_cycling.jpg" class="" style="width: 100%;">
</div>
<div style="padding: 20px 30px 40px; background: #FEF2FD;  -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">
<img align="left" style="max-width: 33.3%; padding: 0px 15px 10px 0px;" src="/images/Cohesion/July%202025/cycling_stats.jpg">
<p style="font-size: 20px; font-weight: bold; text-align: left; color: #FF5C83; margin: 0px 0px;">Favourite activity: </p>

<p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px 0px 10px; margin: 0px;">Cycling, hands down! I fell in love with pedalling during the COVID lockdown, and it's been my go-to ever since. </p>

<p style="font-size: 20px; font-weight: bold; text-align: left; color: #FF5C83; margin: 15px 0px 0px;">Training hours: </p>

<p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px 0px 10px; margin: 0px;">After 9.00pm or at the crack of dawn (4.30am!) – weather permitting! Traded Netflix binges and extra sleep for fresh air and the thrill of the ride! </p>

<p style="font-size: 20px; font-weight: bold; text-align: left; color: #FF5C83; margin: 15px 0px 0px;;">Why join the SG60 Healthier Together Movement?</p>

<p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px 0px 10px; margin: 0px;">To keep the fitness vibes high and add more fun to an already active lifestyle. Plus, contributing to the 60,000km target felt like joining a nationwide fitness party! </p>

<p style="font-size: 20px; font-weight: bold; text-align: left; color: #FF5C83; margin: 15px 0px 0px;;">Motivation fuel: </p>

<p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px 0px 10px; margin: 0px;">It started with "let's shed a few pounds" – but once I hit my target weight, it was all about staying fit and crushing personal goals. That kept me pedalling with a smile! </p>

<p style="font-size: 20px; font-weight: bold; text-align: left; color: #FF5C83; margin: 15px 0px 0px;;">Next fitness move: </p>

<p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px 0px 10px; margin: 0px;">I'm all for joining the North West Healthy Living Clubs. Count me in for brisk walking or running fun – the more action, the better! </p>
</div>





<div style="background: #F96B8D; margin: 30px 0px 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px; -moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;">
  <div style="text-align: left; display: flex; margin: 0px auto; padding: 20px 35px 18px; color: #FFFFFF; font-size: 18px; font-weight: bold; font-family: Arial, 'sans-serif;';">
          <strong style="font-weight: bold; color: #FFFFFF;">Get Moving to Stay Healthy </strong>
  </div>
</div>

<div style="padding: 20px 30px 20px; background: #FEF2FD; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">
  <div class="w-100">

    <p style="font-size: 16px; line-height: 26px; padding: 10px 5px 15px; margin: 0px 0px;">Unlock a whole new world of free classes available at the various North West Healthy Living Clubs!  From Brisk Walking and Running to Qigong and Tai Chi, as well as Dance Fit and FitnessX (HIIT, Fight-Do, Kpop Fitness and Zumba), explore each class and see how many you can tick off the list! 
      <br><br>
    <a style="font-weight: bold; color: #F96B8D; text-decoration: underline;" target="_new" href="https://form.gov.sg/647d8a160590a40012ff0128">Register here</a>.
    </p>

  <div style="max-width: 100%; background: #FDE7FC; padding: 10px 20px;" class="rounded20">
    <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px; margin: 0px;"><em style="font-weight: normal; color: #E66776;">More on this topic:</em></p>
    <hr style="margin: 10px 0px; color: #E66776;">
    <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px 0px 5px; margin: 0px; color: #E66776;">
      &gt; &nbsp;<a href="https://northwest.cdc.gov.sg/cohesion/january-2025/nw-hlc/" style="font-family: 'Lato', sans-serif; font-size: 16px; line-height: 26px; font-weight: bold; color: #E66776; text-decoration: underline;" target="new"><span style="text-decoration: underline;">Start Your Fitness Journey with North West Healthy Living Clubs </span>
      </a>
    </p>
  </div>




  </div>
</div>








<div style="padding: 20px 0px 0px; display: flex;" class="col-">&nbsp;</div>

<div style="width: 100%; background: #FB5C1F; border-radius: 30px; padding: 0px 0px; display: flex;">
  <div style="width: 100%; padding: 30px 10px 8px; text-align: center; margin: auto;">
    <h1 style="font-family:  Arial; font-size: xx-large; font-weight: bold; color: #FFFFFF; letter-spacing: normal !important; padding-bottom: 15px;"><em>Keep updated with our latest stories!</em></h1>
    <a style="text-decoration: none;" target="_new" href="https://go.gov.sg/subscribe-cohesion">
      <div style="font-family:  Arial; font-size: large; font-weight: bold; background: #FFFFFF; color: #FB5C1F; padding: 10px 15px; max-width: 320px; margin: auto; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; text-decoration: none;"><em>Subscribe to Cohesion Magazine</em>
      </div>
    </a>

    <div style="width: 100%;">
    <div style="width: 100%; padding: 15px 10px; text-align: center;   display: flex; justify-content: center; align-items: center;">
      <span style="font-family: Arial; font-weight: bold; font-size: large; color: #FFFFFF;">Follow us on</span>
      <a target="_new" href="https://www.facebook.com/nwcdc/" style="line-height: normal !important; margin-bottom: 0px !important;"><img style="padding: 5px 7px;" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-facebook.png"></a>
      <a target="_new" href="https://www.linkedin.com/company/north-west-community-development-council/posts/?feedView=all" style="line-height: normal !important; margin-bottom: 0px !important;"><img style="padding: 0px 7px; max-width: 33px;" src="/images/Cohesion/January%202025/linkedin_white.png"></a>
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