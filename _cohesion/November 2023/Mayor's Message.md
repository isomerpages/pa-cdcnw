---
title: Mayor's Message
permalink: /cohesion/november-2023/mayor-message/
description: ""
third_nav_title: November 2023
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


/*Tabs*/
.tabs {
  max-width: 800px;
  margin-top: 20px;
  padding: 0px;
}
.tabs input {
  display: none;
}
.tabs label {
  display: inline-block;
  padding: 6px 0 6px 0;
  margin: 0 -2px;
  width: 25%; 
  text-align: center;
  font-family: 'Lato', sans-serif;
}
.tabs label:hover {
  cursor: pointer;
  color: #FB5C1F;
}
.tabs input:checked + label {
  border-width: 1px 1px 0 1px;
  color: #FB5C1F;
  font-weight: bold;
}
.tabs #tab1:checked ~ .content #content1,
.tabs #tab2:checked ~ .content #content2,
.tabs #tab3:checked ~ .content #content3,
.tabs #tab4:checked ~ .content #content4 {
  display: block;
}
.tabs .content > div {
  display: none;
  padding-top: 20px;
  text-align: left;
  overflow: auto;
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

/* Tabs */
.tabbed {
  position: relative;
}
.tabbed figure {
  display: block;
  margin: 0;
  clear: both;
  z-index: 9;
}
.tabbed figure .tab_form {
  opacity: 0;
  visibility: hidden;
  height: 0;
  width: 100%;
  line-height: 1.5em;
  letter-spacing: 0.3px;
  text-align: left;
  margin: 0;
}
.tabbed figure .tab_form .tab_inner > *:first-child {
  margin-top: 0;
}
.tabbed figure .tab_form .tab_inner > *:last-child {
  margin-bottom: 0;
}
.tabbed > input {
  display: none;
}
.tabbed nav {
  height: auto;
  display: flex;
  flex-wrap: wrap;
}
.tabbed nav label {
  width: 25%;
  padding: 8px 0px;
  color: #fff;
  cursor: pointer;
  transition: background-color 0.5s;
}

.theme-1.tabbed {
  display: flex;
  flex-wrap: wrap;
}
.theme-1.tabbed figure {
  width: 75%;
  margin-top: 10px;
}
.theme-1.tabbed figure .tab_form {
  height: 0;
  background: #fff;
  text-align: left;
}
.theme-1.tabbed figure .tab_form .tab_inner {
  padding: 20px;
  border: 1px solid #0096ff;
}
.theme-1.tabbed nav {
  width: 25%;
  height: auto;
  display: block;
}
.theme-1.tabbed nav label {
  display: block;
  width: 100%;
  padding: 8px 20px;
  border: 1px solid #0096ff;
  background: #0096ff;
  color: #fff;
  cursor: pointer;
  margin-bottom: 4px;
  margin-right: 4px;
  transition: background-color 0.5s;
}
.theme-1.tabbed nav label:hover {
  background: rgba(0, 150, 255, 0.5);
}
.theme-1.tabbed nav label:active {
  background: #ffffff;
}

.theme-2.tabbed figure {
  padding-top: 35px;
}
.theme-2.tabbed figure .tab_form .tab_inner {
  padding: 0 0 50px 0;
  background-color: #ffffff;
}
.theme-2.tabbed nav {
  position: absolute;
  width: 100%;
}
.theme-2.tabbed nav label {
  /*border: 1px solid #0096ff;
  background: #0096ff;*/
  width: 24%;
  /*margin-right: 0px;*/
  text-align: center;
  color: #000000;
  font-family: 'Lato', sans-serif;
}
.theme-2.tabbed nav label:hover {
  color: #FB5C1F;
}
.theme-2.tabbed nav label:active {
  background: #ffffff;
}

.theme-3.tabbed {
  display: flex;
  flex-wrap: wrap;
}
.theme-3.tabbed figure {
  width: 75%;
}
.theme-3.tabbed figure .tab_form {
  height: 0;
  background: #fff;
  text-align: left;
}
.theme-3.tabbed figure .tab_form .tab_inner {
  padding: 20px;
  border: 1px solid #0096ff;
}
.theme-3.tabbed nav {
  width: 25%;
  height: auto;
  display: block;
}
.theme-3.tabbed nav label {
  display: block;
  width: 80%;
  padding: 8px 20px;
  color: #0096ff;
  cursor: pointer;
  margin-bottom: 4px;
  margin-right: 4px;
  padding-left: 30px;
  text-align: left;
  position: relative;
}
.theme-3.tabbed nav label:before {
  content: "➤";
  position: absolute;
  left: -20px;
  top: 2px;
  opacity: 0;
  font-size: 24px;
  transition: opacity 0.5s, left 0.5s;
}
.theme-3.tabbed nav label:hover:before {
  opacity: 1;
  left: -8px;
}
.theme-3.tabbed nav label:active:before {
  opacity: 1;
  left: -8px;
}

@media (max-width: 767px) {
  .theme-1.tabbed nav {
    width: 100%;
  }
  .theme-1.tabbed nav label {
    width: calc( 100% - 40px );
    display: block;
    float: none;
    margin: 4px 0;
    border-bottom: 1px solid #0096ff !important;
  }
  .theme-1.tabbed nav label:after {
    display: none !important;
  }
  .theme-1.tabbed figure {
    width: 100%;
  }

  .theme-3.tabbed nav {
    width: 100%;
  }
  .theme-3.tabbed figure {
    width: 100%;
    margin-top: 20px;
  }
}
.tabbed #tab1_1:checked ~ figure .tab1 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.tabbed #tab1_2:checked ~ figure .tab1 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.tabbed #tab1_3:checked ~ figure .tab1 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.theme-1 #tab1_1:checked ~ nav label[for=tab1_1] {
  background: #ffffff;
  color: #0096ff;
}

