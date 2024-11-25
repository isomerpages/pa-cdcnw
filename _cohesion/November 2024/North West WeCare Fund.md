---
title: North West WeCare Fund
permalink: /cohesion/november-2024/wcf/
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
  </style>


<article style="max-width: 800px; width: 100%; margin: auto;">

<div style="width: 100%;">
  <a href="https://northwest.cdc.gov.sg/cohesion/november-2024/at-a-glance/">
    <img style="width: 100%; max-width: 100px; position: relative; float: left;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://northwest.cdc.gov.sg/images/Cohesion/January%202024/caring_communities.png">
  <img style="width: 100%; max-width:" src="/images/Cohesion/November%202024/title_northland.png">
</div>

<div style="padding: 10px 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Thinking of volunteering but not sure where to start? Take the lead from Northland Primary School, where giving back is in its DNA! The school is on a mission to make a real difference in the community – and when everyone pitches in, great things happen!<br><br>
Throughout the years, Northland Primary has been very active in supporting efforts to uplift others in the community. It has regularly teamed up with North West CDC through outreach programmes such as Service Weeks to spread kindness to families in need.</p>
</div>

<div style="max-width: 100%; padding: 20px 0px 10px;" class="rounded20">
  <img style="width: 100%; margin-top: 0px;" class="rounded20" src="/images/Cohesion/November%202024/kv_northland.gif">
</div>

<div style="max-width: 100%; padding: 20px 0px 10px;" class="rounded20">
  <img style="width: 100%; margin-top: 0px;" class="rounded20" src="/images/Cohesion/November%202024/the_scene.png">
</div>


<div class="" style="width:100%; max-width: 100%; padding: 10px 0px; display: inline-block;">
  <div style="" class="col-6 float-left">
    <img style="width: 100%; padding: 10px 0px;" src="/images/Cohesion/November%202024/moonlight.jpg">
    <div style="width: 99%; background: #EBDFEC; margin: 0px auto;" class="rounded20">
      <div style="width: 100%; padding: 10px 10px; display: inline;">
      <p style="font-size: 16px; line-height: 22px; margin: 10px 20px;"><span style="font-weight: bold; color: #856AB7;">Collab partners:</span> Northland Primary School, Nee Soon Central Zone 6 Residents' Network and North West CDC</p>

      <p style="font-size: 16px; line-height: 22px; margin: 10px 20px;"><span style="font-weight: bold; color: #856AB7;">Beneficiaries:</span> Residents from Villa Francis Home and low income families in Nee Soon</p>

      <p style="font-size: 16px; line-height: 22px; margin: 10px 20px 0px;"><span style="font-weight: bold; color: #856AB7;">Programme:</span><br>
        </p><ul>
          <li>Game booths</li>
          <li>Zumba, wushu, dance and magic show performances</li>
          <li>Lantern procession</li>
          <li>Parent-child pomelo peeling competition</li>
          <li>Mooncake sampling</li>
          <li>Lucky draw</li>
        </ul>
      
      <div style="width: 100%; text-align: center;">
        <iframe allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowfullscreen="true" frameborder="0" scrolling="no" style="border:none;overflow:hidden" height="476" width="267" src="https://www.facebook.com/plugins/video.php?height=476&amp;href=https%3A%2F%2Fwww.facebook.com%2Fnwcdc%2Fvideos%2F1898889947271111%2F&amp;show_text=false&amp;width=267&amp;t=0"></iframe>
      </div>
      </div>
    </div>
  </div>
  <div style="" class="col-6 float-left">
    <img style="width: 100%; padding: 10px 0px;" src="/images/Cohesion/November%202024/carnival.jpg">
    <div style="width: 99%; background: #EBDFEC; margin: 0px auto;" class="rounded20">
      <div style="width: 100%; padding: 10px 10px; display: inline;">
      <p style="font-size: 16px; line-height: 22px; margin: 10px 20px;"><span style="font-weight: bold; color: #856AB7;">Collab partners:</span> Northland Primary School and North West CDC</p>

      <p style="font-size: 16px; line-height: 22px; margin: 10px 20px;"><span style="font-weight: bold; color: #856AB7;">Beneficiaries:</span> Underprivileged residents and families living in the North West</p>

      <p style="font-size: 16px; line-height: 22px; margin: 10px 20px 0px;"><span style="font-weight: bold; color: #856AB7;">Service Weeks pop-up market:</span><br>
        </p><ul>
          <li>Packing and distribution of food items</li>
          <li>Personal shopping assistance</li>
        </ul>
      

      <p style="font-size: 16px; line-height: 22px; margin: 10px 20px 0px;"><span style="font-weight: bold; color: #856AB7;">Carnival activities:</span><br>
        </p><ul style="padding-bottom: 7px;">
          <li>Carnival games</li>
          <li>Bouncy castle</li>
          <li>Carnival treats</li>
        </ul>
      
      <div style="width: 100%; text-align: center;">
        <iframe allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowfullscreen="true" frameborder="0" scrolling="no" style="border:none;overflow:hidden" height="476" width="267" src="https://www.facebook.com/plugins/video.php?height=476&amp;href=https%3A%2F%2Fwww.facebook.com%2Fnwcdc%2Fvideos%2F2643521192525102%2F&amp;show_text=false&amp;width=267&amp;t=0"></iframe>
      </div>
      </div>
    </div>
  </div>
