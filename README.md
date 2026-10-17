<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Katzeblume</title>
  <link rel="icon" href="logo.png">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Anton&family=Space+Grotesk:wght@400;700&family=Space+Mono&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <a href="index.html"><img src="images/katzeblume-logo.jpg" alt="Katzeblume logo"></a>
    <nav>
      <a href="index.html" class="active" data-i18n="nav.home">Home</a>
      <a href="books.html" data-i18n="nav.books">Books</a>
      <a href="wear.html" data-i18n="nav.wear">Wear</a>
      <a href="prints.html" data-i18n="nav.prints">Prints</a>
      <a href="artists.html" data-i18n="nav.artists">Artists</a>
      <a href="about.html" data-i18n="nav.about">About</a>
      <button id="lang-btn" class="lang-btn">FR</button>
    </nav>
  </header>

  <div class="marquee">
    <div class="marquee-track">
      <span>KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ </span>
      <span>KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ KATZEBLUME ✿ MONTRÉAL ✿ POÉSIE ✿ ART ✿ </span>
    </div>
  </div>

  <main>
  <section class="hero">
    <div class="brand">
  <img class="hero-logo" src="images/katzeblume-logo.jpg" alt="Katzeblume logo">
  <h1>Katzeblume</h1>
</div>
    <p data-i18n="home.tagline">Poetry, art, clothes and Montreal artists.</p>
    
  </section>

  <section>
    <h2 data-i18n="home.featured">Featured book</h2>
    <article class="product">
      <img src="images/effulgentcover.png" alt="Cover of Effulgent">
      <div>
        <h2>Effulgent</h2>
        <p data-i18n="books.meta">by Emil Beaudet · poetry · EPUB</p>
        <p data-i18n="home.blurb">I write about the things I can't say out loud. Book in english only.</p>
        <p class="price">6.55 CAD</p>
        <a class="btn" href="PASTE-YOUR-LULU-LINK-HERE" data-i18n="books.buy">Buy on Lulu</a>
      </div>
    </article>
  </section>

  <section>
    <h2 data-i18n="home.chapters">Chapters</h2>
    <div class="chapters">
      <a class="chapter c1" href="books.html">
        <span class="num">01</span>
        <h3 data-i18n="nav.books">Books</h3>
        <p data-i18n="ch.books">Poetry, publicized by Katzeblume.</p>
      </a>
      <a class="chapter c2" href="wear.html">
        <span class="num">02</span>
        <h3 data-i18n="nav.wear">Wear</h3>
        <p data-i18n="ch.wear">Clothes made because the store didn't have them.</p>
      </a>
      <a class="chapter c3" href="prints.html">
        <span class="num">03</span>
        <h3 data-i18n="nav.prints">Prints</h3>
        <p data-i18n="ch.prints">Art for your walls.</p>
      </a>
      <a class="chapter c4" href="artists.html">
        <span class="num">04</span>
        <h3 data-i18n="nav.artists">Artists</h3>
        <p data-i18n="ch.artists">A place for Montreal artists to create together.</p>
      </a>
    </div>
  </section>
<section class="insta">
  <h2 data-i18n="home.insta.title">See our creations on Instagram!</h2>
  <div class="insta-grid">
    <a href="https://instagram.com/katzeblume.mtl" target="_blank" rel="noopener">
      <img src="images/shirt.jpg" alt="Katzeblume on Instagram">
    </a>
    <a href="https://instagram.com/katzeblume.mtl" target="_blank" rel="noopener">
      <img src="images/print-1.jpg" alt="Katzeblume on Instagram">
    </a>
    <a href="https://instagram.com/katzeblume.mtl" target="_blank" rel="noopener">
      <img src="effulgent.jpg" alt="Katzeblume on Instagram">
    </a>
  </div>
  <a class="btn" href="https://instagram.com/katzeblume.mtl" target="_blank" rel="noopener" data-i18n="home.insta.cta">Follow @katzeblume</a>
</section>
  <section class="join">
    <h2 data-i18n="home.join.title">Make something with us</h2>
    <p data-i18n="home.join.text">Katzeblume is growing, and it's looking for Montreal poets, writers and artists who believe in it.</p>
    <a class="btn" href="artists.html" data-i18n="home.join.cta">Join the project</a>
  </section>
</main>

  <footer>© Katzeblume · <span data-i18n="footer.city">Montréal</span></footer>

  <script src="script.js"></script>
</body>
</html>
