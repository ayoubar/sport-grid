les variables css utlisés :

```
  --primary-color: #c72727;
  --secondary-color: #f99500;
  --light-color: #f3f3f3;
  --dark-color: #333;
  --max-width: 1100px;
  --sports-color: #f99500;
  --ent-color: #a66bbe;
  --tech-color: #009cff;
```

Les Fonts utilisés :

```
font-family: 'Staatliches', cursive;
font-family: 'Lato', sans-serif;
```

Strcuture Navbar:

![Alt text](./maquette/navbar.png?raw=true 'Title')

```html
<nav id="main-nav">
  <div class="container">
    <img src="img/logo.png" alt="NewsGrid" class="logo" />
    <div class="social">
      <a href="http://facebook.com" target="_blank"
        ><i class="fab fa-facebook fa-2x"></i
      ></a>
      <a href="http://twitter.com" target="_blank"
        ><i class="fab fa-twitter fa-2x"></i
      ></a>
      <a href="http://instagram.com" target="_blank"
        ><i class="fab fa-instagram fa-2x"></i
      ></a>
      <a href="http://youtube.com" target="_blank"
        ><i class="fab fa-youtube fa-2x"></i
      ></a>
    </div>
    <ul>
      <li><a class="current" href="index.html">Home</a></li>
      <li><a href="about.html">About</a></li>
    </ul>
  </div>
</nav>
```

Structure Header

![Alt text](./maquette/header.png?raw=true 'Title')

```html
<header id="showcase">
  <div class="container">
    <div class="showcase-container">
      <div class="showcase-content">
        <div class="category category-sports">Sports</div>
        <h1>Some Sports Article</h1>
        <p>remplir un contenu ici !</p>
        <a href="article.html" class="btn btn-primary">Read More</a>
      </div>
    </div>
  </div>
</header>
```

## Structure html pour la partie des articles

```html
<!-- Home Articles -->
<section id="home-articles" class="py-2">
  <div class="container">
    <h2>Editor Picks</h2>
    <div class="articles-container">
      <article class="card">
        <img src="img/articles/ent1.jpg" alt="" />
        <div>
          <div class="category category-ent">Entertainment</div>
          <h3>
            <a href="article.html">Lorem ipsum dolor sit amet</a>
          </h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quam
            eius ducimus optio veniam sit nihil beatae ea autem. Doloribus.
          </p>
        </div>
      </article>
      <article class="card bg-dark">
        <div class="category category-sports">Sports</div>
        <h3>
          <a href="article.html">Lorem ipsum dolor sit amet</a>
        </h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quam
          eius ducimus optio veniam sit nihil beatae ea autem. Doloribus.
        </p>
      </article>
      <article class="card">
        <img src="img/articles/tech1.jpg" alt="" />
        <div class="category category-tech">Technology</div>
        <h3>
          <a href="article.html">Lorem ipsum dolor sit amet</a>
        </h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quam
          eius ducimus optio veniam sit nihil beatae ea autem. Doloribus.
        </p>
      </article>
      <article class="card">
        <div class="category category-sports">Sports</div>
        <h3>
          <a href="article.html">Lorem ipsum dolor sit amet</a>
        </h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quam
          eius ducimus optio veniam sit nihil beatae ea autem. Doloribus.
        </p>
        <img src="img/articles/sports1.jpg" alt="" />
      </article>
      <article class="card">
        <img src="img/articles/tech2.jpg" alt="" />
        <div class="category category-tech">Technology</div>
        <h3>
          <a href="article.html">Lorem ipsum dolor sit amet</a>
        </h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quam
          eius ducimus optio veniam sit nihil beatae ea autem. Doloribus.
        </p>
      </article>
      <article class="card bg-primary">
        <div class="category category-sports">Sports</div>
        <h3>
          <a href="article.html">Lorem ipsum dolor sit amet</a>
        </h3>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quam
          eius ducimus optio veniam sit nihil beatae ea autem. Doloribus.
        </p>
      </article>
      <article class="card">
        <div>
          <div class="category category-ent">Entertainment</div>
          <h3>
            <a href="article.html">Lorem ipsum dolor sit amet</a>
          </h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla quam
            eius ducimus optio veniam sit nihil beatae ea autem. Doloribus.
          </p>
        </div>
        <img src="img/articles/ent2.jpg" alt="" />
      </article>
    </div>
  </div>
</section>
```

### Enjoy Your time
