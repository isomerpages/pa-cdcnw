---
title: Interfaith Network @ North West
permalink: /interfaith-network-north-west/
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
  <a href="https://northwest.cdc.gov.sg/cohesion/may-2024/at-a-glance/">
    <img style="width: 100%; max-width: 100px; position: relative; float: left;" alt="North West Cohesion" src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif">
  </a>
</div>

<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive.png">
  <img style="width: 100%; max-width:" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/title_inclusive.png">
</div>

<div style="padding: 20px 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">Inclusivity, harmony and tolerance are values we hold dear in our multicultural and multireligious society. Through Interfaith Network @ North West, faith institutions in the North West have opened their doors to people from other faiths, hosting site tours and interfaith dialogues to build bridges and foster trust. Let’s revisit these journeys together. </p>
</div>

<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_01.png">
</div>

<div style="width: 100%; background-color: #FFEFEF; background: url('https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_02.png') top center repeat-y; background-size: contain;">
  <div style="width: 100%; margin: 0px 0px;">
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin: 0px;">Host</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">Covenant Evangelical Free Church hosted the first Interfaith @ 
North West session online during the COVID-19 pandemic.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Focus</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">The session provided an insight into Christianity and the Evangelical Free denomination. Leaders from other religious organisations also joined in for an interfaith dialogue.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Highlights</h4>
      <p>The online session enabled viewers who tuned in to:</p>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px; padding-bottom: 10px;">Understand Christianity’s core beliefs and the significance of baptism.</li>
        <li style="font-size: 16px; padding-bottom: 10px;">Learn about the church’s involvement in community initiatives.</li>
        <li style="font-size: 16px; padding-bottom: 10px;">Find out more about the interesting design elements of the church</li>
      </ul>
      <p>Curious about the virtual open house? Watch the video <a style="color: #D5262B; font-weight: bold;" href="https://www.facebook.com/watch/live/?ref=watch_permalink&amp;v=705880363394991">here</a>.</p>
    </div>
    <div style="margin: 0px 0px 0px 34%; padding: 0px 50px 20px 0px;">
      <a target="_new" href="https://www.facebook.com/watch/live/?ref=watch_permalink&amp;v=705880363394991"><img style="width: 100%;" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/interfaith1_1.png"></a>
    </div>
  </div>
</div>

<div style="width: 100%; background-color: #FFEFEF; background: url('https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_05.png') top center repeat-y; background-size: contain;">
<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_04.png">
</div>
  <div style="width: 100%; margin: 0px 0px;">
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin: 0px;">Host</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">Masjid Yusof Ishak hosted the second online Interfaith Network @ North West session.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Focus</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">The session shone a spotlight on the Islamic faith, including its key religious tenets and values. An interfaith dialogue and Q&amp;A session allowed participants to deepen their understanding about the religion.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Highlights</h4>
      <p>The virtual session allowed viewers to:</p>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px; padding-bottom: 10px;">Learn all about the five pillars of Islam and the six articles of faith.</li>
        <li style="font-size: 16px; padding-bottom: 10px;">Appreciate the mosque’s unique design which blends traditional Islamic motifs with Nusantara influences.</li>
        <li style="font-size: 16px; padding-bottom: 10px;">Discover this interesting fact: Masjid Yusof Ishak was named after Singapore’s first president, Yusof Ishak.</li>
      </ul>
      <p>Let’s revisit the tour by watching the video <a style="color: #D5262B; font-weight: bold;" href="https://www.facebook.com/watch/live/?ref=watch_permalink&amp;v=276035527246394">here</a>.</p>
    </div>
    <div style="margin: 0px 0px 0px 34%; padding: 0px 50px 20px 0px;">
      <a target="_new" href="https://www.facebook.com/watch/live/?ref=watch_permalink&amp;v=276035527246394"><img style="width: 100%;" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/interfaith2_1.png"></a>
    </div>
  </div>
</div>

