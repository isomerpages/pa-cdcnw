---
title: North West WeCare Fund
permalink: /cohesion/september-2023/nw-wcf/
description: ""
third_nav_title: September 2023
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
  padding-top: calc(1 / 1.23 * 100%);
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
#carousel-4:checked ~ .control-4 ~ .carousel-indicators li:nth-child(4) .carousel-bullet {
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

.rounded25 {
  -webkit-border-radius: 25px;
  -moz-border-radius: 25px;
  border-radius: 25px;
}
</style>

<article style="max-width: 800px; width: 100%; margin: auto;">

<div style="width: 100%; padding-top: 15px;">
  <a href="#">
    <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif" style="width: 100%; max-width: 100px; position: relative; padding-left: 10px; float:left !important; padding-bottom: 20px;">
  </a>
</div>

<div style="width: 100%;">
  <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/enabling-partnerships-volunteerism.png" style="width: 100%; max-width:">
  <img src="/images/Cohesion/Sep%202023/famk-title.png" style="width: 100%; max-width:">
</div>

<div style="max-width: 100%; padding: 30px 0px 30px;" class="rounded20">

      <div style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="videoframe">
        <iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" class="rounded20" src="https://www.youtube.com/embed/gpKagvpXYTk?autoplay=1&amp;mute=1&amp;loop=1&amp;rel=0"></iframe>
      </div>

</div>



<div style="padding: 0px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold !important; font-size: x-large; margin: 0px 0px;">
  <strong>Enriching the lives of the silver generation through community activities for social engagement and intergenerational bonding.</strong>
</h2>
</div>

<div style="padding: 0px 0px 30px;">
<p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">At the third run of the FAM K @ North West, a community initiative supported by the North West WeCare Fund, elderly residents from Sembawang Central Zone ‘K’ had a fun day out celebrating National Day through fitness, arts and music.</p>

<p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">We speak to a resident to find out her experience at the event.</p>
</div>

<div style="padding: 0px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold !important; font-size: x-large; margin: 0px 0px;">
  <strong>Healthy Body, Healthy Mindset at  FAM K @ North West</strong>
</h2>
</div>

<div style="max-width: 100%; padding: 20px 0px;" class="rounded20">
  <img src="/images/Cohesion/Sep%202023/famk-quote.png" class="rounded20" style="width: 100%; margin-top: 0px;">
</div>

<div style="max-width: 100%; padding: 20px 0px;" class="rounded20">
  <img src="/images/Cohesion/Sep%202023/famk-timeline2.jpg" class="rounded20" style="width: 100%; margin-top: 0px;">
</div>

<div style="max-width: 100%; padding: 20px 0px;" class="rounded20">
  <img src="/images/Cohesion/Sep%202023/famk-infographics.png" class="rounded20" style="width: 100%; margin-top: 0px;">
</div>

<div style="max-width: 100%; padding: 30px 0px 0px;" class="rounded20">
  <img src="/images/Cohesion/Sep%202023/famk-committee.png" class="rounded20" style="width: 100%; margin-top: 0px;">
  <figcaption class="w-100" style="text-align: center; padding: 5px 0px; margin:  auto; max-width: 450px !important; font-family: 'Lato', sans-serif !important;"><i>FAM K @ North West National Day 2023 Organising Committee Loh&nbsp;Han Kiat, 24 years old and Ho Lingyan Joyce, 24 years old</i></figcaption> 
</div>


<div style="padding: 20px 0px; margin: 0px 0px;">
<div class="rounded20" style="width: 100%; background: #F5E1E0; padding: 0px 0px 0px;">
  <div style="padding: 20px 20px 40px;">
    <div style="padding: 0px 0px;">
      <img src="https://northwest.cdc.gov.sg/images/Cohesion/July%202023/quote%20inverted%20commas%20.png" style="width: 100%; padding: 0px 0px 10px; max-width: 60px; display: inline-flex;">

        <div class="w-100" style="padding: 0px 40px 40px; max-width: 650px !important; margin: auto;">
        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;"><strong>“For each FAM K @ North West event, we strive to deliver a refreshing experience to our elderly residents. We put in a lot of effort to organise a diverse range of performances that represent our multiracial and multicultural society. If you’re keen to be a catalyst of change in the community, build strong relationships with community stakeholders and let your voice be heard. Together, we can all make a difference!”</strong></p> 

        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; padding: 20px 0px 0px;">
          <i>Loh Han Kiat<br>
Secretary, Sembawang Central Zone ‘K’ Residents Network</i>  
        </p>
        </div>

      <div style="width: 25px; text-align: right; float: right;
    display: inline-flex;
    margin-bottom: 30px;"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-arrow.png" style="width: 25px;"></div>
  </div>