</div>

<div style="width: 100%; padding: 50px 0px 0px;">
  <img style="width: 100%; max-width:" class="" src="/images/Cohesion/November%202024/game_master.png">
</div>
<div style="padding: 15px 25px 30px; border-left: 4px solid #B25694; border-right: 4px solid #B25694; border-bottom: 4px solid #B25694;-webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">
  <img style="width: 100%; padding: 0px 0px 25px;" class="" src="/images/Cohesion/November%202024/volunteers1.gif">
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Role:</span> Runs the game booths and makes sure everyone has fun</p>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Personality:</span> Outgoing, energetic</p>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Superpower:</span> Master of explaining the rules, can hype up the crowd, ability to keep things going</p>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Motto:</span> Bringing the fun!</p>
</div>

<div style="width: 100%; padding: 50px 0px 0px;">
  <img style="width: 100%; max-width:" class="" src="/images/Cohesion/November%202024/performer.png">
</div>
<div style="padding: 0px 25px 20px; border-left: 4px solid #B25694; border-right: 4px solid #B25694; border-bottom: 4px solid #B25694;-webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">
  <div style="max-width: 100%; padding: 20px 0px;">
  <div class="video-container rounded20">
    <iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/NgbSYVj-WoU?si=N_LhpSw6DwnCR2Y3" height="315" width="560"></iframe>
  </div>
  </div>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Role:</span> Entertains the audience (e.g. through a dance or wushu performance)</p>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Personality:</span> Expressive, loves to perform</p>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Superpower:</span> Has stage presence, master of choreography, well-coordinated</p>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Motto:</span> Spreading joy!</p>
</div>

<div style="width: 100%; padding: 50px 0px 0px;">
  <img style="width: 100%; max-width:" class="" src="/images/Cohesion/November%202024/shopper.png">
</div>
<div style="padding: 15px 25px 30px; border-left: 4px solid #B25694; border-right: 4px solid #B25694; border-bottom: 4px solid #B25694;-webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">
  <img style="width: 100%; padding: 0px 0px 25px;" class="" src="/images/Cohesion/November%202024/volunteers3.gif">
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Role:</span> Helps residents to select food items at the food distribution booths</p>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Personality:</span> Helpful, pays attention to details</p>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Superpower:</span> Organised, can find the perfect item for anyone, quick thinker and able to offer suggestions</p>
  <p style="font-size: 16px; line-height: 26px; margin: 0px 0px;"><span style="font-weight: bold; color: #B25694;">Motto:</span> Service with a smile!</p>
</div>

<div style="width: 100%; padding: 20px 0px 20px;">
  <img style="width: 100%; max-width:" class="rounded20" src="/images/Cohesion/November%202024/northland_quote.jpg">
</div>

<div style="padding: 0px 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Discover more of Northland Primary School’s past volunteering efforts. Here’s what a mother-daughter team did during a day out volunteering at the North West Service Weeks Pop-Up Market in 2023.</p>
</div>

<div style="width: 100%; padding: 20px 0px 20px;">
  <a target="_new" href="https://northwest.cdc.gov.sg/cohesion/july-2023/sw-volunteersdayout/"><img style="width: 100%; max-width:" class="rounded20" src="/images/Cohesion/November%202024/volunteers_kv_cta.jpg"></a>
</div>







<div style="padding: 20px 0px;">
<div style="width: 100%; background: #F5E1E0; padding: 0px 0px 0px;" class="rounded20">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #DA312C; margin: 0px 0px;"><strong>Plan your own ground-up initiative</strong>
      </p> 

      <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px 0px;">Northland Primary School is a shining example of how schools can make an impact in the community! With funding from the North West WeCare Fund, the school has brought together students, teachers, parents and the community to organise ground-up initiatives like the Moonlight Garden Party @ North West and North West Service Weeks and Children’s Day Carnival. Projects like these are all about building connections and giving back! For its efforts in promoting community bonding, Northland Primary School also received the Community Spirit Award in 2024.
<br><br>
You can get involved and make a difference too! If you have an idea for a community-driven project that can benefit local residents, we want to hear from you! Contact us at <a style="font-weight: bold; color: #D5262B;" target="_new" href="mailto:northwestcdc_partnerships@pa.gov.sg">northwestcdc_partnerships@pa.gov.sg</a> to discuss your project ideas.
<br><br>
Find out more about the North West WeCare Fund <a style="font-weight: bold; color: #D5262B;" target="_new" href="https://go.gov.sg/nw-wecare-fund">here</a>.
      </p> 
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


