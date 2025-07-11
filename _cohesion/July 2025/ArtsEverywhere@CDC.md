---
title: ArtsEverywhere@CDC
permalink: /artseverywhere-cdc/
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
.float-right {float: right;}
.text-center {text-align: center;}
.text-left {text-align: left;}
.text-right {text-align: right;}

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
  <img style="width: 100%;" src="https://northwest.cdc.gov.sg/images/Cohesion/September%202024/inclusive_communities.png">
  <img style="width: 100%;" alt="" src="/images/Cohesion/July%202025/title_11_free.png">
</div>


<div style="padding: 20px 0px 20px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;">Free performances? Don't miss out! ArtsEverywhere@CDC is buzzing with both large-scale shows and street art performances, showcasing the best of local talent. 
<br><br>
Expect vibrant cultural performances, hands-on fringe activities, and plenty of community fun for all ages as we celebrate SG60 together! 
<br><br>
Here are 11 performances to look out for that’ll make your weekends way more interesting! 
</p>
</div>

<div class="" style="max-width: 100%; padding: 0px 0px;">
  <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/ae_bg_01.jpg">
</div>

<div class="" style="max-width: 100%; padding: 0px 0px; background: url('/images/Cohesion/July%202025/ae_bg_02.jpg') top center; background-size: cover; background-repeat: repeat-y;">

  <p style="font-size: 24px; line-height: 26px; text-align: center; font-weight: bold; padding: 40px 10% 10px; margin: 0px; color: #542A9A;">Large scale performances with dazzling visuals and&nbsp;powerful storytelling</p>


  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center;">
    <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">1. Move Your World by O School</p>
    <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f1.jpg">
    <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Our residents had front-row seats to experience the Malay culture and heritage, transporting them back to the good old kampong days - where life was all about gotong-royong (mutual cooperation) and community spirit.</p>
  </div>

  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center;">
    <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">2. A Tribute to Heritage, a Celebration of Diversity by Singapore Chinese Dance Theatre </p>
    <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f2.jpg">
    <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Celebrate Singapore's rich cultural heritage as Chinese, Malay, and Indian dance traditions come alive in a vibrant display of movement and storytelling. Continue the experience with hands-on fringe activities – try making intricate Indian crafts, learn meditative Chinese arts, and create traditional Malay art forms. </p>
  </div>

  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center;">
    <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">3. Camino Flamenco by Flamenco Sin Fronteras </p>
    <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f3.jpg">
    <p style="ffont-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Discover the journey of the flamenco, which traces its roots from India and the Middle East to Spain. This show blends cultures and dances, revealing the magic behind the flamenco's powerful rhythm. Don't forget to join the fun dance workshop to learn flamenco steps, kathak gestures, and Middle Eastern spins. </p>
  </div>


  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center;">
    <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">4. The Tiger Hero by Paper Monkey Theatre</p>
    <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f4.jpg">
    <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Dive into the magical world of Chinese hand puppetry as legendary tales like Wu Song come alive with stunning artistry and powerful storytelling. Get hands-on with various Chinese puppetry styles and unlock the secrets behind their moves during the fringe activities. </p>
  </div>


  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center;">
    <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">5. Yesterday Once More by Rudy Djoe &amp; Kenchana Jazz</p>
    <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f5.jpg">
    <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Take a journey down memory lane in this soulful showcase featuring timeless folk, jazz and Latin pop melodies including Chan Mali Chan, Burung Kakak Tua, Tian Mi Mi and Rose, Rose I Love You. Then, get moving in "Let's Cha Cha Cha!" – learn fun, easy steps and that capture the charm of the golden dance era! </p>
  </div>


  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center;">
    <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">6. Where We Belong by Act 3 International </p>
    <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f6.jpg">
    <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Immerse yourself in this magical storytelling journey that brings an island village to life. Younger audiences will delight in the playful, interactive style of this heartwarming tale. Don't forget to let the fun continue through imaginative play in a hands-on drama workshop. </p>
  </div>

  <p style="font-size: 24px; line-height: 26px; text-align: center; font-weight: bold; padding: 40px 10% 10px; margin: 0px; color: #542A9A;">Musical street performances by rising stars </p>

  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center; display: inline-flex;">
      <div style="padding: 0px 0px; margin: 0px 0px;" class="col-12 w-100">
      <div class="col-4 text-center float-left">
        <div style="padding: 20px 0px 0px;">
          <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f7.jpg">
        </div>
      </div>
      <div class="col-8 float-left text-left">
        <div style="padding: 20px 1rem 10px;">
          <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">7. <a style="color: #542A9A;" target="_new" href="https://www.instagram.com/p/DIxxlbjh22U/">Shayne Ko</a></p>
          <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Be awed by this 9-year old's incredible talent, whose enchanting piano performances have captured the hearts of audiences. Besides the piano, Shayne masterfully blends keyboard skills, finger drumming and mesmerising loops to elevate his performance!</p>
        </div>
      </div>
      </div>
  </div>


  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center; display: inline-flex;">
      <div style="padding: 0px 0px; margin: 0px 0px;" class="col-12 w-100">
      <div class="col-4 text-center float-left">
        <div style="padding: 20px 0px 0px;">
          <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f8.jpg">
        </div>
      </div>
      <div class="col-8 float-left text-left">
        <div style="padding: 20px 1rem 10px;">
          <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">8. <a style="color: #542A9A;" target="_new" href="https://www.instagram.com/hayleymusiclover/">Hayley Ho</a></p>
          <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Let the enchanting melodies of the guzheng fill the air as 14-year-old Hayley performs a vibrant medley of English, Chinese, Hokkien, and K-pop tunes. Her expressive playing brings each piece to life, inviting audiences of all ages to enjoy the beauty of this traditional instrument. </p>
        </div>
      </div>
      </div>
  </div>


  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center; display: inline-flex;">
      <div style="padding: 0px 0px; margin: 0px 0px;" class="col-12 w-100">
      <div class="col-4 text-center float-left">
        <div style="padding: 20px 0px 0px;">
          <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f9.jpg">
        </div>
      </div>
      <div class="col-8 float-left text-left">
        <div style="padding: 20px 1rem 10px;">
          <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">9. <a style="color: #542A9A;" target="_new" href="https://www.instagram.com/lee_theodora/">Theodora Lee</a></p>
          <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">This 10-year-old musician is sure to charm you with her singing and stage presence. Fresh from winning Cristofori's Got Talent 2024, Theodora is also a multi-instrumentalist and plays the piano, keyboard, ukelele, and guitar. </p>
        </div>
      </div>
      </div>
  </div>


  <p style="font-size: 24px; line-height: 26px; text-align: center; font-weight: bold; padding: 40px 20% 10px; margin: 0px; color: #542A9A;">Movement and street theater performances full of magic and entertainment</p>

  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center; display: inline-flex;">
      <div style="padding: 0px 0px; margin: 0px 0px;" class="col-12 w-100">
      <div class="col-4 text-center float-left">
        <div style="padding: 20px 0px 0px;">
          <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f10.jpg">
        </div>
      </div>
      <div class="col-8 float-left text-left">
        <div style="padding: 20px 1rem 10px;">
          <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">10. Jackie Chionh</p>
          <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Enjoy a unique performance that blends magic and cardistry. Watch as Jackie shows off skillful moves and surprising tricks that showcase passion and creativity. It's a chance to be inspired by an artist who’s overcome challenges through the art of performance. </p>
        </div>
      </div>
      </div>
  </div>

  <div class="" style="max-width: 100%; padding: 0px 12% 0px; margin: 0px; text-align: center; display: inline-flex;">
      <div style="padding: 0px 0px; margin: 0px 0px;" class="col-12 w-100">
      <div class="col-4 text-center float-left">
        <div style="padding: 20px 0px 0px;">
          <img style="width: 100%;" class="" src="/images/Cohesion/July%202025/f11.jpg">
        </div>
      </div>
      <div class="col-8 float-left text-left">
        <div style="padding: 20px 1rem 10px;">
          <p style="font-size: 20px; line-height: 26px; text-align: justify; font-weight: bold; font-style: italic; color: #542A9A;">11. Gabriel Lim</p>
          <p style="font-size: 16px;line-height: initial;text-align: justify;margin: 10px 0px 30px;">Be thrilled by Gabriel's exciting act featuring handbalancing, contortion, and masterful cigar box juggling. With his focus, control and balance taking centre stage, this display of strength and skill will keep you entertained from start to finish. </p>
        </div>
      </div>
      </div>
  </div>

  <div class="" style="max-width: 100%; padding: 0px 12% 50px; margin: 0px; text-align: center; display: flex; border-bottom: 3px solid #542A9A;">
  </div>



