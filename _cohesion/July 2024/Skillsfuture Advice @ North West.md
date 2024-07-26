---
title: Skillsfuture Advice @ North West
permalink: /cohesion/jul-2024/nw-sfa/
variant: markdown
description: ""
third_nav_title: July 2024
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
  <a href="https://northwest.cdc.gov.sg/cohesion/july-2024/at-a-glance/">
    <img style="width: 100%; max-width: 100px; position: relative; float: left;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%;" src="https://northwest.cdc.gov.sg/images/Cohesion/January%202024/learning_communities.png">
  <img style="width: 100%;" src="/images/Cohesion/July%202024/title_learning_tips.png">
</div>

<div class="" style="max-width: 100%; padding: 20px 0px 0px;">
  <img style="width: 100%;" class="rounded20" src="/images/Cohesion/July%202024/kv_learning.jpg">
</div>

<div style="padding: 20px 0px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Feeling stuck in your career and unsure what to do next? We’ve curated a list of free resources to help you achieve career resilience. Check them out here!
</p>
</div>



<div class="" style="max-width: 100%; padding: 15px 0px 0px;">
  <img style="width: 100%; -webkit-border-top-left-radius: 20px; -webkit-border-top-right-radius: 20px; -moz-border-radius-topleft: 20px; -moz-border-radius-topright: 20px; border-top-left-radius: 20px; border-top-right-radius: 20px;" class="" src="/images/Cohesion/July%202024/tip1.png">
</div>
<div class="" style="max-width: 100%; padding: 70px 30px 20px; background: #F7F7F7; margin-top: -50px; -webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">

<div class="" style="width: 100%; padding-bottom: 20px; border-bottom: thin solid #707070">
<h3 style="font-size: 18px; color: #000000; font-weight: bold;">Embark on your career journey with experts who’ll help you to clarify your career goals and provide advice on career opportunities.</h3>
<div style="width: 100%; text-align: center; padding: 20px 0px;">
  <a style="background: #1670A7; font-family: Arial, 'sans-serif;'; font-size: 16px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem;" href="https://content.mycareersfuture.gov.sg/career-guidance/">Get career guidance</a>
</div>
</div>

<div style="display: inline-block;" class="w-100 col-">
  <div style="padding: 10px 0px;" class="col-4 float-left">
    <div style="padding: 15px 10px;" class="w-100">
    <h3 style="font-size: 16px;color: #1670A7;text-align: center;font-weight: bold;line-height: initial;">Access Free Career Matching Services</h3>
    <p style="font-size: 15px; line-height: normal; text-align: center; margin: 0px 0px;">Get personalised career advice from Workforce Singapore (WSG) for your job search and career development. Learn how to tailor your resume and improve your interview skills, plus connect with prospective employers.
    </p>
    <div style="width: 100%; text-align: center; padding: 20px 0px;">
      <a style="background: #1670A7; font-family: Arial, 'sans-serif;'; font-size: 13px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 15px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; display: inline-block; margin: 0px;" href="https://content.mycareersfuture.gov.sg/job-search-advisory-registration/content/">Sign Up Now</a>
    </div>
    </div>
  </div>
  <div style="padding: 10px 0px;" class="col-4 float-left">
    <div style="padding: 15px 10px;" class="w-100">
    <h3 style="font-size: 16px;color: #1670A7;text-align: center;font-weight: bold;line-height: initial;">Get Advice on How to Plan Your Career</h3>
    <p style="font-size: 15px; line-height: normal; text-align: center; margin: 0px 0px;">Meet up with a Career Coach at WSG’s Careers Connect or NTUC’s e2i centres for guidance on your career goals, interests and skills. Receive one-on-one support on how to develop an action plan to advance in your career.
    </p>
    <div style="width: 100%; text-align: center; padding: 20px 0px;">
      <a style="background: #1670A7; font-family: Arial, 'sans-serif;'; font-size: 13px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 15px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; display: inline-block; margin: 0px;" href="https://www.wsg.gov.sg/home/individuals/career-advisory-coaching/visit-career-centres">Book an Appointment</a>
    </div>
    </div>
  </div>
  <div style="padding: 10px 0px;" class="col-4 float-left">
    <div style="padding: 15px 10px;" class="w-100">
    <h3 style="font-size: 16px;color: #1670A7;text-align: center;font-weight: bold;line-height: initial;">Get Job Advice
