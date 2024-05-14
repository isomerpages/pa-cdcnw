---
title: SkillsFuture Advice @ North West
permalink: /cohesion/may-2024/nw-sfa/
variant: markdown
description: ""
third_nav_title: May 2024
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
  <a href="https://northwest.cdc.gov.sg/cohesion/may-2024/at-a-glance/">
    <img style="width: 100%; max-width: 100px; position: relative; float: left;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%;" src="https://northwest.cdc.gov.sg/images/Cohesion/January%202024/learning_communities.png">
  <img style="width: 100%;" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/title_learning.png">
</div>


<div style="padding: 20px 0px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;">In January 2024, Zhenghua CC organised a Skills in Demand webinar in conjunction with SkillsFuture Singapore (SSG) and the Lifelong Learning Institute. It was aimed at addressing residents’ concerns on how to upskill for better jobs and salaries in the midst of rising inflation.<br><br> 
The webinar highlighted in-demand skills for the fast-growing digital, care and green economies, as well as actionable strategies for career success. Let’s take a look at what the residents learnt about the future economic landscape and how they can improve their skills for better job opportunities. 
</p>
</div>

<div class="" style="max-width: 100%; padding: 15px 0px 0px;">
  <img style="width: 100%;" class="rounded20" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inc_caring.png">
</div>
<div class="" style="max-width: 100%; padding: 70px 30px 20px; background: #F7F7F7; margin-top: -50px; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #1670A7;">1. Train to be a volunteer and learn how to befriend seniors</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Pick up befriending skills and learn how to effectively communicate and build meaningful connections with seniors, so you can help them to age actively.
<br><br>
Trainer: Fei Yu Community Services <br>
Duration: 15 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2021008261">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #1670A7;">2. Understand chronic diseases to help seniors</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Better understanding of chronic diseases can help you motivate seniors to lead healthy and active lives, while improving your own healthy knowledge and habits.
<br><br>
Trainer: Fei Yu Community Services <br>
Duration: 4 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2021008182">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #1670A7;">3. Become a healthy and happy caregiver
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Prioritise self-care and learn stress management techniques so you can enhance your personal well-being and become a better and happier caregiver to your loved ones.
<br><br>
Trainer: Tsao Foundation <br>
Duration: 8 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2018507665">Learn more</a>
</p>
</div>

</div>


<div class="" style="max-width: 100%; padding: 15px 0px 0px;">
  <img style="width: 100%;" class="rounded20" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inc_sustainable.png">
</div>
<div class="" style="max-width: 100%; padding: 70px 30px 20px; background: #F7F7F7; margin-top: -50px; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #086B37;">4. Understand the basics of sustainability for your work</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Learn why sustainability matters in the workplace and explore how organisations can adopt green technologies for sustainable living. Professional certification issued.
<br><br>
Trainer: Singapore Polytechnic  <br>
Duration: 16 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2023021531">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #086B37;">5. Master basic home maintenance skills for sustainable living</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Acquire basic home maintenance skills and knowledge on air-con efficiency, energy efficient lighting and water conserving plumbing for sustainability in daily living.
<br><br>
Trainer: Institute of Technical Education <br>
Duration: 21 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2021008182">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #086B37;">6. Discover the joy of indoor gardening
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Learn how to grow and care for plants in an indoor environment. Gain knowledge on simple home composting methods using horticulture waste or food scraps.
<br><br>
Trainer: Ngee Ann Polytechnic <br>
Duration: 7 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2018508084">Learn more</a>
</p>
</div>

</div>


<div class="" style="max-width: 100%; padding: 15px 0px 0px;">
  <img style="width: 100%;" class="rounded20" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inc_healthy.png">
</div>
<div class="" style="max-width: 100%; padding: 70px 30px 20px; background: #F7F7F7; margin-top: -50px; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #B25694;">7. Learn how to stay healthy and fit as you age</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Master healthy ageing by equipping yourself with knowledge about the human body, common illnesses, and how to adopt a daily fitness routine for holistic wellness.
<br><br>
Trainer: Singapore Training &amp; Development Association <br>
Duration: 8 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2023020140">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #B25694;">8. Gain mindfulness tools for healthy ageing
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Discover how mindfulness plays a role in healthy ageing and learn mindfulness techniques to help seniors improve social interactions and prevent dementia.
<br><br>
Trainer: Tsao Foundation  <br>
Duration: 8 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2020508245">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #B25694;">9. Learn to eat well for healthy living
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Arm yourself with practical knowledge on basic nutrition so you can make better dietary choices and adopt healthy eating habits. Conducted in Mandarin.
<br><br>
Trainer: Fei Yue Community Services  <br>
Duration: 18 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2020508384">Learn more</a>
</p>
</div>

</div>

<div class="" style="max-width: 100%; padding: 15px 0px 0px;">
  <img style="width: 100%;" class="rounded20" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inc_inclusive.png">
</div>
<div class="" style="max-width: 100%; padding: 70px 30px 20px; background: #F7F7F7; margin-top: -50px; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #1F4D7F;">10. Embrace diversity and inclusiveness in the workplace
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Arm yourself with the emotional intelligence to effectively navigate everyday situations with team members and customers with different needs. Suitable for the service industry.
<br><br>
Trainer: LearnCollab Pte Ltd <br>
Duration: 16 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2022013854">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #1F4D7F;">11. Learn how to interact positively in a diverse workplace
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Acquire the tools and techniques to understand the interests of diverse groups at the workplace and learn how to create an inclusive work environment.
<br><br>
Trainer: NTUC LearningHub Pte Ltd<br>
Duration: 7 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2023018462">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #1F4D7F;">12. Gain insights on how to build an inclusive organisation
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Find out how to collaborate with stakeholders from diverse backgrounds and abilities so you can build an inclusive working environment that fosters mutual understanding.
<br><br>
Trainer: SeraphCorp Institute Pte Ltd <br>
Duration: 14 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2023019273">Learn more</a>
</p>
</div>

</div>


<div class="" style="max-width: 100%; padding: 15px 0px 0px;">
  <img style="width: 100%;" class="rounded20" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inc_learning.png">
</div>
<div class="" style="max-width: 100%; padding: 70px 30px 20px; background: #F7F7F7; margin-top: -50px; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #1F4D7F;">13. Pick up tips and tricks to become a better learner
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Learning does not have to be painful. With effective strategies, you can learn better with less stress and retain the knowledge you have learnt for longer periods.
<br><br>
Trainer: Simple IT <br>
Duration: 3 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2023020242">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #1F4D7F;">14. Find out how digitalisation can improve work processes
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Discover how IT technologies such as robotic process automation, data analytics and cloud solutions can enhance innovation and productivity.
<br><br>
Trainer: Republic Polytechnic <br>
Duration: 8 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2019508683">Learn more</a>
</p>
</div>

<div class="" style="width: 100%; padding-bottom: 20px;">
<h3 style="font-size: 18px; color: #1F4D7F;">15. Chart your path for career growth and development
</h3>
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Whether changing careers or re-entering the workforce, staying relevant is crucial. Acquire the knowledge to plan your career path and identify your learning needs effectively.
<br><br>
Trainer: Capelle Consulting Pte Ltd <br>
Duration: 7 hours
<br><br>
<a style="color: #000000;" href="https://www.myskillsfuture.gov.sg/content/portal/en/training-exchange/course-directory/course-detail.html?courseReferenceNumber=TGS-2023018870">Learn more</a>
</p>
</div>

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