</div>


<div style="padding: 40px 0px 0px;">
<p style="font-size: 22px; font-weight: bold; text-align: left; color: #542A9A; margin: 10px 0px 0px;">Here's what audiences have to say about ArtsEverywhere@CDC performances</p>
</div>

<div style="padding: 0px 0px 10px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;"><span style="font-weight: bold; color: #7B669E;">What: My Identity: Beyond Artistry by Brahmastra<br>
Where: Khatib Plaza</span>
<br><br>
Besides enjoying the dance musical, brothers Teoh Yu Quan and Teoh Yu Le both had fun exploring the fringe activities that gave them a closer look at Indian arts and culture. </p>
</div>


  <div class="" style="max-width: 100%; padding: 0px 0px; margin: 0px; text-align: center; display: inline-flex;">
      <div style="padding: 0px 0px; margin: 0px 0px;" class="col-12 w-100">
      <div class="col-6 text-center">
        <div class="rounded20" style="padding: 20px 0px 0px; float: left;">
          <iframe class="rounded20" src="https://www.youtube.com/embed/n1G96vf9qH4" frameborder="0" allowfullscreen="true" height="569" width="320"></iframe>
        </div>
      </div>
      <div class="col-6 float-left text-left">
        <div style="padding: 20px 1rem 10px;">
