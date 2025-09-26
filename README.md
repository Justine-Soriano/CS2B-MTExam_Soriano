<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ilocos Sur - Tourist Spots & Products</title>
  <link rel="stylesheet" href="css/style.css" />
</head>
<body>
  <!-- Header / Navbar -->
  <header class="site-header">
    <div class="container header-inner">
      <div class="brand">
        <img src="assets/logo-placeholder.png" alt="Ilocos Sur Logo" class="logo" />
        <span class="site-title">Ilocos Sur</span>
      </div>
      <nav class="nav">
        <a href="index.html" class="nav-link">Home [Ilocos Sur]</a>
        <a href="contact.html" class="nav-link">Contact Us</a>
      </nav>
      <button class="mobile-menu-toggle" aria-label="Open menu">☰</button>
    </div>
  </header>

  <!-- Hero -->
  <section class="hero">
    <div class="container hero-inner">
      <h1>Discover Ilocos Sur</h1>
      <p>Explore historic sites, coastal adventures, and local crafts. Hand-picked tourist spots and authentic local products—designed for your midterm WebDev project.</p>
      <a class="btn" href="#tourist-spots">Explore Spots</a>
    </div>
  </section>

  <!-- Section 1: Tourist Spots -->
  <main class="container main-content">
    <section id="tourist-spots" class="section section-spots">
      <h2>Top Tourist Spots & Adventures</h2>

      <article class="spot-card">
        <div class="spot-media">
          <img src="https://via.placeholder.com/640x360?text=Vigan+Heritage+Village" alt="Vigan Heritage Village"/>
        </div>
        <div class="spot-body">
          <h3>Vigan Heritage Village</h3>
          <p>Vigan is a beautifully preserved Spanish colonial town renowned for its cobblestone streets and ancestral houses. Walking through the Calle Crisologo transports visitors back in time — you can ride in a calesa or browse local pottery shops. The town offers museums, heritage tours, and traditional cuisine that reflect centuries of cultural layering.</p>
          <p class="hashtags">#Vigan #HeritageTown #CalleCrisologo #Culture #History</p>
        </div>
      </article>

      <article class="spot-card">
        <div class="spot-media">
          <img src="https://via.placeholder.com/640x360?text=Bantay+Bell+Tower" alt="Bantay Bell Tower"/>
        </div>
        <div class="spot-body">
          <h3>Bantay Bell Tower & Viewpoint</h3>
          <p>The Bantay Bell Tower stands on a hill offering panoramic views of the town and coastline. Historically the bell tower was used for watch and warning during colonial times and now functions as a scenic landmark. Visitors climb its steps, enjoy the vista, and take photos—especially at sunrise and sunset.</p>
          <p class="hashtags">#BantayBellTower #Panorama #SunsetViews #Heritage #PhotoSpot</p>
        </div>
      </article>

      <article class="spot-card">
        <div class="spot-media">
          <img src="https://via.placeholder.com/640x360?text=Bangui+Windmills" alt="Bangui Windmills"/>
        </div>
        <div class="spot-body">
          <h3>Bangui Windmills & Coastal Drive</h3>
          <p>Bangui Bay is famous for its row of wind turbines set against the sea — an iconic mix of renewable energy and coastal scenery. The long stretch of coastline makes for a relaxing drive and many stops to take photos and learn about local fishing communities. The area also supports eco-tourism and offers seaside eateries serving fresh seafood.</p>
          <p class="hashtags">#BanguiWindmills #CoastalDrive #EcoTourism #Seaside #Photography</p>
        </div>
      </article>
    </section>

    <!-- Section 2: Local Products -->
    <section id="local-products" class="section section-products">
      <h2>Local Products Marketplace</h2>
      <p class="muted">A showcase of 12 local products. Use the Add / Remove buttons to simulate a simple cart (for your JavaScript requirement).</p>

      <div class="products-grid">
        <!-- Product Card Template — repeat with different content -->
        <div class="product-card" data-product-id="p1">
          <img src="https://via.placeholder.com/300x200?text=Inabel+Weave" alt="Inabel Weave">
          <h4>Inabel Handwoven Cloth</h4>
          <p class="product-details">Handwoven textile by local artisans. 100% cotton, traditional patterns.</p>
          <div class="product-meta">
            <span class="price">₱850</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p2">
          <img src="https://via.placeholder.com/300x200?text=Vigan+Longganisa" alt="Vigan Longganisa">
          <h4>Vigan Longganisa (Pack)</h4>
          <p class="product-details">Signature garlicky sausage local to Vigan. Packed for freshness.</p>
          <div class="product-meta">
            <span class="price">₱220</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p3">
          <img src="https://via.placeholder.com/300x200?text=Bangui+Souvenir" alt="Bangui Souvenir">
          <h4>Bangui Windmill Souvenir</h4>
          <p class="product-details">Miniature windmill model — perfect as a keepsake or gift.</p>
          <div class="product-meta">
            <span class="price">₱150</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p4">
          <img src="https://via.placeholder.com/300x200?text=Salabat+Tea" alt="Salabat Tea">
          <h4>Salabat (Ginger Tea)</h4>
          <p class="product-details">Locally made dried ginger tea — soothing and aromatic.</p>
          <div class="product-meta">
            <span class="price">₱95</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p5">
          <img src="https://via.placeholder.com/300x200?text=Handmade+Pottery" alt="Handmade Pottery">
          <h4>Handmade Pottery</h4>
          <p class="product-details">Ceramic bowls and pots crafted by local artisans.</p>
          <div class="product-meta">
            <span class="price">₱420</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p6">
          <img src="https://via.placeholder.com/300x200?text=Ilocos+Chili+Sauce" alt="Chili Sauce">
          <h4>Ilocos Chili Sauce</h4>
          <p class="product-details">Spicy local chili sauce—popular with native dishes.</p>
          <div class="product-meta">
            <span class="price">₱130</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p7">
          <img src="https://via.placeholder.com/300x200?text=Local+Honey" alt="Local Honey">
          <h4>Wildflower Honey</h4>
          <p class="product-details">Pure local honey sourced from nearby farms.</p>
          <div class="product-meta">
            <span class="price">₱260</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p8">
          <img src="https://via.placeholder.com/300x200?text=Garlic+Bulbs" alt="Garlic Bulbs">
          <h4>Ilocos Garlic (1kg)</h4>
          <p class="product-details">Aromatic garlic grown in Ilocos—packaged by the kilo.</p>
          <div class="product-meta">
            <span class="price">₱180</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p9">
          <img src="https://via.placeholder.com/300x200?text=Handmade+Basket" alt="Handmade Basket">
          <h4>Woven Basket</h4>
          <p class="product-details">Traditional woven basket — durable and decorative.</p>
          <div class="product-meta">
            <span class="price">₱300</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p10">
          <img src="https://via.placeholder.com/300x200?text=Surf+Map" alt="Surf Map">
          <h4>Ilocos Surf Map</h4>
          <p class="product-details">Map and guide for local surf points and lovers of the sea.</p>
          <div class="product-meta">
            <span class="price">₱120</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p11">
          <img src="https://via.placeholder.com/300x200?text=Local+Jam" alt="Local Jam">
          <h4>Mango & Coconut Jam</h4>
          <p class="product-details">Sweet and tropical jam made from local fruit.</p>
          <div class="product-meta">
            <span class="price">₱150</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>

        <div class="product-card" data-product-id="p12">
          <img src="https://via.placeholder.com/300x200?text=Handmade+Jewelry" alt="Handmade Jewelry">
          <h4>Beaded Jewelry</h4>
          <p class="product-details">Handmade necklaces and bracelets using native beads.</p>
          <div class="product-meta">
            <span class="price">₱210</span>
            <div class="product-actions">
              <button class="btn small add-to-cart">Add</button>
              <button class="btn small remove-from-cart" disabled>Remove</button>
            </div>
          </div>
        </div>
      </div>

      <div class="cart-summary">
        <strong>Cart:</strong> <span id="cart-count">0</span> items — <span id="cart-total">₱0</span>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="site-footer">
    <div class="container footer-inner">
      <div>
        <h4>Ilocos Sur Tourism</h4>
        <p>Address: Ilocos Sur, Philippines · Email: info@ilocos-sur.example</p>
      </div>
      <div class="footer-links">
        <a href="#">Privacy</a> · <a href="#">Terms</a> · <a href="contact.html">Contact</a>
      </div>
    </div>
  </footer>

  <script src="js/app.js"></script>
</body>
</html>
