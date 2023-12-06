---
title: Testing
permalink: /testing/
variant: markdown
description: testing various elements to put on website
---
<style>
  .articles {
    /* Add any styles for the articles section here */
  }

  .article-wrapper {
    position: relative;
    border-radius: 16px;
    box-shadow: none;
    background: #fff;
    overflow: hidden;
    transition: all 0.4s ease-in-out;
  }

  article h2 {
    margin: 0 0 18px 0;
    font-family: "Bebas Neue", cursive;
    font-size: 1.9rem;
    letter-spacing: 0.06em;
    color: var(--title-color);
    transition: color 0.3s ease-out;
  }

  figure {
    margin: 0;
    padding: 0;
    aspect-ratio: 16 / 9;
    overflow: hidden;
  }

  article img {
    max-width: 100%;
    transform-origin: center;
    transform: scale(var(--img-scale));
    transition: transform 0.4s ease-in-out;
  }

  .article-body {
    padding: 24px;
  }

  article a {
    display: inline-flex;
    align-items: center;
    text-decoration: none;
    color: #28666e;
  }

  /* Add any additional styles for the article elements here */
</style>

<section class="articles">
  <article>
    <div class="article-wrapper">
      <figure>
       <img alt="Insights vol 5 cover" src="/images/Insights/2021%20insight.png">
      </figure>
      <div class="article-body">
        <h2>Insights Vol 5</h2>
        <p></p>
        <a class="Download here" href="#">Donwload here <span class="sr-only">about this article</span></a>
      </div>
    </div>
  </article>
</section>