<p style="font-size: 16px; line-height: 26px; text-align: justify;"><span style="font-weight: bold; color: #7B669E;">Learning about Indian instruments </span>
<br><br>
"What caught my attention was the different Indian instruments – I've never seen or touched most of them before, so it was really interesting and engaging to find out how they work and the sounds they make. I've also learned to appreciate Indian heritage and arts!" 
<br>
<span style="font-style: italic;">- Teoh Yu Quan, 15 years old</span></p>
<br>
<p style="font-size: 16px; line-height: 26px; text-align: justify;"><span style="font-weight: bold; color: #7B669E;">Appreciating Indian music and art </span>
<br><br>
"The Indian music at the performance was memorable and really brightened up my day! I also enjoyed the photo booth because there were lots of interesting Indian art, props and decorations – it made the photo-taking fun and turned out to be a great family bonding experience."
<br><br>
<span style="font-style: italic;">- Teoh Yu Le, 13 years old</span></p>
        </div>
      </div>
      </div>
  </div>








<div style="background: #7B669E; margin: 30px 0px 0px; -webkit-border-top-left-radius: 25px; -webkit-border-top-right-radius: 25px; -moz-border-radius-topleft: 25px; -moz-border-radius-topright: 25px; border-top-left-radius: 25px; border-top-right-radius: 25px;">
  <div style="text-align: left; display: flex; margin: 0px auto; padding: 20px 35px 18px; color: #FFFFFF; font-size: 18px; font-weight: bold; font-family: Arial, 'sans-serif;';">
          <strong style="font-weight: bold; color: #FFFFFF;">Be part of the next performance!</strong>
  </div>
</div>

<div style="padding: 20px 30px 20px; background: #EFE9F8; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">
  <div class="w-100">

    <p style="font-size: 16px; line-height: 26px; padding: 10px 5px 15px; margin: 0px 0px;">
      Experience the joy of live performances across Singapore – for free! Here's what's coming up in the
North&nbsp;West:
<br><br>
<span style="font-weight: bold; color: #7B669E; font-style: italic; font-size: 18px;">A Tribute to Heritage, A Celebration of Diversity</span><br> 
<span style="font-weight: bold; color: #7B669E;">Presented by: Singapore Chinese Dance Theatre and Partners</span><br>
<br>
<img style="max-width: 20px; padding-right: 5px; display: inline;" src="/images/Cohesion/July%202025/calendar_icon.png">Date: 12 July 2025<br>
<img style="max-width: 20px; padding-right: 5px; display: inline;" src="/images/Cohesion/July%202025/time_icon.png">Time: 6.30pm to 8.30pm <br>
<img style="max-width: 20px; padding-right: 5px; display: inline;" src="/images/Cohesion/July%202025/marker_icon.png">Venue: Limbang Shopping Centre<br>
<br>
<span style="font-weight: bold; color: #7B669E; font-style: italic; font-size: 18px;">Wonders of the Animal Kingdom</span><br>
<span style="font-weight: bold; color: #7B669E;">Presented by Reverberance 回响</span><br>
<br>
<img style="max-width: 20px; padding-right: 5px; display: inline;" src="/images/Cohesion/July%202025/calendar_icon.png">Date: 26 July 2025<br>
<img style="max-width: 20px; padding-right: 5px; display: inline;" src="/images/Cohesion/July%202025/time_icon.png">Time: 10am to 1pm <br>
<img style="max-width: 20px; padding-right: 5px; display: inline;" src="/images/Cohesion/July%202025/marker_icon.png">Venue: Hardcourt in front of Blk 413 Yishun Ring Road<br>
<br>
<a style="color: #7B669E; font-weight: bold;" target="_new" href="https://form.gov.sg/66cd5073725169f909275a33">Register your interest</a> now and you'll also receive a game card to redeem a free snack at the performance. 

What else is coming? Find the next performance at <a style="color: #7B669E; font-style: italic; font-weight: bold;" target="_new" href="https://go.gov.sg/artseverywhere-cdc">https://go.gov.sg/artseverywhere-cdc</a>
    </p>

  </div>

  <div style="max-width: 100%; background: #FDFDFE; padding: 10px 20px;" class="rounded20">
    <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px; margin: 0px;"><em style="font-weight: normal; color: #7B669E;">More on this topic:</em></p>
    <hr style="margin: 10px 0px; color: #7B669E;">
    <p style="font-size: 16px; line-height: 26px; text-align: justify; padding: 0px 0px 5px; margin: 0px; color: #7B669E;">
      &gt; &nbsp;<a href="https://northwest.cdc.gov.sg/cohesion/may-2025/arts-everywhere/" style="font-family: 'Lato', sans-serif; font-size: 16px; line-height: 26px; font-weight: bold; color: #7B669E; text-decoration: underline;" target="new"><span style="text-decoration: underline;">Bigger, Better, and More Exciting ArtsEverywhere@CDC Performances Coming Your Way</span>
      </a>
    </p>
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






