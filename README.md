<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ighosotu Farm Ltd | Fresh Spices & Quality Snacks</title>
  <style>
    :root {
      --primary: #2e7d32;
      --secondary: #e65100;
      --bg-light: #f9f9f9;
      --text-dark: #222;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    body { color: var(--text-dark); line-height: 1.6; background-color: var(--bg-light); }
    
    header { background: #fff; padding: 1rem 5%; display: flex; justify-content: space-between; align-items: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); sticky; top: 0; z-index: 100; }
    .logo { font-size: 1.5rem; font-weight: bold; color: var(--primary); }
    
    .hero { background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('hero-bg.jpg') center/cover; color: #fff; text-align: center; padding: 4rem 1rem; }
    .hero h1 { font-size: 2.5rem; margin-bottom: 0.5rem; }
    .hero p { font-size: 1.2rem; margin-bottom: 1.5rem; }
    
    .btn { display: inline-block; background: var(--secondary); color: #fff; padding: 0.75rem 1.5rem; text-decoration: none; border-radius: 5px; font-weight: bold; }
    .btn-whatsapp { background: #25D366; }
    
    .container { width: 90%; max-width: 1100px; margin: 2rem auto; }
    .section-title { text-align: center; margin-bottom: 2rem; color: var(--primary); }
    
    .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 1.5rem; }
    .product-card { background: #fff; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.08); text-align: center; padding: 1rem; }
    .product-card img { width: 100%; height: 180px; object-fit: cover; border-radius: 5px; }
    .product-card h3 { margin: 0.8rem 0 0.4rem; color: var(--primary); }
    
    footer { background: #111; color: #fff; text-align: center; padding: 1.5rem 1rem; margin-top: 3rem; }
  </style>
</head>
<body>

  <header>
    <div class="logo">IGHOSOTU FARM LTD</div>
    <a href="https://wa.me/2340000000000" class="btn btn-whatsapp">Order on WhatsApp</a>
  </header>

  <section class="hero">
    <h1>Farm-Fresh Spices & Delicious Snacks</h1>
    <p>Authentic Banga Spices, Pepper Soup Spices, Plantain Chips, Chin Chin & Pure Honey</p>
    <a href="#products" class="btn">Explore Our Products</a>
  </section>

  <main class="container" id="products">
    <h2 class="section-title">Our Featured Products</h2>
    <div class="product-grid">
      
      <div class="product-card">
        <img src="banga-spice.jpg" alt="Banga Spice">
        <h3>Banga Spice Blend</h3>
        <p>Rich, natural herbs & spices for traditional soup.</p>
      </div>

      <div class="product-card">
        <img src="peppersoup-spice.jpg" alt="Pepper Soup Spice">
        <h3>Pepper Soup Spice</h3>
        <p>Aromatic and hot blend for perfect pepper soup.</p>
      </div>

      <div class="product-card">
        <img src="plantain-chips.jpg" alt="Plantain Chips">
        <h3>Plantain Chips</h3>
        <p>Crunchy, fresh, and wholesome snacks.</p>
      </div>

      <div class="product-card">
        <img src="pure-honey.jpg" alt="Pure Honey">
        <h3>Pure Natural Honey</h3>
        <p>100% unrefined, organic farm-fresh honey.</p>
      </div>

    </div>
  </main>

  <footer>
    <p>&copy; Ighosotu Farm Ltd — Ukuidjere, Delta State</p>
  </footer>

</body>
</html>
# Ighosotu-Farm-ltd-
Official website of Ighosotu Farm ltd 