</div>
</div>
</div>


<div style="padding: 30px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold !important; font-size: x-large; margin: 0px 0px;">
  <strong>FAM K @ North West, National Day 2023</strong>
</h2>
<div style="margin: 20px auto; text-align: center;" class="">
  <iframe allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowfullscreen="true" frameborder="0" scrolling="no" style="border:none;overflow:hidden" height="891" width="500" src="https://www.facebook.com/plugins/video.php?height=476&amp;href=https%3A%2F%2Fwww.facebook.com%2Fnwcdc%2Fvideos%2F804385274696628%2F&amp;show_text=false&amp;width=267&amp;t=0"></iframe>
</div>
</div>

<div style="padding: 30px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold !important; font-size: x-large; margin: 0px 0px;">
  <strong>FAM K @ North West, CNY 2023</strong>
</h2>
<div style="margin: 20px auto; text-align: center;" class="">
<iframe allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowfullscreen="true" frameborder="0" scrolling="no" style="border:none;overflow:hidden" height="787" width="500" src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2FSembZoneK%2Fposts%2Fpfbid02MMz8888EpVsBkxBLbzmaWgVeiUjEypHA3MpJqMUX9rhgdhY2gZjMpajrB6tQwCRAl&amp;show_text=true&amp;width=500"></iframe>
</div>
</div>

<div style="padding: 30px 0px 0px;">
<h2 style="color: #D5262B; font-weight: bold !important; font-size: x-large; margin: 0px 0px;">
  <strong>FAM K @ North West, National Day 2022</strong>
</h2>
<div style="margin: 20px auto; text-align: center;" class="">
<iframe allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowfullscreen="true" frameborder="0" scrolling="no" style="border:none;overflow:hidden" height="761" width="500" src="https://www.facebook.com/plugins/post.php?href=https%3A%2F%2Fwww.facebook.com%2FSembZoneK%2Fposts%2Fpfbid0Uc1VJ3NibqdsbPq6NeQwka7iZj7QtYN7YSaaYb19cB2GsFGw5uRnBmcBKYrKRy3sl&amp;show_text=true&amp;width=500"></iframe>
</div>
</div>




<!--CTA-->
<div style="width: 100%; background: #F5E1E0; padding: 15px 0px; margin: 25px 0px; display: flex;" class="rounded20">
    <div style="padding: 20px 40px;">
      <div style="background-image: url('/images/Cohesion/Sep%202023/we-care-logo.png'); background-color: #F5E1E0; background-blend-mode: darken; min-height: 85px; background-repeat: no-repeat; background-size: contain; margin-left: 0px; padding-bottom: 15px;">
      </div>
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #D5262B; margin: 0px 0px; padding-top: 15px;"><strong>Let’s Build a Caring and Healthy North West community together! </strong>
      </p> 

      <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">Do you feel inspired to make a difference in the North West community? Take the lead in organising your very own community initiative!</p> 

      <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">The North West WeCare Fund provides funding for passionate individuals and groups who wish to serve the community. If you have a great idea, we want to hear from you. Discover how you can apply for&nbsp;funding <a href="https://go.gov.sg/nw-wecare-fund" target="_new" style="font-weight: bold; color: #D5262B;">here</a>.</p>  
      </div>
    </div>  

<!--CTA End-->










<!--Footer-->
<div class="col-" style="padding: 10px 0px 0px; display: flex;">&nbsp;</div>

<div style="width: 100%; background: #FB5C1F; border-radius: 30px; padding: 0px 0px; display: flex;">
  <div style="width: 100%; padding: 30px 10px 8px; text-align: center; margin: auto;">
    <h1 style="font-family:  Arial; font-size: xx-large; font-weight: bold; color: #FFFFFF; letter-spacing: normal !important; margin: 15px 0px;"><em>Keep updated with our latest stories!</em></h1>
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

<div style="padding: 40px 20px; text-align: center;">
  <h2 style="font-size: xx-large; font-weight: bold;"><em>Our Team</em></h2>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Adviser: Mayor Alex Yam</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Editorial Team: Michael Lau, Sim Chuan San, Steve Luo, Eric Liu, Melvin Tai, Charlene Koh</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Please send feedback, suggestions and comments to <a href="mailto:northwest_cdc@pa.gov.sg" target="_new" style="color: #000000; text-decoration: underline;">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Some articles in Cohesion are contributed by volunteers and are not necessarily opinions/comments by North&nbsp;West&nbsp;CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Reproduction in whole or in part is prohibited without prior permission from North West CDC.</p>
</div>
<!--Footer End-->


</article>