Through Video Chat</h3>
    <p style="font-size: 15px; line-height: normal; text-align: center; margin: 0px 0px;">No time to visit a career centre? No problem. Connect with a career officer through video chat for quick career tips and advice.
    </p>
    <div style="width: 100%; text-align: center; padding: 20px 0px;">
      <a style="background: #1670A7; font-family: Arial, 'sans-serif;'; font-size: 13px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 10px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; display: inline-block; margin: 0px;" href="https://content.mycareersfuture.gov.sg/video-advisory/">Connect With a Career Officer</a>
    </div>
    </div>
  </div>
</div>
</div>


<div class="" style="max-width: 100%; padding: 25px 0px 0px;">
  <img style="width: 100%; -webkit-border-top-left-radius: 20px; -webkit-border-top-right-radius: 20px; -moz-border-radius-topleft: 20px; -moz-border-radius-topright: 20px; border-top-left-radius: 20px; border-top-right-radius: 20px;" class="" src="/images/Cohesion/July%202024/tip2.png">
</div>
<div class="" style="max-width: 100%; padding: 70px 30px 20px; background: #F7F7F7; margin-top: -50px; -webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">

<div class="" style="width: 100%; padding-bottom: 20px; border-bottom: thin solid #707070">
<h3 style="font-size: 18px; color: #000000; font-weight: bold;">Discover a wide range of free seminars and workshops on the Career Grit portal where
you can learn in-demand skills for free!</h3>
<div style="width: 100%; text-align: center; padding: 20px 0px;">
  <a style="background: #1F4D7F; font-family: Arial, 'sans-serif;'; font-size: 16px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem;" href="https://www.careergrit.sg/seminars-and-workshops">Search for a Workshop</a>
</div>
</div>

<h3 style="font-size: 18px; color: #000000; font-weight: bold; padding: 0px 0px; margin: 15px 0px 0px;">If you’re looking to build career resilience, here are three seminars to get you started.</h3>

<div style="display: inline-block;" class="w-100 col-">
  <div style="padding: 10px 0px;" class="col-4 float-left">
    <div style="padding: 15px 10px;" class="w-100">
    <h3 style="font-size: 16px;color: #1670A7;text-align: center;font-weight: bold;line-height: initial;">Practical Career Planning
Strategies (Professionals)</h3>
    <p style="font-size: 15px; line-height: normal; text-align: center; margin: 0px 0px;">Join this webinar for working professionals focused on proactive career planning and navigating uncertainties. Gain practical guidance and learn how to integrate work-life considerations into your career strategy.
<br><br>
<span style="font-weight: bold;">
Date: 22 Aug 2024<br>
Time: 7pm to 9pm<br>
Type: Virtual</span>
    </p>
    <div style="width: 100%; text-align: center; padding: 20px 0px;">
      <a style="background: #1F4D7F; font-family: Arial, 'sans-serif;'; font-size: 13px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; display: inline-block; margin: 0px;" href="https://www.careergrit.sg/seminars-and-workshops">Sign Up Now</a>
    </div>
    </div>
  </div>
  <div style="padding: 10px 0px;" class="col-4 float-left">
    <div style="padding: 15px 10px;" class="w-100">
    <h3 style="font-size: 16px;color: #1670A7;text-align: center;font-weight: bold;line-height: initial;">Your Personal Brand 
and Pitch</h3>
    <p style="font-size: 15px; line-height: normal; text-align: center; margin: 0px 0px;">Seeking career advancement within your current organisation? Learn how to craft a standout personal brand and compelling pitch so you can communicate your value and establish yourself as an industry leader.
