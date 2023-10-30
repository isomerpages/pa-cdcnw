---
title: North West Brisk Walking Club
permalink: /cohesion/november-2023/bwc-article/
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

.rounded25 {
  -webkit-border-radius: 25px;
  -moz-border-radius: 25px;
  border-radius: 25px;
}
  </style>



<article style="max-width: 800px; width: 100%; margin: auto;">

<div style="width: 100%;">
  <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif" alt="North West Cohesion" style="width: 100%; max-width: 100px; position: relative;">
</div>

<div style="width: 100%;">
  <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/promoting-health-wellness.png" alt="Promoting Health and Wellness" style="width: 100%; max-width:">
  <img src="/images/Cohesion/November%202023/title-step-way-healthier.jpg" alt="" style="width: 100%; max-width:">
</div>

<div style="max-width: 100%; padding: 30px 0px 0px;" class="rounded20">
	<img src="/images/Cohesion/November%202023/brisk-walking-kv.jpg" class="rounded20" style="width: 100%; margin-top: 0px;">
</div>

<div style="padding: 20px 0px 0px;">
<p style="font-size: 16px; line-height: 26px;">From weekly strolls in the North West to exploring picturesque green spaces in other parts of Singapore, North West Brisk Walking Club members have found that this low-impact exercise is also a great way to socialise with their ‘kakis’ while staying active.</p>

<p style="font-size: 16px; line-height: 26px;">Let’s find out more!</p>
</div>

<h2 style="color: #B25694; font-weight: bold; font-size: x-large; padding: 15px 0px;">
  <strong>#KopiTalk with North West Brisk Walking Club Members</strong>
</h2>

<div class="rounded25" style="padding: 30px 35px; background: #FFFAED;">

  <div class="w-100" style="padding: 5px 0px; display: inline-table;">
  <img src="/images/Cohesion/November%202023/patricia-quote.jpg" style="max-width: 100%; padding: 10px 0px 15px; background-blend-mode: darken;">
  <img src="/images/Cohesion/November%202023/milo%20pic.png" style="max-width: 50px; float: right; padding: 10px 15px 10px 5px;">
  <p style="font-size: 16px; line-height: 26px; padding-top: 10px; display: table; margin: auto;"><span style="font-weight: bold; color: #B25694;">The kind of kopi I like best is …</span> actually its cousin – Milo. Just like some people cannot start the day with kopi, Milo gives me the energy boost I need.</p>
  </div>

  <div class="w-100" style="padding: 5px 0px; display: inline-table;">
  <img src="/images/Cohesion/November%202023/pat1%20group.png" style="max-width: 300px; float: left; padding: 10px 20px 5px 0px;"><p style="font-size: 16px; line-height: 26px; display: table; margin: auto; padding: 20px 0px 5px;"><span style="font-weight: bold; color: #B25694;">When I’m not working, you’ll find me … </span> taking on the role of CEO at home as I oversee the housework and cooking. Besides that, I find fulfilment in volunteering and enjoy the company of my friends when we go brisk walking. The walks are filled with fun moments as we’ll snap photos or chit chat. We’ll usually wrap up the walk with breakfast or a trip to the market.</p>
  </div>

  <div class="w-100" style="padding: 15px 15px; display: inline-table;">
  <img src="/images/Cohesion/November%202023/pat2%20group.png" style="max-width: 320px; float: right; padding: 10px 0px 5px 20px;">
  <div style="padding: 15px 0px;">
  <p style="font-size: 16px; line-height: 26px; display: table; margin: auto; padding: 0px 0px 15px;"><span style="font-weight: bold; color: #B25694;">My superpower is … </span> being 'Little Miss Sunshine'. I'm a very bubbly person and love to motivate and bring cheer to those around me.</p>
  <p style="font-size: 16px; line-height: 26px; display: table; margin: auto;"><span style="font-weight: bold; color: #B25694;">My favourite place to go brisk walking is at …</span> the&nbsp;Singapore Botanic Gardens. It’s filled with natural beauty and has a rich heritage.</p>
  </div>
  </div>

  <div class="w-100" style="padding: 20px 0px 0px; display: inline-table;">
  <img src="/images/Cohesion/November%202023/pat3%20group.png" style="max-width: 280px; float: left; padding: 0px 20px 5px 0px;">
  <p style="font-size: 16px; line-height: 26px; padding-top: 0px;"><span style="font-weight: bold; color: #B25694;">As a regular Brisk Walking Club member, my top tips are …   </span> to make it a point to go for your daily or weekly walks. When you walk in big group, you’re less likely to skip a walk. Group walks also give you a chance to socialise and make new friends. Don’t forget to take more photos to capture these fun memories!</p>
  </div>