.theme-2 #tab1_2:checked ~ nav label[for=tab1_2] {
  background: #ffffff;
  color: #FB5C1F;
  font-weight: bold;
}

.theme-3 #tab1_3:checked ~ nav label[for=tab1_3]:before {
  opacity: 1;
  left: 0px;
}

.tabbed #tab2_1:checked ~ figure .tab2 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.tabbed #tab2_2:checked ~ figure .tab2 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.tabbed #tab2_3:checked ~ figure .tab2 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.theme-1 #tab2_1:checked ~ nav label[for=tab2_1] {
  background: #ffffff;
  color: #0096ff;
}

.theme-2 #tab2_2:checked ~ nav label[for=tab2_2] {
  color: #FB5C1F;
  font-weight: bold;
}

.theme-2 #tab4_2:checked ~ nav label[for=tab4_2] {
  color: #FB5C1F;
  font-weight: bold;
}

.theme-2 #tab2_4:checked ~ nav label[for=tab2_4] {
  background: #ffffff;
  border-bottom-color: #ffffff;
  color: #0096ff;
}

.theme-3 #tab2_3:checked ~ nav label[for=tab2_3]:before {
  opacity: 1;
  left: 0px;
}

.tabbed #tab3_1:checked ~ figure .tab3 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.tabbed #tab3_2:checked ~ figure .tab3 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.tabbed #tab4_2:checked ~ figure .tab4 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.tabbed #tab3_3:checked ~ figure .tab3 {
  opacity: 1;
  visibility: visible;
  height: auto;
}

.theme-1 #tab3_1:checked ~ nav label[for=tab3_1] {
  background: #ffffff;
  color: #0096ff;
}

.theme-2 #tab3_2:checked ~ nav label[for=tab3_2] {
  color: #FB5C1F;
  font-weight: bold;
}

.theme-3 #tab3_3:checked ~ nav label[for=tab3_3]:before {
  opacity: 1;
  left: 0px;
}

/* Tabs - End */

  </style>


<article style="max-width: 800px; width: 100%; margin: auto;">

<div style="width: 100%;">
  <img style="width: 100%; max-width: 100px; position: relative; padding-left: 10px; float:left !important; padding-bottom: 20px;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
</div>

<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://staging.d2pf4p43lgd5yo.amplifyapp.com/images/Cohesion/November%202023/mayor-msg.png">
</div>


<div style="width: 100%; padding: 0px 0px;">


<!-- Second Tab-Style -->

      <div class="tabbed theme-2">

        <input checked="checked" name="tabs_2" type="radio" id="tab1_2">
        <input name="tabs_2" type="radio" id="tab2_2">
        <input name="tabs_2" type="radio" id="tab3_2">
        <input name="tabs_2" type="radio" id="tab4_2">

        <nav style="position: absolute; bottom: -33px; border-top: thin solid #484848; border-bottom: thin solid #484848; display: inline-flex !important;">

          <label for="tab1_2">English</label>
          <label for="tab2_2">中文字幕</label>
          <label for="tab3_2">Sarikata Bahasa Melayu</label>
          <label for="tab4_2">தமிழ் வரிகள்</label>

        </nav>

        <figure style="margin: 0px; padding: 20px 0 10px;">

          <div data-group="integrations" class="tab_form tab1">

            <div class="tab_inner">
              <div class="video-container rounded20">
              <iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/VfP7YiZcahE?si=7s7QUpEu7Pt7Rwfr" height="315" width="560"></iframe>
              </div>
            </div>

          </div>

          <div data-group="integrations" class="tab_form tab2">

            <div class="tab_inner">
              <div class="video-container rounded20">
              <iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/uVkoJRB3dNs?si=DVRLOD4cLrbTe6eD" height="315" width="560"></iframe>
              </div>
            </div>

          </div>

          <div data-group="integrations" class="tab_form tab3">

            <div class="tab_inner">
              <div class="video-container rounded20">
              <iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/5PuN39UaYRo?si=m4Zp9FiPbP0D6do7" height="315" width="560"></iframe>
              </div>
            </div>

          </div>

          <div data-group="integrations" class="tab_form tab4">

            <div class="tab_inner">
              <div class="video-container rounded20">
              <iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/uZBZQqyGtwo?si=CxgGOxEQ9kGKUJTZ" height="315" width="560"></iframe>
              </div>
            </div>

          </div>

        </figure>

      </div>
      <!-- Second Tab-Style - End -->







</div>











<!--Footer-->
<div style="padding: 50px 0px 0px; display: flex;" class="col-">&nbsp;</div>

<!--Latest Stores Card-->
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
<!--Latest Stores Card-->

<div style="padding: 40px 20px; text-align: center;">
  <h2 style="font-size: xx-large; font-weight: bold;"><em>Our Team</em></h2>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Adviser: Mayor Alex Yam</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Editorial Team: Garick Kea, Sim Chuan San, Steve Luo, Eric Liu, Melvin Tai, Charlene Koh</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Please send feedback, suggestions and comments to <a style="color: #000000; text-decoration: underline;" target="_new" href="mailto:northwest_cdc@pa.gov.sg">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Some articles in Cohesion are contributed by volunteers and are not necessarily opinions/comments by North&nbsp;West&nbsp;CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Reproduction in whole or in part is prohibited without prior permission from North West CDC.</p>
</div>
<!--Footer End-->


</article>