<div style="width: 100%; background-color: #FFEFEF; background: url('https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_02.png') top center repeat-y; background-size: contain;">
<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_07.png">
</div>
  <div style="width: 100%; margin: 0px 0px;">
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin: 0px;">Host</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">BW Monastery hosted the first in-person learning journey attended by over 60 guests including students from Republic Polytechnic, Woodgrove Secondary School, Spectra Secondary School, as well as representatives from the North West Youth Assembly.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Focus</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">The visit allowed participants to learn more about Buddhism’s values and traditions, as well as the monastery’s community services. An interactive exchange with the monks allowed participants to deepen their understanding of the Buddhism faith.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Highlights</h4>
      <p>Here are some interesting facts the participants found:</p>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px; padding-bottom: 10px;">BW Monastery stands for “Bliss and Wisdom” Monastery.</li>
        <li style="font-size: 16px; padding-bottom: 10px;">In Buddhism, the Triple Gems stand for the Buddha (the teacher), the Dharma (the teachings) and the Sangha (the Buddhist community).</li>
        <li style="font-size: 16px; padding-bottom: 10px;">The Three Great Buddhas in the Grand Shrine Hall represent Compassion, Perfection, and Wisdom.</li>
      </ul>
      <p>To learn more, experience the visit through the eyes of John, a student of Republic Monastery. </p>
      <p>Read the full article <a style="color: #D5262B; font-weight: bold;" href="https://northwest.cdc.gov.sg/cohesion/may-2023/interfaith-network/">here</a>.</p>
    </div>
<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_09.png">
</div>
  </div>
</div>


<div style="width: 100%; background-color: #FFEFEF; background: url('https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_05.png') top center repeat-y; background-size: contain;">
<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_10.png">
</div>
  <div style="width: 100%; margin: 0px 0px;">
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin: 0px;">Host</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">Holy Tree Sri Balasubramaniar Temple opened its doors to over 200 Secondary 3 students from the School of Science and Technology Singapore.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Focus</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">The curated temple tour enabled students to learn about the Hindu faith and engage in dialogue to foster greater respect and understanding. The conversation was enriched by candid sharing and perspectives from leaders of other faiths.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Highlights</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px; padding-bottom: 10px;">Participants discovered all about the deities, traditions and cultural heritage of the Hindu faith during the tour.</li>
        <li style="font-size: 16px; padding-bottom: 10px;">Over a hearty meal, they shared stories, connected further and discussed their appreciation for diversity.</li>
      </ul>
      <p>Check out how participants felt about the visit in this <a style="color: #D5262B; font-weight: bold;" href="https://www.facebook.com/watch/?v=2043426709326042">video reel</a>.</p>
    </div>
    <div style="margin: 0px 0px 0px 34%; padding: 0px 50px 20px 0px; text-align: center;">
      <iframe allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share" allowfullscreen="true" frameborder="0" scrolling="no" style="border:none;overflow:hidden" height="476" width="267" src="https://www.facebook.com/plugins/video.php?height=476&amp;href=https%3A%2F%2Fwww.facebook.com%2Fnwcdc%2Fvideos%2F2043426709326042%2F&amp;show_text=false&amp;width=267&amp;t=0"></iframe>
    </div>
  </div>
</div>


<div style="width: 100%; background-color: #FFEFEF; background: url('https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_02.png') top center repeat-y; background-size: contain;">
<div style="width: 100%;">
  <img style="width: 100%; max-width:" src="https://staging-lite.d2zr4mfri8ph9q.amplifyapp.com/images/Cohesion/May%202024/inclusive_infographics_12.png">