<br><br>
<span style="font-weight: bold;">
Date: 30 Jul 2024<br>
Time: 12pm to 2pm<br>
Type: Virtual</span>
    </p>
    <div style="width: 100%; text-align: center; padding: 20px 0px;">
      <a style="background: #1F4D7F; font-family: Arial, 'sans-serif;'; font-size: 13px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; display: inline-block; margin: 0px;" href="https://www.careergrit.sg/seminars-and-workshops">Sign Up Now</a>
    </div>
    </div>
  </div>
  <div style="padding: 10px 0px;" class="col-4 float-left">
    <div style="padding: 15px 10px;" class="w-100">
    <h3 style="font-size: 16px;color: #1670A7;text-align: center;font-weight: bold;line-height: initial;">Raise Resilience to
Rejuvenate Career</h3>
    <p style="font-size: 15px; line-height: normal; text-align: center; margin: 0px 0px;">To stay employable, PMETs must continuously reskill and adapt to new norms. Learn practical strategies to become more adaptable and resilient, while pursuing a purpose-driven career.
<br><br>
<span style="font-weight: bold;">
Date: 31 Jul 2024<br>
Time: 7pm to 9pm<br>
Type: Virtual</span>
    </p>
    <div style="width: 100%; text-align: center; padding: 20px 0px;">
      <a style="background: #1F4D7F; font-family: Arial, 'sans-serif;'; font-size: 13px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; display: inline-block; margin: 0px;" href="https://www.careergrit.sg/seminars-and-workshops">Sign Up Now</a>
    </div>
    </div>
  </div>
</div>
</div>


<div class="" style="max-width: 100%; padding: 25px 0px 0px;">
  <img style="width: 100%; -webkit-border-top-left-radius: 20px; -webkit-border-top-right-radius: 20px; -moz-border-radius-topleft: 20px; -moz-border-radius-topright: 20px; border-top-left-radius: 20px; border-top-right-radius: 20px;" class="" src="/images/Cohesion/July%202024/tip3.png">
</div>
<div class="" style="max-width: 100%; padding: 70px 30px 20px; background: #F7F7F7; margin-top: -50px; -webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">

<div style="display: inline-block;" class="w-100 col-">
  <div style="padding: 10px 0px;" class="col-4 float-left">
    <div style="padding: 15px 10px;" class="w-100">
    <h3 style="font-size: 16px;color: #1670A7;text-align: center;font-weight: bold;line-height: initial;">Listen to a Podcast</h3>
    <p style="font-size: 15px; line-height: normal; text-align: center; margin: 0px 0px;">Whether you’re seeking strategies for a career relaunch or want to develop a growth mindset, find inspiration in podcasts – a perfect way to spend your time while commuting.
    </p>
    <div style="width: 100%; text-align: center; padding: 20px 0px;">
      <a style="background: #0070A7; font-family: Arial, 'sans-serif;'; font-size: 13px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; display: inline-block; margin: 0px;" href="https://www.careergrit.sg/learning-on-the-go-details/podcast">Tune In to a Podcast</a>
    </div>
    </div>
  </div>
  <div style="padding: 10px 0px;" class="col-4 float-left">
    <div style="padding: 15px 10px;" class="w-100">
    <h3 style="font-size: 16px;color: #1670A7;text-align: center;font-weight: bold;line-height: initial;">Enrol in Bite-Sized
e‑Learning Courses</h3>
    <p style="font-size: 15px; line-height: normal; text-align: center; margin: 0px 0px;">Micro-learning courses are ideal for busy individuals. Through these brief e-learning modules, learn how
