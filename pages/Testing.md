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
  border-radius: 8px;
  box-shadow: none;
  background: #919d8d;
  overflow: hidden;
  transition: all 0.4s ease-in-out;
}

article h2 {
  margin: 5 5 5px 5;
  font-family: "Bebas Neue", cursive;
  font-size: 1.0rem;
  letter-spacing: 0.06em;
  color: var(--title-color);
  transition: color 0.3s ease-out;
}

figure {
  margin: 0;
  padding: 0;
  aspect-ratio: 1 / 1;
  overflow: hidden;
}

article img {
  max-width: 70%;
	margin: 10px auto;
	display:block;
  transform-origin: center;
  transform: scale(var(--img-scale));
  transition: transform 0.4s ease-in-out;
  border-radius: 10px; /* Apply rounded corners to the image */
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
        <a class="Download here" href="https://drive.google.com/drive/folders/14JRcJkOuaTu0218Zhvzw6QxZOLrQY9do">Download here <span class="sr-only">about this article</span></a>
      </div>
    </div>
  </article>
</section>