</div>
  <div style="width: 100%; margin: 0px 0px;">
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin: 0px;">Host</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">Shang Di Miao Chai Kong Temple, Hong Tho Bilw Temple and New Life Bible-Presbyterian Church were hosts to more than 100 students from Marsiling Secondary School for this interfaith visit.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Focus</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px;">In this eye-opening learning journey to various faith institutions, students learnt more about two different religions: the Taoism and Presbyterian faiths. This allowed them to appreciate the religious diversity in our community.</li>
      </ul>
    </div>
    <div style="margin: 0px 30px 0px 34%;">
      <h4 style="color: #D5262B; font-weight: bold; font-size: 16px; margin-bottom: 0px;">Highlights</h4>
      <ul style="padding: 0px 15px;">
        <li style="font-size: 16px; padding-bottom: 10px;">The students found out more about various religions, for example, in Taoism, worshippers venerate different deities through different rituals and practices.</li>
        <li style="font-size: 16px; padding-bottom: 10px;">The visit was educational, enriching and interesting, and this immersion into different faiths helped participants to foster better respect amongst different communities.</li>
      </ul>
      <p>Here are the students’ impression of the visit in this <a style="color: #D5262B; font-weight: bold;" href="https://www.instagram.com/p/C4z_2JCShLx/?hl=en">video</a>.</p>
    </div>
    <div style="margin: 0px 0px 0px 34%; padding: 0px 50px 20px 0px; text-align: center;">
      <blockquote style="background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:540px; min-width:326px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);" data-instgrm-version="14" data-instgrm-permalink="https://www.instagram.com/reel/C4z_2JCShLx/?utm_source=ig_embed&amp;utm_campaign=loading" class="instagram-media"><div style="padding:16px;"> <a target="_blank" style="background:#FFFFFF; line-height:0; padding:0 0; text-align:center; text-decoration:none; width:100%;" href="https://www.instagram.com/reel/C4z_2JCShLx/?utm_source=ig_embed&amp;utm_campaign=loading"> <div style="display: flex; flex-direction: row; align-items: center;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 40px; margin-right: 14px; width: 40px;"></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 100px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 60px;"></div></div></div><div style="padding: 19% 0;"></div> <div style="display:block; height:50px; margin:0 auto 12px; width:50px;"><svg xmlns:xlink="https://www.w3.org/1999/xlink" xmlns="https://www.w3.org/2000/svg" version="1.1" viewBox="0 0 60 60" height="50px" width="50px"><g fill-rule="evenodd" fill="none" stroke-width="1" stroke="none"><g fill="#000000" transform="translate(-511.000000, -20.000000)"><g><path d="M556.869,30.41 C554.814,30.41 553.148,32.076 553.148,34.131 C553.148,36.186 554.814,37.852 556.869,37.852 C558.924,37.852 560.59,36.186 560.59,34.131 C560.59,32.076 558.924,30.41 556.869,30.41 M541,60.657 C535.114,60.657 530.342,55.887 530.342,50 C530.342,44.114 535.114,39.342 541,39.342 C546.887,39.342 551.658,44.114 551.658,50 C551.658,55.887 546.887,60.657 541,60.657 M541,33.886 C532.1,33.886 524.886,41.1 524.886,50 C524.886,58.899 532.1,66.113 541,66.113 C549.9,66.113 557.115,58.899 557.115,50 C557.115,41.1 549.9,33.886 541,33.886 M565.378,62.101 C565.244,65.022 564.756,66.606 564.346,67.663 C563.803,69.06 563.154,70.057 562.106,71.106 C561.058,72.155 560.06,72.803 558.662,73.347 C557.607,73.757 556.021,74.244 553.102,74.378 C549.944,74.521 548.997,74.552 541,74.552 C533.003,74.552 532.056,74.521 528.898,74.378 C525.979,74.244 524.393,73.757 523.338,73.347 C521.94,72.803 520.942,72.155 519.894,71.106 C518.846,70.057 518.197,69.06 517.654,67.663 C517.244,66.606 516.755,65.022 516.623,62.101 C516.479,58.943 516.448,57.996 516.448,50 C516.448,42.003 516.479,41.056 516.623,37.899 C516.755,34.978 517.244,33.391 517.654,32.338 C518.197,30.938 518.846,29.942 519.894,28.894 C520.942,27.846 521.94,27.196 523.338,26.654 C524.393,26.244 525.979,25.756 528.898,25.623 C532.057,25.479 533.004,25.448 541,25.448 C548.997,25.448 549.943,25.479 553.102,25.623 C556.021,25.756 557.607,26.244 558.662,26.654 C560.06,27.196 561.058,27.846 562.106,28.894 C563.154,29.942 563.803,30.938 564.346,32.338 C564.756,33.391 565.244,34.978 565.378,37.899 C565.522,41.056 565.552,42.003 565.552,50 C565.552,57.996 565.522,58.943 565.378,62.101 M570.82,37.631 C570.674,34.438 570.167,32.258 569.425,30.349 C568.659,28.377 567.633,26.702 565.965,25.035 C564.297,23.368 562.623,22.342 560.652,21.575 C558.743,20.834 556.562,20.326 553.369,20.18 C550.169,20.033 549.148,20 541,20 C532.853,20 531.831,20.033 528.631,20.18 C525.438,20.326 523.257,20.834 521.349,21.575 C519.376,22.342 517.703,23.368 516.035,25.035 C514.368,26.702 513.342,28.377 512.574,30.349 C511.834,32.258 511.326,34.438 511.181,37.631 C511.035,40.831 511,41.851 511,50 C511,58.147 511.035,59.17 511.181,62.369 C511.326,65.562 511.834,67.743 512.574,69.651 C513.342,71.625 514.368,73.296 516.035,74.965 C517.703,76.634 519.376,77.658 521.349,78.425 C523.257,79.167 525.438,79.673 528.631,79.82 C531.831,79.965 532.853,80.001 541,80.001 C549.148,80.001 550.169,79.965 553.369,79.82 C556.562,79.673 558.743,79.167 560.652,78.425 C562.623,77.658 564.297,76.634 565.965,74.965 C567.633,73.296 568.659,71.625 569.425,69.651 C570.167,67.743 570.674,65.562 570.82,62.369 C570.966,59.17 571,58.147 571,50 C571,41.851 570.966,40.831 570.82,37.631"></path></g></g></g></svg></div><div style="padding-top: 8px;"> <div style="color:#3897f0; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:550; line-height:18px;">View this post on Instagram</div></div><div style="padding: 12.5% 0;"></div> <div style="display: flex; flex-direction: row; margin-bottom: 14px; align-items: center;"><div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(0px) translateY(7px);"></div> <div style="background-color: #F4F4F4; height: 12.5px; transform: rotate(-45deg) translateX(3px) translateY(1px); width: 12.5px; flex-grow: 0; margin-right: 14px; margin-left: 2px;"></div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(9px) translateY(-18px);"></div></div><div style="margin-left: 8px;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 20px; width: 20px;"></div> <div style="width: 0; height: 0; border-top: 2px solid transparent; border-left: 6px solid #f4f4f4; border-bottom: 2px solid transparent; transform: translateX(16px) translateY(-4px) rotate(30deg)"></div></div><div style="margin-left: auto;"> <div style="width: 0px; border-top: 8px solid #F4F4F4; border-right: 8px solid transparent; transform: translateY(16px);"></div> <div style="background-color: #F4F4F4; flex-grow: 0; height: 12px; width: 16px; transform: translateY(-4px);"></div> <div style="width: 0; height: 0; border-top: 8px solid #F4F4F4; border-left: 8px solid transparent; transform: translateY(-4px) translateX(8px);"></div></div></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center; margin-bottom: 24px;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 224px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 144px;"></div></div></a><p style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;"><a target="_blank" style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none;" href="https://www.instagram.com/reel/C4z_2JCShLx/?utm_source=ig_embed&amp;utm_campaign=loading">A post shared by North West CDC (@northwestcdc)</a></p></div></blockquote> 
    </div>
  </div>
