---
title: Green Bootcamp @ North West
permalink: /cohesion/september-2023/greenbootcamp-nw/
description: ""
third_nav_title: September 2023
---
<style>

p {
  font-family: 'Lato', sans-serif !important;
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
    <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif" style="width: 100%; max-width: 100px; position: relative; float:left !important; padding-bottom: 20px;">
  </a>
</div>

<div style="width: 100%;">
  <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/advocating-green-living.png" style="width: 100%;">
  <img src="/images/Cohesion/Sep%202023/sustainable-future.png" style="width: 100%;">
</div>

<div style="max-width: 100%; padding: 30px 0px 30px;" class="rounded20">
  <img src="/images/Cohesion/Sep%202023/get-green-kv.gif" class="rounded20" style="width: 100%; margin-top: 0px;">
</div>

<div style="padding: 0px 0px 0px;">
<p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">Part of our efforts in encouraging residents to go green, the Green Bootcamp @ North West hopes to inspire youths to think out of the box and become eco-innovators to support green living.</p>

<p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">The secondary school edition of the bootcamp was held over 3 days in July. Four teams engaged in a series of workshops and activities to better understand today’s environmental issues, inspiring them to ideate solutions to solve these problems. They wrapped up the bootcamp with a pitch presentation to showcase their solutions and a chance to win cash prizes! </p>
</div>

<div style="max-width: 100%; padding: 30px 0px 20px;" class="rounded20">
  <img src="/images/Cohesion/Sep%202023/gbc_nw.png" class="rounded20" style="width: 100%; margin-top: 0px;">
</div>

<div style="max-width: 100%; padding: 30px 20px 20px;" class="">
  <img src="/images/Cohesion/Sep%202023/in-photo.png" class="" style="width: 100%; margin-top: 0px;">
</div>

<div style="background: #CFEAE3;padding: 20px 15px;" class="w-100 rounded20">
  <img src="/images/Cohesion/Sep%202023/w1%20pic.png" style="width: 100%;">
  <div style="background: #FFFFFF; display: inherit; margin: -1px auto 15px !important; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;" class="w-100">
    <div style="display: inline-block; margin: 0 7% 15px;" class="w-100">
    <p style="font-size: 24px; line-height: 26px; font-weight: bold; margin:0 0; padding-top: 20px;  color: #0C6C37;"><i>Sharing by Team LATO</i></p>

    <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">Hidayah from Team LATO, one of the finalists from the Green Bootcamp 2022 was there to share her journey and experience in transforming their green ideas into reality.</p>

    <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">It was inspiring to hear from an actual participant and how each of us can make a difference in our own small ways.</p>
    </div>

    <div style="display: inline-block; margin: 0 7% 15px;" class="w-100">
      <img src="/images/Cohesion/Sep%202023/w2%20pic.png" style="width: 100%;">
      <p style="font-size: 24px; line-height: 26px; font-weight: bold; margin:0 0; padding-top: 20px; color: #0C6C37;"><i>Upcycling Workshop by Semula</i></p>

      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">In the upcycling workshop by Semula, we literally learned how to turn "trash into treasure". Semula believes that unwanted materials should be given a new life through upcycling.</p>

      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">The facilitators taught us how to make folders out of trash bags. It was a fun, hands-on activity to drum home the message of the 3Rs: reduce, recycle and reuse.</p> 

      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">This activity also inspired the idea for our pitch that we developed for the Green Bootcamp! </p>
    </div>

    <div style="display: inline-block; margin: 0 7% 15px;" class="w-100">
      <img src="/images/Cohesion/Sep%202023/w3%20pic.png" style="width: 100%;">
      <p style="font-size: 24px; line-height: 26px; font-weight: bold; margin:0 0; padding-top: 20px; color: #0C6C37;"><i>Tour of Tzu Chi Foundation</i></p>

      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">During the tour of the Tzu Chi Foundation, we had a glimpse of its efforts to raise awareness on environmental protection.</p> 

<p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">A memorable moment that stood out for me during the tour was the presence of the climate clock because it was a visual reminder that we are racing against time to tackle 
global warming.</p> 

<p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">When I saw the time left on the clock (6 years and 16 days), I felt really sad because it meant that once the climate clock counts down to zero, the Earth's carbon budget would be used up. As humans, we have very little time left to take decisive action to keep global warming under the 1.5°C threshold. </p>

<p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">In 6 years, many people would still be children, teens and young adults and to live in a world in constant threat of climate change is not a pleasant thought. It made me feel very strongly about how each of us can do our part to extend the date in which Earth would run out of the carbon budget. 
</p>
    </div>

    <div style="padding: 20px 0px;" class="w-100">
    </div>

  </div>

  <div style="margin: -8% auto 0px; text-align: center;" class="w-100">
    <img src="/images/Cohesion/Sep%202023/charlotte.png" style="width: 95%;">
  </div>


  <div style="background: #FFFFFF; display: inherit; margin: -25px auto 15px !important;" class="w-100 rounded20">
    <div style="display: inline-block; margin: 50px 7% 15px;" class="w-100">
      <img src="/images/Cohesion/Sep%202023/pitch%20pic.png" style="width: 100%;">

      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">Our team wanted to tackle the issue of how to encourage residents in the North West to carry out the 3Rs (reduce, reuse, recycle) in their daily activities to move towards the goal 
of a zero waste nation.</p>  

      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">We got the idea from our friends and family when we did some research and found out that they did not usually practise the 3Rs.</p>

      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">We brainstormed ideas on how to make simple changes to our daily routines so that they can be more environmentally friendly. </p>

      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">We came up with a "Garbage Guru" to help residents with 3 simple steps: </p>

      <ol style="padding: 0px 15px;">
        <li style="line-height: 26px; font-size: initial;">Reuse packaging such as drink cartons and egg trays as pots for plants</li>
        <li style="line-height: 26px; font-size: initial;"> Maximise every part of a food produce by growing plants from commonly-discarded 
               food&nbsp;parts</li>
        <li style="line-height: 26px; font-size: initial;"> Making garbage enzyme from fruit peels</li>
      </ol>


      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">To implement this, we suggested giving out a free sample of a garbage enzyme with a QR code linked to a website where residents can learn more about how the garbage enzyme works, as well as pick up other 3Rs tips. </p>
      <p></p>
    </div>
     
    <div style="display: inline-block; margin: 0px 7% 15px;" class="w-100">
      <img src="/images/Cohesion/Sep%202023/what-about.png" style="width: 100%;">
    </div>

    <div style="display: inline-block; margin: 15px 7% 15px;" class="w-100">
      <img alt="Charlotte Kok" src="/images/Cohesion/Sep%202023/kok%20jpg.png" style="width: 100%;">
      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">From the Green Bootcamp, I have a greater understanding about the impact of human activities such as agriculture and construction on the environment. These activities release greenhouse gases which harm the environment. I also now realise that Singapore produces a huge amount of waste. </p>
      <p style="font-size: 16px; line-height: 26px;">I'm now more aware of the environmental issues we are facing and what needs to be fixed. </p>  
    </div>

    <div style="display: inline-block; margin: 15px 7% 15px;" class="w-100">
      <img alt="Charlotte Ong" src="/images/Cohesion/Sep%202023/ong%20pic.png" style="width: 82%;">
      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">Overall, I think the Green Bootcamp is a very good idea to inspire the next generation of eco champions to advocate sustainability in Singapore. We learnt many new things about climate change and also had the chance to listen to other students' ideas.</p> 

      <p style="font-size: 16px; line-height: 26px; margin: 15px 0px;">I would definitely encourage fellow students to join the Green Bootcamp next time. It's a good opportunity for them to learn more about climate change. This will also encourage them to care more about the environment and the impact of their actions on the planet.</p>  
    </div>


  </div>


</div>




<!--CTA-->
<div style="width: 100%; background: #DCEAE3; padding: 15px 0px; margin: 25px 0px; display: flex;" class="rounded20">
    <div style="padding: 20px 40px;">
      <div style="background-image: url('/images/Cohesion/Sep%202023/froggie-logo.png'); background-color: #DCEAE3; background-blend-mode: darken; min-height: 100px; background-repeat: no-repeat; background-size: contain; margin-left: 0px;">
      </div>
        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">Would you like to make an impact on the environment? Discover how you can be part of the solution by learning about sustainable practices, connecting with like-minded individuals in the community and turning your green ideas into a reality.</p>
        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">Stay tuned for the next edition of Green Bootcamp @ North West. Find out more <a href="https://northwest.cdc.gov.sg/programmes/advocating-green-living/greenbootcamp-nw/" target="_new" style="font-weight: bold; color: #0C6C37;">here</a>.</p>  
      </div>
    </div>  
<!--CTA End-->




<!--Footer-->
<div class="col-" style="padding: 20px 0px 0px; display: flex;">&nbsp;</div>

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