to sharpen your presentation skills, navigate challenging discussions at work, and much more.
    </p>
    <div style="width: 100%; text-align: center; padding: 20px 0px;">
      <a style="background: #0070A7; font-family: Arial, 'sans-serif;'; font-size: 13px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; display: inline-block; margin: 0px;" href="https://www.careergrit.sg/learning-on-the-go-details/micro-learning-courses">Find a Course</a>
    </div>
    </div>
  </div>
  <div style="padding: 10px 0px;" class="col-4 float-left">
    <div style="padding: 15px 10px;" class="w-100">
    <h3 style="font-size: 16px;color: #1670A7;text-align: center;font-weight: bold;line-height: initial;">Explore Online
Learning Resources</h3>
    <p style="font-size: 15px; line-height: normal; text-align: center; margin: 0px 0px;">Through online articles that touch on topics such as how to face the future of work amidst the AI revolution, and how to manage change amidst job redesigns, you can pick up tips on how to future-proof your career.
    </p>
    <div style="width: 100%; text-align: center; padding: 20px 0px;">
      <a style="background: #0070A7; font-family: Arial, 'sans-serif;'; font-size: 13px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; display: inline-block; margin: 0px;" href="https://www.careergrit.sg/learning-on-the-go-details/building-career-resilience">Explore Online Articles</a>
    </div>
    </div>
  </div>
</div>
</div>


<div class="" style="max-width: 100%; padding: 25px 0px 0px;">
  <img style="width: 100%; -webkit-border-top-left-radius: 20px; -webkit-border-top-right-radius: 20px; -moz-border-radius-topleft: 20px; -moz-border-radius-topright: 20px; border-top-left-radius: 20px; border-top-right-radius: 20px;" class="" src="/images/Cohesion/July%202024/tip4.png">
</div>
<div class="" style="max-width: 100%; padding: 40px 30px 20px; background: #F7F7F7; margin-top: -50px; -webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #000000; font-weight: bold;">Find out what skills you need to climb up the career ladder, transition to a new role,
achieve salary progression or to future-proof your career.</h3>
<div style="width: 100%; text-align: center; padding: 20px 0px;">
  <a style="background: #1F4D7F; font-family: Arial, 'sans-serif;'; font-size: 16px; color: #FFFFFF; font-weight: bold; text-decoration: none; padding: 12px 25px; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem;" href="https://careersfinder.mycareersfuture.gov.sg/">Take the CareersFinder Quiz</a>
</div>
</div>
</div>

<div style="width: 100%; padding: 50px 0px 0px;">
<p style="font-size: 20px; font-weight: bold; text-align: left; color: #1F4D7F; margin: 0px 0px;"><strong>Join Us For SkillsFuture Festival @ North West!</strong></p>
</div>

<div style="width: 100%; padding: 20px 0px 0px;">
  <img style="width: 100%; max-width:" class="" src="/images/Cohesion/July%202024/skillfuture_festival.jpg">
</div>
<div style="width: 100%; padding: 0px 0px; background: #FAF2E5; -webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">
  <p style="font-size: 16px; line-height: 26px; font-weight: bold; padding: 0px 40px 50px; margin: 0px 0px;">Attendance is free! Register now at <a style="font-weight: bold; color: #1F4D7F;" target="_new" href="https://go.gov.sg/sff-nwcdc">go.gov.sg/sff-nwcdc</a></p>
</div>










<div style="padding: 20px 0px;">
<div style="width: 100%; background: #DAF4FE; padding: 0px 0px 0px;" class="rounded20">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">

      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #1F4D7F; margin: 0px 0px;"><strong>About SkillsFuture Advice @ North West</strong>
      </p> 

      <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px 20px;">SkillsFuture Advice @ North West helps residents explore their potential through career planning, skill identification, and access to resources, events, webinars and workshops.
      </p> 

      <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px 0px;">Join us in making lifelong learning a way of life! <a style="font-weight: bold; color: #1F4D7F;" target="_new" href="https://go.gov.sg/connectsfa">Subscribe</a> to our email list for updates on the latest upskilling resources. Find out more <a style="font-weight: bold; color: #1F4D7F;" target="_new" href="https://go.gov.sg/nw-sfa">here</a>.
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


