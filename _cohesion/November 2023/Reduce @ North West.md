---
title: Reduce @ North West
permalink: /cohesion/november-2023/reduce-article/
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

@media only screen and (max-width: 767px) {
  [class*="col-"] {
    width: 100%;
  }

  .slider--cover .slider__inner {
    height: 600px !important;
  }

.slide-txt {font-size:  16px; color: #FFFFFF; font-weight: 600; padding: 10px 25px; margin-top: 0px; line-height: initial !important;}  
}

.w-100 {max-width: 100% !important;}

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
  <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-cohesion-logo-2023%201.gif" alt="North West Cohesion" style="width: 100%; max-width: 100px; position: relative; padding-left: 10px; float:left !important; padding-bottom: 20px;">
</div>

<div style="width: 100%;">
  <img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/advocating-green-living.png" style="width: 100%;">
  <img src="/images/Cohesion/November%202023/title-smart-ways.jpg" style="width: 100%;">
</div>

<div style="max-width: 100%; padding: 30px 0px 0px;" class="rounded20">
	<img src="/images/Cohesion/November%202023/smart-ways-kv.jpg" class="rounded20" style="width: 100%;">
</div>

<div style="padding: 20px 0px;">
<p style="font-size: 16px; line-height: 26px;">The path to a greener lifestyle starts at home. With rising energy costs, it’s time to kickstart your green journey by changing how you consume electricity and water. Let’s find out how 2 North West residents embrace green habits in their everyday lives to save money and our earth.</p>
</div>

<div style="padding: 20px 0px;">
  <p style="font-size: 24px; font-weight: bold; text-align: left; color: #0C6C37; margin: 0px 0px;"><strong>North West Residents Share Their Eco-Friendly Practices</strong>
  </p>
</div>

<div style="padding: 20px 0px; text-align: center; margin: 0px auto; width: 100%;">
  <div style="margin: 0px auto;">
<blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/p/CyqbYR4p3dN/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:540px; min-width:326px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:16px;"> <a href="https://www.instagram.com/p/CyqbYR4p3dN/?utm_source=ig_embed&amp;utm_campaign=loading" style="background:#FFFFFF; line-height:0; padding:0 0; text-align:center; text-decoration:none; width:100%;" target="_blank"> <div style="display: flex; flex-direction: row; align-items: center;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 40px; margin-right: 14px; width: 40px;"></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 100px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 60px;"></div></div></div><div style="padding: 19% 0;"></div> <div style="display:block; height:50px; margin:0 auto 12px; width:50px;"><svg width="50px" height="50px" viewBox="0 0 60 60" version="1.1" xmlns="https://www.w3.org/2000/svg" xmlns:xlink="https://www.w3.org/1999/xlink"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g transform="translate(-511.000000, -20.000000)" fill="#000000"><g><path d="M556.869,30.41 C554.814,30.41 553.148,32.076 553.148,34.131 C553.148,36.186 554.814,37.852 556.869,37.852 C558.924,37.852 560.59,36.186 560.59,34.131 C560.59,32.076 558.924,30.41 556.869,30.41 M541,60.657 C535.114,60.657 530.342,55.887 530.342,50 C530.342,44.114 535.114,39.342 541,39.342 C546.887,39.342 551.658,44.114 551.658,50 C551.658,55.887 546.887,60.657 541,60.657 M541,33.886 C532.1,33.886 524.886,41.1 524.886,50 C524.886,58.899 532.1,66.113 541,66.113 C549.9,66.113 557.115,58.899 557.115,50 C557.115,41.1 549.9,33.886 541,33.886 M565.378,62.101 C565.244,65.022 564.756,66.606 564.346,67.663 C563.803,69.06 563.154,70.057 562.106,71.106 C561.058,72.155 560.06,72.803 558.662,73.347 C557.607,73.757 556.021,74.244 553.102,74.378 C549.944,74.521 548.997,74.552 541,74.552 C533.003,74.552 532.056,74.521 528.898,74.378 C525.979,74.244 524.393,73.757 523.338,73.347 C521.94,72.803 520.942,72.155 519.894,71.106 C518.846,70.057 518.197,69.06 517.654,67.663 C517.244,66.606 516.755,65.022 516.623,62.101 C516.479,58.943 516.448,57.996 516.448,50 C516.448,42.003 516.479,41.056 516.623,37.899 C516.755,34.978 517.244,33.391 517.654,32.338 C518.197,30.938 518.846,29.942 519.894,28.894 C520.942,27.846 521.94,27.196 523.338,26.654 C524.393,26.244 525.979,25.756 528.898,25.623 C532.057,25.479 533.004,25.448 541,25.448 C548.997,25.448 549.943,25.479 553.102,25.623 C556.021,25.756 557.607,26.244 558.662,26.654 C560.06,27.196 561.058,27.846 562.106,28.894 C563.154,29.942 563.803,30.938 564.346,32.338 C564.756,33.391 565.244,34.978 565.378,37.899 C565.522,41.056 565.552,42.003 565.552,50 C565.552,57.996 565.522,58.943 565.378,62.101 M570.82,37.631 C570.674,34.438 570.167,32.258 569.425,30.349 C568.659,28.377 567.633,26.702 565.965,25.035 C564.297,23.368 562.623,22.342 560.652,21.575 C558.743,20.834 556.562,20.326 553.369,20.18 C550.169,20.033 549.148,20 541,20 C532.853,20 531.831,20.033 528.631,20.18 C525.438,20.326 523.257,20.834 521.349,21.575 C519.376,22.342 517.703,23.368 516.035,25.035 C514.368,26.702 513.342,28.377 512.574,30.349 C511.834,32.258 511.326,34.438 511.181,37.631 C511.035,40.831 511,41.851 511,50 C511,58.147 511.035,59.17 511.181,62.369 C511.326,65.562 511.834,67.743 512.574,69.651 C513.342,71.625 514.368,73.296 516.035,74.965 C517.703,76.634 519.376,77.658 521.349,78.425 C523.257,79.167 525.438,79.673 528.631,79.82 C531.831,79.965 532.853,80.001 541,80.001 C549.148,80.001 550.169,79.965 553.369,79.82 C556.562,79.673 558.743,79.167 560.652,78.425 C562.623,77.658 564.297,76.634 565.965,74.965 C567.633,73.296 568.659,71.625 569.425,69.651 C570.167,67.743 570.674,65.562 570.82,62.369 C570.966,59.17 571,58.147 571,50 C571,41.851 570.966,40.831 570.82,37.631"></path></g></g></g></svg></div><div style="padding-top: 8px;"> <div style="color:#3897f0; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:550; line-height:18px;">View this post on Instagram</div></div><div style="padding: 12.5% 0;"></div> <div style="display: flex; flex-direction: row; margin-bottom: 14px; align-items: center;"><div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(0px) translateY(7px);"></div> <div style="background-color: #F4F4F4; height: 12.5px; transform: rotate(-45deg) translateX(3px) translateY(1px); width: 12.5px; flex-grow: 0; margin-right: 14px; margin-left: 2px;"></div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(9px) translateY(-18px);"></div></div><div style="margin-left: 8px;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 20px; width: 20px;"></div> <div style="width: 0; height: 0; border-top: 2px solid transparent; border-left: 6px solid #f4f4f4; border-bottom: 2px solid transparent; transform: translateX(16px) translateY(-4px) rotate(30deg)"></div></div><div style="margin-left: auto;"> <div style="width: 0px; border-top: 8px solid #F4F4F4; border-right: 8px solid transparent; transform: translateY(16px);"></div> <div style="background-color: #F4F4F4; flex-grow: 0; height: 12px; width: 16px; transform: translateY(-4px);"></div> <div style="width: 0; height: 0; border-top: 8px solid #F4F4F4; border-left: 8px solid transparent; transform: translateY(-4px) translateX(8px);"></div></div></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center; margin-bottom: 24px;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 224px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 144px;"></div></div></a><p style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;"><a href="https://www.instagram.com/p/CyqbYR4p3dN/?utm_source=ig_embed&amp;utm_campaign=loading" style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none;" target="_blank">A post shared by Shubhada Jayant Bhide (@shub_sg)</a></p></div></blockquote>
  </div>
</div>


<div style="max-width: 100%;">
  <img src="/images/Cohesion/November%202023/shub-quote.jpg" class="rounded20" style="width: 100%; margin-top: 30px;">
</div>

<div style="max-width: 100%; text-align: center">
  <img src="/images/Cohesion/November%202023/shub-tips-title.jpg" class="" style="width: 100%; margin: 50px auto 30px; max-width: 640px;">
</div>

<div style="max-width: 100%;">
  <img src="/images/Cohesion/November%202023/shub-tips-card%201.jpg" class="rounded20" style="width: 100%; margin: 0px;">
</div>


<div style="padding: 20px 0px; text-align: center; margin: 50px auto 20px; width: 100%;">
  <div style="margin: 0px auto;">
<blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/p/Cyz2Rxdr0Od/?utm_source=ig_embed&amp;utm_campaign=loading" data-instgrm-version="14" style="background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:540px; min-width:326px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:16px;"> <a href="https://www.instagram.com/p/Cyz2Rxdr0Od/?utm_source=ig_embed&amp;utm_campaign=loading" style="background:#FFFFFF; line-height:0; padding:0 0; text-align:center; text-decoration:none; width:100%;" target="_blank"> <div style="display: flex; flex-direction: row; align-items: center;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 40px; margin-right: 14px; width: 40px;"></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 100px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 60px;"></div></div></div><div style="padding: 19% 0;"></div> <div style="display:block; height:50px; margin:0 auto 12px; width:50px;"><svg width="50px" height="50px" viewBox="0 0 60 60" version="1.1" xmlns="https://www.w3.org/2000/svg" xmlns:xlink="https://www.w3.org/1999/xlink"><g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd"><g transform="translate(-511.000000, -20.000000)" fill="#000000"><g><path d="M556.869,30.41 C554.814,30.41 553.148,32.076 553.148,34.131 C553.148,36.186 554.814,37.852 556.869,37.852 C558.924,37.852 560.59,36.186 560.59,34.131 C560.59,32.076 558.924,30.41 556.869,30.41 M541,60.657 C535.114,60.657 530.342,55.887 530.342,50 C530.342,44.114 535.114,39.342 541,39.342 C546.887,39.342 551.658,44.114 551.658,50 C551.658,55.887 546.887,60.657 541,60.657 M541,33.886 C532.1,33.886 524.886,41.1 524.886,50 C524.886,58.899 532.1,66.113 541,66.113 C549.9,66.113 557.115,58.899 557.115,50 C557.115,41.1 549.9,33.886 541,33.886 M565.378,62.101 C565.244,65.022 564.756,66.606 564.346,67.663 C563.803,69.06 563.154,70.057 562.106,71.106 C561.058,72.155 560.06,72.803 558.662,73.347 C557.607,73.757 556.021,74.244 553.102,74.378 C549.944,74.521 548.997,74.552 541,74.552 C533.003,74.552 532.056,74.521 528.898,74.378 C525.979,74.244 524.393,73.757 523.338,73.347 C521.94,72.803 520.942,72.155 519.894,71.106 C518.846,70.057 518.197,69.06 517.654,67.663 C517.244,66.606 516.755,65.022 516.623,62.101 C516.479,58.943 516.448,57.996 516.448,50 C516.448,42.003 516.479,41.056 516.623,37.899 C516.755,34.978 517.244,33.391 517.654,32.338 C518.197,30.938 518.846,29.942 519.894,28.894 C520.942,27.846 521.94,27.196 523.338,26.654 C524.393,26.244 525.979,25.756 528.898,25.623 C532.057,25.479 533.004,25.448 541,25.448 C548.997,25.448 549.943,25.479 553.102,25.623 C556.021,25.756 557.607,26.244 558.662,26.654 C560.06,27.196 561.058,27.846 562.106,28.894 C563.154,29.942 563.803,30.938 564.346,32.338 C564.756,33.391 565.244,34.978 565.378,37.899 C565.522,41.056 565.552,42.003 565.552,50 C565.552,57.996 565.522,58.943 565.378,62.101 M570.82,37.631 C570.674,34.438 570.167,32.258 569.425,30.349 C568.659,28.377 567.633,26.702 565.965,25.035 C564.297,23.368 562.623,22.342 560.652,21.575 C558.743,20.834 556.562,20.326 553.369,20.18 C550.169,20.033 549.148,20 541,20 C532.853,20 531.831,20.033 528.631,20.18 C525.438,20.326 523.257,20.834 521.349,21.575 C519.376,22.342 517.703,23.368 516.035,25.035 C514.368,26.702 513.342,28.377 512.574,30.349 C511.834,32.258 511.326,34.438 511.181,37.631 C511.035,40.831 511,41.851 511,50 C511,58.147 511.035,59.17 511.181,62.369 C511.326,65.562 511.834,67.743 512.574,69.651 C513.342,71.625 514.368,73.296 516.035,74.965 C517.703,76.634 519.376,77.658 521.349,78.425 C523.257,79.167 525.438,79.673 528.631,79.82 C531.831,79.965 532.853,80.001 541,80.001 C549.148,80.001 550.169,79.965 553.369,79.82 C556.562,79.673 558.743,79.167 560.652,78.425 C562.623,77.658 564.297,76.634 565.965,74.965 C567.633,73.296 568.659,71.625 569.425,69.651 C570.167,67.743 570.674,65.562 570.82,62.369 C570.966,59.17 571,58.147 571,50 C571,41.851 570.966,40.831 570.82,37.631"></path></g></g></g></svg></div><div style="padding-top: 8px;"> <div style="color:#3897f0; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:550; line-height:18px;">View this post on Instagram</div></div><div style="padding: 12.5% 0;"></div> <div style="display: flex; flex-direction: row; margin-bottom: 14px; align-items: center;"><div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(0px) translateY(7px);"></div> <div style="background-color: #F4F4F4; height: 12.5px; transform: rotate(-45deg) translateX(3px) translateY(1px); width: 12.5px; flex-grow: 0; margin-right: 14px; margin-left: 2px;"></div> <div style="background-color: #F4F4F4; border-radius: 50%; height: 12.5px; width: 12.5px; transform: translateX(9px) translateY(-18px);"></div></div><div style="margin-left: 8px;"> <div style="background-color: #F4F4F4; border-radius: 50%; flex-grow: 0; height: 20px; width: 20px;"></div> <div style="width: 0; height: 0; border-top: 2px solid transparent; border-left: 6px solid #f4f4f4; border-bottom: 2px solid transparent; transform: translateX(16px) translateY(-4px) rotate(30deg)"></div></div><div style="margin-left: auto;"> <div style="width: 0px; border-top: 8px solid #F4F4F4; border-right: 8px solid transparent; transform: translateY(16px);"></div> <div style="background-color: #F4F4F4; flex-grow: 0; height: 12px; width: 16px; transform: translateY(-4px);"></div> <div style="width: 0; height: 0; border-top: 8px solid #F4F4F4; border-left: 8px solid transparent; transform: translateY(-4px) translateX(8px);"></div></div></div> <div style="display: flex; flex-direction: column; flex-grow: 1; justify-content: center; margin-bottom: 24px;"> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; margin-bottom: 6px; width: 224px;"></div> <div style="background-color: #F4F4F4; border-radius: 4px; flex-grow: 0; height: 14px; width: 144px;"></div></div></a><p style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;"><a href="https://www.instagram.com/p/Cyz2Rxdr0Od/?utm_source=ig_embed&amp;utm_campaign=loading" style="color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none;" target="_blank">A post shared by 𝑅𝒶𝒸𝒽𝑒𝓁 𝒪𝓌▪︎Culinary ▪︎Travel▪︎Parenting▪︎Beauty (@munchwithvienna)</a></p></div></blockquote>
  </div>
</div>

<div style="max-width: 100%;">
  <img src="/images/Cohesion/November%202023/rachel-quote.jpg" class="rounded20" style="width: 100%; margin-top: 30px;">
</div>

<div style="max-width: 100%; text-align: center">
  <img src="/images/Cohesion/November%202023/rachel-tips-title.jpg" class="" style="width: 100%; margin: 50px auto 30px; max-width: 640px;">
</div>

<div style="max-width: 100%;">
  <img src="/images/Cohesion/November%202023/rachel-tips-card.jpg" class="rounded20" style="width: 100%; margin: 0px;">
</div>


<div style="max-width: 100%; display: inline-block;">
  <div style="max-width: 100%;">
    <img src="/images/Cohesion/November%202023/eco-journey-title%201.jpg" class="" style="width: 100%; margin-top: 30px;">
  </div>

<!--1-->  
<div class="col-" style="max-width: 100%; display: flex;">
  
  <div class="col- col-6" style="float: left; background: #D7F6E7;">
    <div class="w-100" style="padding: 25px 15px; text-align: center; margin: auto;">
      <img src="/images/Cohesion/November%202023/reduce@nw.png" class="" style="width: 100%; max-width: 180px;">
    </div>
  </div>

  <div class="col- col-6" style="float: left; background: #CEF4E2;">
    <div class="w-100" style="padding: 25px 15px; text-align: center; margin: auto;">
      <img src="/images/Cohesion/November%202023/green%20homes.png" class="" style="width: 100%; max-width: 200px;">
    </div>
  </div>

</div>
<!--1--> 

  <div style="width: 100%; background: #157577; display: inline-block;">
    <p style="font-size: 20px; font-weight: bold; text-align: center; color: #FFFFFF; margin: 0px 0px; padding: 15px 15px;">
      <b>What you need to do</b>
    </p>
  </div>

<!--2-->  
<div class="col-" style="max-width: 100%; display: flex;">
  
  <div class="col- col-6" style="float: left; background: #D7F6E7;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px; text-align: center;">
        <img src="/images/Cohesion/November%202023/icon1%20pic.png" style="width:  100%; max-width: 80px;">
      </div>
      <div>
        <p style="font-size: 18px; line-height: initial; color: #000000; text-align: center; padding: 10px 20px;">Save energy and water, and reduce food wastage at home.</p>
      </div>
    </div>
  </div>

  <div class="col- col-6" style="float: left; background: #CEF4E2;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px; text-align: center;">
        <img src="/images/Cohesion/November%202023/icon2%20pic.png" style="width:  100%; max-width: 80px;">
      </div>
      <div>
        <p style="font-size: 18px; line-height: initial; color: #000000; text-align: center; padding: 10px 20px;">Adopt eco-friendly habits at home and use energy-efficient appliances.</p>
      </div>
    </div>
  </div>

</div>
<!--2--> 

  <div style="width: 100%; background: #157577; display: inline-block;">
    <p style="font-size: 20px; font-weight: bold; text-align: center; color: #FFFFFF; margin: 0px 0px; padding: 15px 15px;">
      <b>How to qualify</b>
    </p>
  </div>


<!--3-->  
<div class="col-" style="max-width: 100%; display: flex;">
  
  <div class="col- col-6" style="float: left; background: #D7F6E7;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px; text-align: center;">
        <img src="/images/Cohesion/November%202023/icon3%20pic%20.png" style="width:  100%; max-width: 80px;">
      </div>
      <div>
        <p style="font-size: 18px; line-height: initial; color: #000000; text-align: center; padding: 10px 20px;">
          Sign up and pledge to reduce water or electricity usage by at least 5% over a period of 4 months<br><br>
          Follow these <a href="https://drive.google.com/file/d/1_rvIMpTqrGkgZq3GJALoZhol3qX_D8t1/view" target="_new" style="font-weight: bold; color: #0C6C37; text-decoration: underline;">tips</a> to achieve your goal.<br><br>
          <small>*After 4 months, <a href="https://form.gov.sg/641db5aab69f640012b014ff" target="_new" style="font-weight: bold; color: #0C6C37; text-decoration: underline;">submit your utility bills</a> for verification.</small>
        </p>
      </div>
    </div>
  </div>

  <div class="col- col-6" style="float: left; background: #CEF4E2;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px; text-align: center;">
        <img src="/images/Cohesion/November%202023/icon4%20pic.png" style="width:  100%; max-width: 80px;">
      </div>
      <div>
        <p style="font-size: 18px; line-height: initial; color: #000000; text-align: center; padding: 10px 20px;">
          Use energy-efficient appliances with energy ratings of 3-ticks and above, LED lightbulbs or water-efficient shower fittings.<br><br>
          Apply through this <a href="https://go.gov.sg/greenhomesnw" target="_new" style="font-weight: bold; color: #0C6C37; text-decoration: underline;">link</a> with the necessary documents.<br><br>
          <small>*A home visit may be arranged to ensure you have met the criteria.</small>
        </p>
      </div>
    </div>
  </div>

</div>
<!--3-->   

  <div style="width: 100%; background: #157577; display: inline-block;">
    <p style="font-size: 20px; font-weight: bold; text-align: center; color: #FFFFFF; margin: 0px 0px; padding: 15px 15px;">
      <b>What you stand to receive</b>
    </p>
  </div>


<!--3-->  
<div class="col-" style="max-width: 100%; display: flex;">
  
  <div class="col- col-6" style="float: left; background: #D7F6E7;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px; text-align: center;">
        <img src="/images/Cohesion/November%202023/icon5%20pic.png" style="width:  100%; max-width: 80px;">
      </div>
      <div>
        <p style="font-size: 18px; line-height: initial; color: #000000; text-align: center; padding: 10px 20px;">
          $50 in e-vouchers<br><br>
          <small>Check out more details <a href="https://go.gov.sg/nw-reduce" target="_new" style="font-weight: bold; color: #0C6C37; text-decoration: underline;">here</a></small>
        </p>
      </div>
    </div>
  </div>

  <div class="col- col-6" style="float: left; background: #CEF4E2;">
    <div class="w-100" style="padding: 15px 15px;">
      <div class="w-100" style="min-height: 60px; text-align: center;">
        <img src="/images/Cohesion/November%202023/icon5%20pic.png" style="width:  100%; max-width: 80px;">
      </div>
      <div>
        <p style="font-size: 18px; line-height: initial; color: #000000; text-align: center; padding: 10px 20px;">
          Qualify for Gold, Platinum or Silver
Awards and win grocery vouchers
ranging from $100 to $500.<br><br>

<small>Check out more details <a href="https://go.gov.sg/nw-greenhomes" target="_new" style="font-weight: bold; color: #0C6C37; text-decoration: underline;">here</a></small>
        </p>
      </div>
    </div>
  </div>

</div>
<!--3--> 

  <div style="width: 100%; background: #CEF4E2; display: inline-block; min-height: 15px; -webkit-border-bottom-right-radius: 25px;
-webkit-border-bottom-left-radius: 25px;
-moz-border-radius-bottomright: 25px;
-moz-border-radius-bottomleft: 25px;
border-bottom-right-radius: 25px;
border-bottom-left-radius: 25px;">
    <div class="col- col-6 rounded20" style="float: left; background: #D7F6E7;">
        <div class="w-100" style="padding: 15px 15px;">
        </div>
    </div>
    <div class="col- col-6 rounded20" style="float: left; background: #CEF4E2;">
        <div class="w-100" style="padding: 15px 15px;">
        </div>
    </div>
  </div>


</div>


<div style="width: 100%; background: #157577; display: inline-block; margin: 30px 0px 0px; -webkit-border-top-left-radius: 20px;
-webkit-border-top-right-radius: 20px;
-moz-border-radius-topleft: 20px;
-moz-border-radius-topright: 20px;
border-top-left-radius: 20px;
border-top-right-radius: 20px;">
    <p style="font-size: 20px; font-weight: bold; text-align: left; color: #FFFFFF; margin: 0px 0px; padding: 15px 40px;">
      <b>There’s more eco-action happening in our neighbourhood!</b>
    </p>
</div>
<div style="padding: 0px 0px; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">
<div class="" style="width: 100%; background: #DCEAE3; padding: 0px 0px 0px; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">
  <div style="padding: 30px 40px; -webkit-border-bottom-right-radius: 20px;
-webkit-border-bottom-left-radius: 20px;
-moz-border-radius-bottomright: 20px;
-moz-border-radius-bottomleft: 20px;
border-bottom-right-radius: 20px;
border-bottom-left-radius: 20px;">

    <div style="padding: 0px 0px 30px; margin: auto; text-align: center;">
      <iframe src="https://www.facebook.com/plugins/video.php?height=476&amp;href=https%3A%2F%2Fwww.facebook.com%2Fnwcdc%2Fvideos%2F682849173795923%2F&amp;show_text=false&amp;width=476&amp;t=0" width="476" height="476" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"></iframe>
    </div>

    <div style="padding: 0px 0px;">
      <p style="font-size: 18px; font-weight: bold; text-align: left; color: #000000; margin: 0px 0px;"><strong>North West Sustainability Festival 2023<br>
Causeway Point, Main Atrium Level 1, 31 October - 5 November 2023, 11am - 9pm</strong>
      </p> 

        <p style="font-size: 16px; text-align: left; line-height: 24px; color: #000; margin: 10px 0px;">Join us at the inaugural North West Sustainability Festival 2023 where we’ll celebrate and promote sustainable living in our community. Explore the exciting line-up of activities where you’ll discover 
eco-friendly practices and ways to embrace green living at home. 
<br><br>
Check out the programme line-up <a href="https://www.go.gov.sg/nwsf2023" target="_new" style="font-weight: bold; color: #0C6C37; text-decoration: underline;">here</a>.
        </p>
  </div>
</div>
</div>
</div>


<!--Footer-->
<div class="col-" style="padding: 20px 0px 0px; display: flex;">&nbsp;</div>

<!--Latest Stores Card-->
<div style="width: 100%; background: #FB5C1F; border-radius: 30px; padding: 0px 0px; display: flex;">
  <div style="width: 100%; padding: 30px 10px 8px; text-align: center; margin: auto;">
    <h1 style="font-family:  Arial; font-size: xx-large; font-weight: bold; color: #FFFFFF; letter-spacing: normal !important;"><em>Keep updated with our latest stories!</em></h1>
    <a href="https://go.gov.sg/subscribe-cohesion" target="_new" style="text-decoration: none;">
      <div style="font-family:  Arial; font-size: large; font-weight: bold; background: #FFFFFF; color: #FB5C1F; padding: 10px 15px; max-width: 320px; margin: auto; -webkit-border-radius: 50rem; -moz-border-radius: 50rem; border-radius: 50rem; text-decoration: none;"><em>Subscribe to Cohesion Magazine</em>
      </div>
    </a>

    <div style="width: 100%;">
    <div style="width: 100%; padding: 15px 10px; text-align: center;   display: flex; justify-content: center; align-items: center;">
      <span style="font-family: Arial; font-weight: bold; font-size: large; color: #FFFFFF;">Follow us on</span>
      <a style="line-height: normal !important; margin-bottom: 0px !important;" href="https://www.facebook.com/nwcdc/" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-facebook.png" style="padding: 5px 7px;"></a>
      <a style="line-height: normal !important; margin-bottom: 0px !important;" href="https://www.instagram.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-instagram.png" style="padding: 5px 7px;"></a>
      <a style="line-height: normal !important; margin-bottom: 0px !important;" href="https://t.me/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/telegram.png" style="padding: 5px 7px;"></a>
      <a style="line-height: normal !important; margin-bottom: 0px !important;" href="https://www.youtube.com/northwestcdc" target="_new"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/square-youtube.png" style="padding: 5px 7px;"></a>
    </div>
    </div>

    <div style="width: 100%; text-align: right;"><img src="https://northwest.cdc.gov.sg/images/Cohesion/May%202023/nw-arrow.png" style="width: 25px; display: inline-block !important;"></div>
  </div>
</div>
<!--Latest Stores Card-->

<div style="padding: 40px 20px; text-align: center;">
  <h2 style="font-size: xx-large; font-weight: bold;"><em>Our Team</em></h2>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Adviser: Mayor Alex Yam</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Editorial Team: Garick Kea, Sim Chuan San, Steve Luo, Eric Liu, Melvin Tai, Charlene Koh</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Please send feedback, suggestions and comments to <a href="mailto:northwest_cdc@pa.gov.sg" target="_new" style="color: #000000; text-decoration: underline;">northwest_cdc@pa.gov.sg</a></p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Some articles in Cohesion are contributed by volunteers and are not necessarily opinions/comments by North&nbsp;West&nbsp;CDC.</p>
  <p style="font-size: 14px; line-height: 24px; margin-top: 0px;">Reproduction in whole or in part is prohibited without prior permission from North West CDC.</p>
</div>
<!--Footer End-->

<script async="" src="https://www.instagram.com/embed.js"></script>

</article>



