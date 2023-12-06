---
title: Testing
permalink: /testing/
variant: markdown
description: testing various elements to put on website
---
<div class="wrapper">
  <div class="cards_wrap">
    <div class="card_item">
      <div class="card_inner">
        <div class="card_top">
          <img alt="car" src="https://i.imgur.com/qhE9KtV.jpg">
        </div>
        <div class="card_bottom">
          <div class="card_category">
            Travel
          </div>
          <div class="card_info">
            <p class="title">10 Best Things about Travel</p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, ab.
            </p>
          </div>
          <div class="card_creator">
            By Alex Kato
          </div>
        </div>
      </div>
    </div>
    <div class="card_item">
      <div class="card_inner">
        <div class="card_top">
          <img alt="car" src="https://i.imgur.com/qhE9KtV.jpg">
        </div>
        <div class="card_bottom">
          <div class="card_category">
            Travel
          </div>
          <div class="card_info">
            <p class="title">10 Best Things about Travel</p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, ab.
            </p>
          </div>
          <div class="card_creator">
            By Alex Kato
          </div>
        </div>
      </div>
    </div>
    <div class="card_item">
      <div class="card_inner">
        <div class="card_top">
          <img alt="car" src="https://i.imgur.com/qhE9KtV.jpg">
        </div>
        <div class="card_bottom">
          <div class="card_category">
            Travel
          </div>
          <div class="card_info">
            <p class="title">10 Best Things about Travel</p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, ab.
            </p>
          </div>
          <div class="card_creator">
            By Alex Kato
          </div>
        </div>
      </div>
    </div>
    <div class="card_item">
      <div class="card_inner">
        <div class="card_top">
          <img alt="car" src="https://i.imgur.com/qhE9KtV.jpg">
        </div>
        <div class="card_bottom">
          <div class="card_category">
            Travel
          </div>
          <div class="card_info">
            <p class="title">10 Best Things about Travel</p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, ab.
            </p>
          </div>
          <div class="card_creator">
            By Alex Kato
          </div>
        </div>
      </div>
    </div>
    <div class="card_item">
      <div class="card_inner">
        <div class="card_top">
          <img alt="car" src="https://i.imgur.com/qhE9KtV.jpg">
        </div>
        <div class="card_bottom">
          <div class="card_category">
            Travel
          </div>
          <div class="card_info">
            <p class="title">10 Best Things about Travel</p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, ab.
            </p>
          </div>
          <div class="card_creator">
            By Alex Kato
          </div>
        </div>
      </div>
    </div>
    <div class="card_item">
      <div class="card_inner">
        <div class="card_top">
          <img alt="car" src="https://i.imgur.com/qhE9KtV.jpg">
        </div>
        <div class="card_bottom">
          <div class="card_category">
            Travel
          </div>
          <div class="card_info">
            <p class="title">10 Best Things about Travel</p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, ab.
            </p>
          </div>
          <div class="card_creator">
            By Alex Kato
          </div>
        </div>
      </div>
    </div>
    <div class="card_item">
      <div class="card_inner">
        <div class="card_top">
          <img alt="car" src="https://i.imgur.com/qhE9KtV.jpg">
        </div>
        <div class="card_bottom">
          <div class="card_category">
            Travel
          </div>
          <div class="card_info">
            <p class="title">10 Best Things about Travel</p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, ab.
            </p>
          </div>
          <div class="card_creator">
            By Alex Kato
          </div>
        </div>
      </div>
    </div>
    <div class="card_item">
      <div class="card_inner">
        <div class="card_top">
          <img alt="car" src="https://i.imgur.com/qhE9KtV.jpg">
        </div>
        <div class="card_bottom">
          <div class="card_category">
            Travel
          </div>
          <div class="card_info">
            <p class="title">10 Best Things about Travel</p>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad, ab.
            </p>
          </div>
          <div class="card_creator">
            By Alex Kato
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
@import url("https://fonts.googleapis.com/css?family=Nunito&amp;display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Nunito", sans-serif;
}

body {
  background: #eedfcc;
  color: #555555;
  font-size: 14px;
}

img {
  display: block;
  width: 100%;
  height: 100%;
}

.wrapper {
  width: 100%;
  margin: 20px auto;
}

.cards_wrap {
  display: flex;
  flex-wrap: wrap;
}

.cards_wrap .card_item {
  width: 25%;
  padding: 10px;
}

.cards_wrap .card_inner {
  background: #fff;
}

.cards_wrap .card_top {
  width: 100%;
  min-height: 225px;
  padding: 10px;
  padding-bottom: 0;
}

.cards_wrap .card_bottom {
  padding: 15px;
}

.cards_wrap .card_bottom .card_category {
  text-transform: uppercase;
  text-align: center;
}

.cards_wrap .card_bottom .card_info {
  padding: 15px;
  margin: 10px 0;
  border: 1px dashed #0071bc;
}

.cards_wrap .card_bottom .card_info .title {
  color: #0071bc;
  font-size: 18px;
  margin-bottom: 5px;
}

.cards_wrap .card_bottom .card_creator {
  text-align: center;
}

@media (max-width: 1024px) {
  .cards_wrap .card_item {
    width: 33.3%;
  }
}

@media (max-width: 768px) {
  .cards_wrap .card_item {
    width: 50%;
  }
}

@media (max-width: 528px) {
  .cards_wrap .card_top {
    height: auto;
  }
  .cards_wrap .card_item {
    width: 100%;
  }
}
