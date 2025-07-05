<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bienvenido a VLOX</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #fff;
      text-align: center;
    }
    header {
      background: #000;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      color: #fff;
      margin: 0 1rem;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1521336575822-6da63fb454b4?auto=format&fit=crop&w=1280&q=80') no-repeat center/cover;
      height: 80vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      background: rgba(0, 0, 0, 0.6);
      padding: 1rem;
    }
    .section {
      padding: 3rem 2rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
      gap: 2rem;
    }
    .product {
      background: #222;
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
    }
    .product img {
      width: 100%;
      border-radius: 4px;
    }
    .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background: crimson;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    footer {
      background: #000;
      padding: 2rem;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h2>VLOX+</h2>
    <nav>
      <a href="#ropa">Ropa</a>
      <a href="#calzado">Calzado</a>
      <a href="#accesorios">Accesorios</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <div class="hero">
    <h1>La nueva era del estilo masculino ha comenzado.</h1>
  </div>

  <section class="section" id="ropa">
    <h2>Ropa</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x250?text=Polo+VLOX" alt="Polo" />
        <h3>Polo VLOX</h3>
        <p>S/ 69.00</p>
        <button class="btn">Comprar</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x250?text=Casaca+VLOX" alt="Casaca" />
        <h3>Casaca Urbana</h3>
        <p>S/ 149.00</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <section class="section" id="calzado">
    <h2>Calzado</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x250?text=Zapatilla+VLOX" alt="Zapatilla" />
        <h3>Zapatilla Negra</h3>
        <p>S/ 199.00</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <section class="section" id="accesorios">
    <h2>Accesorios</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x250?text=Gorra+VLOX" alt="Gorra" />
        <h3>Gorra Snapback</h3>
        <p>S/ 49.00</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <section class="section" id="contacto">
    <h2>Contáctanos</h2>
    <p>Correo: contacto@vlox.com</p>
    <p>Instagram: @vlox.oficial</p>
  </section>

  <footer>
    <p>&copy; 2025 VLOX. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bienvenido a VLOX</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #111;
      color: #fff;
      text-align: center;
    }
    header {
      background: #000;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav a {
      color: #fff;
      margin: 0 1rem;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1521336575822-6da63fb454b4?auto=format&fit=crop&w=1280&q=80') no-repeat center/cover;
      height: 80vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    .hero h1 {
      font-size: 3rem;
      background: rgba(0, 0, 0, 0.6);
      padding: 1rem;
    }
    .section {
      padding: 3rem 2rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
      gap: 2rem;
    }
    .product {
      background: #222;
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
    }
    .product img {
      width: 100%;
      border-radius: 4px;
    }
    .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background: crimson;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    footer {
      background: #000;
      padding: 2rem;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <h2>VLOX+</h2>
    <nav>
      <a href="#ropa">Ropa</a>
      <a href="#calzado">Calzado</a>
      <a href="#accesorios">Accesorios</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <div class="hero">
    <h1>La nueva era del estilo masculino ha comenzado.</h1>
  </div>

  <section class="section" id="ropa">
    <h2>Ropa</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x250?text=Polo+VLOX" alt="Polo" />
        <h3>Polo VLOX</h3>
        <p>S/ 69.00</p>
        <button class="btn">Comprar</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/200x250?text=Casaca+VLOX" alt="Casaca" />
        <h3>Casaca Urbana</h3>
        <p>S/ 149.00</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <section class="section" id="calzado">
    <h2>Calzado</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x250?text=Zapatilla+VLOX" alt="Zapatilla" />
        <h3>Zapatilla Negra</h3>
        <p>S/ 199.00</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <section class="section" id="accesorios">
    <h2>Accesorios</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/200x250?text=Gorra+VLOX" alt="Gorra" />
        <h3>Gorra Snapback</h3>
        <p>S/ 49.00</p>
        <button class="btn">Comprar</button>
      </div>
    </div>
  </section>

  <section class="section" id="contacto">
    <h2>Contáctanos</h2>
    <p>Correo: contacto@vlox.com</p>
    <p>Instagram: @vlox.oficial</p>
  </section>

  <footer>
    <p>&copy; 2025 VLOX. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