</div>

<div style="padding: 15px 0px;">
</div>

<div class="rounded25" style="padding: 30px 35px; background: #FFFAED;">

  <div class="w-100" style="padding: 5px 0px; display: inline-table;">
  <img src="/images/Cohesion/November%202023/bas-quote.jpg" style="max-width: 100%; padding: 10px 0px 15px; background-blend-mode: darken;">
  <img src="/images/Cohesion/November%202023/coffee.png" style="max-width: 110px; float: left; padding: 10px 15px 10px 5px;">
  <p style="font-size: 16px; line-height: 26px; padding-top: 10px; display: table; margin: auto;"><span style="font-weight: bold; color: #B25694;">எனக்கு மிகவும் பிடித்த கோபி… </span> <br>கோபி-சி எனக்கு மிகவும் பிடிக்கும், சுகாதார நோக்கங்களுக்காக, நான் எப்போதும் கோபி-சி சியு டாயை (குறைந்த சர்க்கரை) தேர்வு செய்ய விரும்புகிறேன்!</p>
  </div>

  <div class="w-100" style="padding: 5px 0px; display: inline-table;">
    <img src="/images/Cohesion/November%202023/bas1%20group.png" style="max-width: 100%; padding: 10px 0px 15px; background-blend-mode: darken;">
  </div>


  <div class="w-100" style="padding: 15px 0px; display: inline-table;">
  <img src="/images/Cohesion/November%202023/bas2%20group.png" style="max-width: 300px; float: right; padding: 10px 0px 5px 20px;">
  <div style="padding: 15px 0px;">
  <p style="font-size: 16px; line-height: 26px; display: table; margin: auto;"><span style="font-weight: bold; color: #B25694;">செம்பவாங் மேற்கில் சமூக தன்னார்வத் தொண்டு செய்தல்…. </span> வடமேற்கில், செம்பவாங் மேற்கில் சமூகத் தன்னார்வத் தொண்டு செய்பவராக நீங்கள் அடிக்கடி என்னைக் காண்பீர்கள். நான் தேவைப்படும் குடும்பங்களுக்கு காய்கறிகளை விநியோகிப்பதன் மூலமும், மாதாந்திர (சிட்-சாட்) சந்திப்பின் போது மூத்தவர்களுடன் தொடர்புகொள்வதன் மூலமும் உதவுவேன். ஆரோக்கியமாக இருக்க, நான் குடியிருப்பாளர்களுடன் விறுவிறுப்பாக நடந்து செல்வேன் </p>
  </div>
  </div>

  <div class="w-100" style="padding: 20px 0px 0px; display: inline-table;">
  <img src="/images/Cohesion/November%202023/bas3%20group.png" style="max-width: 280px; float: left; padding: 0px 20px 5px 0px;">
  <p style="font-size: 16px; line-height: 26px; padding-top: 0px;"><span style="font-weight: bold; color: #B25694;">விறுவிறுப்பான நடைப்பயணத்தின் போது எனக்கு மிகவும் சுவாரஸ்யமான தருணங்கள்…</span> சக குடியிருப்பாளர்களுடன் நான் ஏற்படுத்தும் தொடர்புகள். நடைப்பயணத்தின் போது, பழைய நண்பர்களை சந்திக்கும் வாய்ப்பு, மற்றும் புதிய நண்பர்களின் அறிமுகம். புதிய நடைபாதைகளைக் கண்டுபிடிப்பதில் மகிழ்ச்சி அடைகிறேன், நடைப்பயணத்தின் போது பாதையில் உள்ள பசுமையான சூழலை ரசிக்கிறேன்.</p>
  </div>

  <div class="w-100" style="padding: 20px 0px 0px; display: inline-table;">
  <p style="font-size: 16px; line-height: 26px; padding-top: 0px;">Read Baskaran's interview in English <a href="https://tangoshark-my.sharepoint.com/personal/socialmgr2_sparkfury_com/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fsocialmgr2%5Fsparkfury%5Fcom%2FDocuments%2FNWCDC%20X%20SF%20Folder%2FCohesion%2F2023%2FOct%5FNov2023%20eDM%20and%20eNewsletter%2FGet%20Active%20Kopitalk%20Briskwalking%2FGet%20Active%20Article%20Translation%5FNov%5Fvetted%20by%20Baskaran%5Fedited%2Epdf&amp;parent=%2Fpersonal%2Fsocialmgr2%5Fsparkfury%5Fcom%2FDocuments%2FNWCDC%20X%20SF%20Folder%2FCohesion%2F2023%2FOct%5FNov2023%20eDM%20and%20eNewsletter%2FGet%20Active%20Kopitalk%20Briskwalking&amp;ga=1" target="_new" style="font-weight: bold; color: #B25694;">here</a>.</p>
  </div>

