---
title: July At A Glance
permalink: /cohesion/july-2025/at-a-glance/
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

.col-1, .col-2, .col-3, .col-4, .col-5, .col-6, .col-7, .col-8, .col-9, .col-10, .col-11, .col-12 {float: left;}
.w-100 {width: 100%;}
.text-center {text-align: center;}

.slide-txt {font-size:  20px; color: #FFFFFF; font-weight: 600; padding: 10px 65px; margin-top: 0px; line-height: initial !important;}

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
  </style>


<article style="max-width: 800px; width: 100%; margin: auto;">

<div style="margin: 30px 10px 0px; -webkit-border-radius: 35px; -moz-border-radius: 35px; border-radius: 35px;">

    <div style="width: 100%; display: inline-block; padding: 10px 0px 30px;">
      <a href="https://northwest.cdc.gov.sg/cohesion/july-2025/at-a-glance/">
        <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif" alt="North West Cohesion" style="width: 100%; max-width: 100px; position: relative; padding-left: 0px; float:left !important; padding-bottom: 0px;">
      </a>
    </div>


    <div style="width: 100%;">
      <img style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="" src="/images/Cohesion/July%202025/healthier_together_kv.gif">
    </div>

  <div style="background: #F8F8F8; padding: 30px 30px; -webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px;">
    <h2 style="color: #F96B8D; font-weight: bold; font-size: x-large; text-align: center; margin: 10px;">
      <em>Healthier Together: Move More, Live Better!</em>
    </h2>

    <p style="font-size: 16px; line-height: 26px; text-align: center;">The SG60 Healthier Together wrapped up with almost 90,000km achieved collectively by our amazing North West community! See who topped the charts for better health.</p>

    <div style="max-width: 100%; text-align: center; padding: 10px 15px 15px;"><a style="background: #F96B8D; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px; display: inline-block; text-align: center;" href="https://northwest.cdc.gov.sg/sg60-healthier-together-movement/"><em>Explore The Highlights</em></a></div>
  </div>
  </div>


<div style="width: 100%; display: inline-block;">

  <div class="col-6">
  <div style="max-width: 100%; padding: 10px 10px;">
    <div style="max-width: 100%; padding: 0px 0px 0px; background: #FFFFFF; margin: 30px 0px 0px; -webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px;">
  <div style="width: 100%;">
    <img style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="" src="/images/Cohesion/July%202025/edm_kv_healthy_living.jpg">
  </div>
  <div style="background: #F8F8F8; padding: 10px 20px 30px; -webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px; min-height: 300px; position: relative; text-align: center;">
    <h2 style="color: #F96B8D;font-weight: bolder;font-size: 20px;line-height: initial;font-style: italic;margin: 15px 0px;">
      Catching the Best Vibes From the
Healthy Living Festival @ North West 
    </h2>
    <p style="font-size: 16px; line-height: 20px; margin: 10px 0px;">Take a look back at the exciting activities and joyful energy that made the Healthy Living Festival @ North West a fun-filled event for visitors of all ages!</p> 

    <div style="width: 100%; text-align: center; display: inline-flex; margin: 0px auto;">
    <div style="max-width: 100%; text-align: center; padding: 10px 15px 0px; margin: 0px auto;"><a style="background: #F96B8D; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px; display: inline-block; text-align: center; font-style: italic;" href="https://northwest.cdc.gov.sg/cohesion/july-2025/hlf-nw/">Relive The Fun</a>
    </div>
    </div>
  </div>
  </div>
  </div>
  </div>

  <div class="col-6">
  <div style="max-width: 100%; padding: 10px 10px;">
    <div style="max-width: 100%; padding: 0px 0px 0px; background: #FFFFFF; margin: 30px 0px 0px; -webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px;">
  <div style="width: 100%;">
    <img style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="" src="/images/Cohesion/July%202025/edm_kv_project_sama.jpg">
  </div>
  <div style="background: #F8F8F8; padding: 10px 20px 30px; -webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px; min-height: 300px; position: relative; text-align: center;">
    <h2 style="color: #DA312C;font-weight: bolder;font-size: 20px;line-height: initial;font-style: italic;margin: 15px 0px;">
      Assistance is Now a QR Scan Away!
    </h2>
    <p style="font-size: 16px; line-height: 20px; margin: 10px 0px;">Project Sama Sama @ North West has officially launched! With the support of our partners and sponsors, more residents will receive help with daily essentials to cope with the rising cost of living.</p> 

    <div style="width: 100%; text-align: center; display: inline-flex; margin: 0px auto;">
    <div style="max-width: 100%; text-align: center; padding: 10px 15px 0px; margin: 0px auto;"><a style="background: #DA312C; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px; display: inline-block; text-align: center; font-style: italic;" href="https://northwest.cdc.gov.sg/project-sama-sama-north-west/">Support The Cause</a>
    </div>
    </div>


  </div>
  </div>
  </div>
  </div>

</div>


<div style="width: 100%; display: inline-block;">

  <div class="col-6">
  <div style="max-width: 100%; padding: 10px 10px;">
    <div style="max-width: 100%; padding: 0px 0px 0px; background: #FFFFFF; margin: 30px 0px 0px; -webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px;">
  <div style="width: 100%;">
    <img style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="" src="/images/Cohesion/July%202025/edm_kv_learning.jpg">
  </div>
  <div style="background: #F8F8F8; padding: 10px 20px 0px; -webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px; min-height: 340px; position: relative; text-align: center; min-height: 315px;">
    <h2 style="color: #1F4D7F;font-weight: bolder;font-size: 20px;line-height: initial;font-style: italic;margin: 15px 0px;">
      Why Lifelong Learning
Matters More Than Ever
    </h2>
    <p style="font-size: 16px; line-height: 20px; margin: 10px 0px;">Discover key takeaways from Learning Neighbourhood @ North West. Participants at this learning roadshow highlighted the importance of lifelong learning and digital upskilling in today's tech-driven world.</p> 


    <div style="width: 100%; text-align: center; display: inline-flex; margin: 0px auto;">
    <div style="max-width: 100%; text-align: center; padding: 10px 15px 0px; margin: 0px auto;"><a style="background: #1F4D7F; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px; display: inline-block; text-align: center; font-style: italic;" href="https://northwest.cdc.gov.sg/learning-neighbourhood-north-west-2025/">Keep On Learning</a>
    </div>
    </div>
  </div>
  </div>
  </div>
  </div>

  <div class="col-6">
  <div style="max-width: 100%; padding: 10px 10px;">
    <div style="max-width: 100%; padding: 0px 0px 0px; background: #FFFFFF; margin: 30px 0px 0px; -webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px;">
  <div style="width: 100%;">
    <img style="width: 100%; margin-top: 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px;-moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;" class="" src="/images/Cohesion/July%202025/edm_kv_11.jpg">
  </div>
  <div style="background: #F8F8F8; padding: 10px 20px 0px; -webkit-border-bottom-right-radius: 25px; -webkit-border-bottom-left-radius: 25px; -moz-border-radius-bottomright: 25px; -moz-border-radius-bottomleft: 25px; border-bottom-right-radius: 25px; border-bottom-left-radius: 25px; min-height: 315px; position: relative; text-align: center;">
    <h2 style="color: #7B669E;font-weight: bolder;font-size: 20px;line-height: initial;font-style: italic;margin: 15px 0px;">
      11 Free ArtsEverywhere@CDC
Performances to Get Excited About
    </h2>
    <p style="font-size: 16px; line-height: 20px; margin: 10px 0px;">From vibrant large productions to lively street acts that showcase local talent and captivating artistry, catch a wide variety of ArtsEverywhere@CDC performances in your neighbourhood.</p> 


    <div style="width: 100%; text-align: center; display: inline-flex; margin: 0px auto 25px;">
    <div style="max-width: 100%; text-align: center; padding: 20px 15px 0px; margin: 0px auto;"><a style="background: #7B669E; color: #FFFFFF; padding: 15px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; font-size: medium; font-family: Arial, 'sans-serif;'; text-decoration: none; text-transform: uppercase; min-width: 150px; display: inline-block; text-align: center; font-style: italic;" href="https://northwest.cdc.gov.sg/artseverywhere-cdc/">Enjoy For Free</a>
    </div>
    </div>

  </div>
  </div>
    </div>
  </div>
  

</div>








<div style="max-width: 100%; padding: 10px 0px;" class="col-12">
  <div style="background: #FFFFFF; margin: 30px 10px 0px; -webkit-border-radius: 25px; -moz-border-radius: 25px; border-radius: 25px;">
    <div style="width: 100%;">
      <div style="background: #FE5D1F; margin: 30px 0px 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px; -moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;">
        <div style="text-align: center; display: flex; justify-content: center; align-items: center; margin: 0px auto; padding: 15px 15px; color: #FFFFFF; text-transform: uppercase; font-size:  x-large; font-weight: bold; font-family: Arial, 'sans-serif;';"><strong style="font-weight: bold;
    color: #FFFFFF;
    font-style: italic;">What's Up</strong> <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-arrow.png" style="padding: 0px 10px; max-width: 40px; width: 40px; margin: 0px 0px;"></div>
      </div>
    </div>

    <div style="width: 100%; padding: 10px 0px; display: inline-block; background: #F8F8F8; -webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">

    <div class="col-12 w-100">

    <div style="padding: 10px 20px 20px;">

      <div style="background: #FFFFFF; padding: 20px 0px; margin-bottom: 10px; display: inline-block;" class="w-100 rounded20">

      <div style="padding: 0px 15px 5px;" class="col-12 w-100">
      <div class="col-3 text-center">
        <div style="padding: 20px 0px 0px;">
          <img class="rounded20" style="max-width: 140px;" src="/images/Cohesion/July%202025/edm_wu_1.jpg">
        </div>
      </div>
      <div class="col-9">
        <div style="padding: 20px 2rem 10px;">
          <h2 style="color: #FE5D1F; font-weight: bolder; font-size: 20px;line-height: initial;font-style: italic; margin: 0px;"><i>SkillsFuture Festival @ North West  </i></h2>

          <span style="color: #FE5D1F; margin: 0px; letter-spacing: 0px; font-size: 16px; line-height: 22px; font-weight: bold; font-family: Arial, 'sans-serif;';"><i>Date: 2 to 3 August 2025<br>
Time: 10am to 7pm <br>
Venue: Causeway Point, Level 1 Atrium</i></span>


          <p style="font-size: 16px; line-height: 20px; padding: 12px 0px; margin: 0px;">Dive into immersive activities that'll give you a taste of in-demand skills in the fast-growing Digital, Green, and Care economies. Meet training providers and education experts who can help you upskill, pivot or discover new career paths! This is your chance to level up your future! Don't miss out.</p>

        </div>
      </div>
      </div>

      </div>



      <div style="background: #FFFFFF; padding: 20px 0px; margin-bottom: 10px; display: inline-block;" class="w-100 rounded20">

      <div style="padding: 0px 15px 5px;" class="col-12 w-100">
      <div class="col-3 text-center">
        <div style="padding: 20px 0px 0px;">
          <img style="max-width: 140px;" class="rounded20" src="/images/Cohesion/July%202025/edm_wu_2.jpg">
        </div>
      </div>
      <div class="col-9">
        <div style="padding: 20px 2rem 10px;">
          <h2 style="color: #FE5D1F; font-weight: bolder; font-size: 20px;line-height: initial;font-style: italic; margin: 0px;"><i>North West Sustainability Festival</i></h2>

          <span style="color: #FE5D1F; margin: 0px; letter-spacing: 0px; font-size: 16px; line-height: 22px; font-weight: bold; font-family: Arial, 'sans-serif;';"><i>Date: 29 to 30 August 2025<br> 
Time: 11am to 9pm<br>
Venue: Northpoint City, South Atrium</i></span>

          <p style="font-size: 16px; line-height: 20px; padding: 12px 0px; margin: 0px;">Ready to play your part in creating a greener future? Pick up smart recycling tips and get inspired by green champions who are passionate about saving the planet. Plus, get hands-on with creative DIY projects and discover how you can give old things a new lease of life! Don't just recycle – upcycle and rethink your way to a greener tomorrow! </p>

          

        </div>
      </div>
      </div>
      </div>


      <div style="background: #FFFFFF; padding: 20px 0px; margin-bottom: 10px; display: inline-block;" class="w-100 rounded20">

      <div style="padding: 0px 15px 5px;" class="col-12 w-100">
      <div class="col-3 text-center">
        <div style="padding: 20px 0px 0px;">
          <img style="max-width: 140px;" class="rounded20" src="/images/Cohesion/July%202025/edm_wu_3.jpg">
        </div>
      </div>
      <div class="col-9">
        <div style="padding: 20px 2rem 10px;">
          <h2 style="color: #FE5D1F; font-weight: bolder; font-size: 20px;line-height: initial;font-style: italic; margin: 0px;"><i>Let’s Celebrate Singapore’s Cultural Diversity</i></h2>


          <p style="font-size: 16px; line-height: 20px; padding: 12px 0px; margin: 0px;">For over 65 years, People's Association has walked alongside fellow Singaporeans to build a multi-racial and multi-cultural community and remains committed to this cause. Explore racial harmony-related programmes organised by grassroots organisations this July <a style="color: #FE5D1F; text-decoration: underline;" href="https://www.pa.gov.sg/our-programmes/racial-harmony/racial-harmony-day/"><i>here</i></a>.</p>

          <p style="font-size: 14px; line-height: 20px; padding: 12px 0px; margin: 0px; font-style: italic;">Image Source: <a style="color: #FE5D1F; text-decoration: underline;" href="https://www.sg60.gov.sg/chingay-2025/">https://www.sg60.gov.sg/chingay-2025/</a></p>


        </div>
      </div>
      </div>
      </div>


      


    

      </div>


    </div>





    </div>

  </div>
</div>


<div class="col-12" style="max-width: 100%; padding: 30px 0px 40px; display: block;">
  <div class="col-12">
    <div style="padding: 0px 10px;">
<div style="width: 100%; background: #FB5C1F; border-radius: 30px; padding: 0px 0px 20px; display: flex;">
        <div style="width: 100%; padding: 30px 10px 10px; text-align: center; margin: auto;">
          <h1 style="font-family:  Arial; font-size: xx-large; font-weight: bold; color: #FFFFFF; letter-spacing: normal;"><strong style="font-weight: bold; color: #FFFFFF; font-style: italic;">Know an interesting or inspiring story?</strong></h1>
          <a href="mailto:northwest_cdc@pa.gov.sg" target="_new" style="text-decoration: none;">
            <div style="font-family:  Arial; font-size: large; font-weight: bold; background: #FFFFFF; color: #FB5C1F; padding: 15px 15px; max-width: 200px; margin: auto; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; text-decoration: none; text-transform: uppercase; font-style: italic;
    font-weight: bold;">Tell Us More
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
</div>


</article>

<div style="display: inline-block; width: 100%;">

<div style="max-width: 800px; width: 100%; margin: auto;">

<div style="width: 100%;">

    <div style="width: 100%; padding: 15px 10px; text-align: center;">
      <div class="w-100">

          <h2 style="color: #331E16; font-family: Arial, 'sans-serif'; line-height: 30px;">
            <em style="font-family: Arial, 'sans-serif'; font-size: 22px;">For the latest events and happenings,</em><br>
            <em style="font-family: Arial, 'sans-serif'; text-transform: uppercase; font-weight: bold; font-size: 20px;">Follow Us On</em>
          </h2>
        
      </div>
      <div class="w-100">
        <a href="https://www.facebook.com/nwcdc/" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-facebook-orange.png" style="padding: 5px 7px; max-width: 40px; display: inline-block;"></a>
        <a href="https://www.linkedin.com/company/north-west-community-development-council/posts/?feedView=all" target="_new"><img src="/images/Cohesion/January%202025/linkedin.png" style="padding: 5px 7px; max-width: 40px; display: inline-block;"></a>
        <a href="https://www.instagram.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-instagram-orange.png" style="padding: 5px 7px; max-width: 40px; display: inline-block;"></a>
        <a href="https://t.me/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/telegram-orange.png" style="padding: 5px 7px; max-width: 40px; display: inline-block;"></a>
        <a href="https://www.youtube.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-youtube-orange.png" style="padding: 5px 7px; max-width: 40px; display: inline-block;"></a>
      </div>
    </div>

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

</div>