</div>

<div style="width: 100%; background-color: #FFEFEF; height: 100px; -webkit-border-bottom-right-radius: 20px; -webkit-border-bottom-left-radius: 20px; -moz-border-radius-bottomright: 20px; -moz-border-radius-bottomleft: 20px; border-bottom-right-radius: 20px; border-bottom-left-radius: 20px;">
</div>



<div style="padding: 20px 0px;">
<div style="width: 100%; background: #F5E1E0; padding: 0px 0px 0px;" class="rounded20">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 0px;">
      <p style="font-size: 20px; font-weight: bold; text-align: left; color: #DA312C; margin: 0px 0px;"><strong>About Interfaith Network @ North West</strong>
      </p> 

      <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px 0px;">At Interfaith Network @ North West, we believe that embracing and celebrating diversity enriches our community. Learn more about how this programme inspires interfaith conversations to build peace and harmony in our community.
      </p> 

      <div style="max-width: 100%; padding: 30px 0px;">
        <div class="video-container rounded20">
          <iframe allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/rke2StZwfHs?si=jz2UNiwb1ZWKN6uY" height="315" width="560"></iframe>
        </div>
      </div>

      <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px 0px;">Join us in cherishing this inclusivity and understanding by participating in our upcoming events. For more information on how you can be part of this initiative, please email <a style="font-weight: bold; color: #D5262B;" target="_new" href="northwestcdc_partnerships@pa.gov.sg">northwestcdc_partnerships@pa.gov.sg</a>
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