</div>


<div style="padding: 20px 0px 0px;">
<h2 style="color: #B25694; font-weight: bold; font-size: x-large; padding: 15px 0px;">
  <strong>Benefits of regular brisk walking</strong>
</h2>

<div style="max-width: 100%; padding: 0px 0px 0px;" class="rounded20">
  <img src="/images/Cohesion/November%202023/bwc-infographics.png" class="rounded20" style="width: 100%; margin-top: 0px;">
</div>

</div>




<!--CTA-->
<div style="padding: 20px 0px;">
<div class="rounded20" style="width: 100%; background: #EBDFEC; padding: 0px 0px 0px;">
  <div style="padding: 30px 40px;">
    <div style="padding: 0px 10px;">
        <img src="/images/Cohesion/November%202023/bwc-logo.png" style="max-width: 150px;">
        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">Make brisk walking a part of your fitness journey and expand your social circle along the way. All you need is comfortable attire and a pair of sturdy shoes to get started. Join the North West Brisk Walking Club today! Register your interest <a href="https://go.gov.sg/hlclub-interestform" target="_new" style="font-weight: bold; color: #B25694;">here</a>.</p>  
  </div>
</div>
</div>
</div>
<!--CTA End-->










<!--Footer-->
<div class="col-" style="padding: 20px 0px 0px; display: flex;">&nbsp;</div>

<div style="width: 100%; background: #FB5C1F; border-radius: 30px; padding: 0px 0px; display: flex;">
  <div style="width: 100%; padding: 10px 10px; text-align: center; margin: auto;">
    <h1 style="font-family:  Arial; font-size: xx-large; font-weight: bold; color: #FFFFFF;"><em>Keep updated with our latest stories!</em></h1>
    <a href="https://go.gov.sg/subscribe-cohesion" target="_new" style="text-decoration: none;">
      <div style="font-family:  Arial; font-size: large; font-weight: bold; background: #FFFFFF; color: #FB5C1F; padding: 10px 15px; max-width: 320px; margin: auto; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; text-decoration: none;"><em>Subscribe to Cohesion Magazine</em>
      </div>
    </a>

    <div style="width: 100%;">
    <div style="width: 100%; padding: 15px 10px; text-align: center;   display: flex;
  justify-content: center;
  align-items: center;">
      <span style="font-family: Arial; font-weight: bold; font-size: large; color: #FFFFFF;">Follow us on</span> <a href="https://www.facebook.com/nwcdc/" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-facebook.png" style="padding: 5px 7px;"></a>
      <a href="https://www.instagram.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-instagram.png" style="padding: 5px 7px;"></a>
      <a href="https://t.me/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/telegram.png" style="padding: 5px 7px;"></a>
      <a href="https://www.youtube.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-youtube.png" style="padding: 5px 7px;"></a>
    </div>
    </div>

    <div style="width: 100%; text-align: right;"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-arrow.png" style="width: 25px;"></div>

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



