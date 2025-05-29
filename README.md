<!DOCTYPE html>
<html lang="ro">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CatalinGPhotography</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background-color: #f9f9f9; color: #333; }
    header {
      background: url('https://source.unsplash.com/1600x600/?photography,camera') no-repeat center center/cover;
      height: 70vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px #000;
      text-align: center;
    }
    header h1 { font-size: 3em; margin: 0; }
    nav { background: #000; padding: 1em; text-align: center; }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover { color: #ffd700; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    h2 { border-bottom: 2px solid #ccc; padding-bottom: 10px; margin-bottom: 20px; }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.2);
    }
    ul { list-style-type: none; padding: 0; }
    ul li { margin-bottom: 10px; font-size: 1.1em; }
    footer {
      background: #000;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Capturăm momente, nu doar poze<br><small style="font-size: 0.5em;">CatalinGPhotography</small></h1>
  </header>

  <nav>
    <a href="#despre">Despre</a>
    <a href="#portofoliu">Portofoliu</a>
    <a href="#servicii">Servicii</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="despre">
    <h2>Despre mine</h2>
    <p>Bun venit! Sunt Cătălin Ghioca, fotograf pasionat cu sediul în Bösel. Ofer servicii foto pentru toate tipurile de evenimente: familie, portrete, botezuri, nunți, peisaje și ședințe artistice. Prin obiectivul meu, transform momentele în amintiri de neuitat.</p>
  </section>

  <section id="portofoliu">
    <h2>Portofoliu</h2>
    <div class="gallery">
      <img src="https://source.unsplash.com/400x300/?family,photo" alt="Ședință de familie">
      <img src="https://source.unsplash.com/400x300/?baby,photo" alt="Fotografie bebeluși">
      <img src="https://source.unsplash.com/400x300/?wedding,couple" alt="Nuntă">
      <img src="https://source.unsplash.com/400x300/?landscape,nature" alt="Peisaj">
      <img src="https://source.unsplash.com/400x300/?portrait,studio" alt="Portret artistic">
      <img src="https://source.unsplash.com/400x300/?event,party" alt="Eveniment">
    </div>
  </section>

  <section id="servicii">
    <h2>Servicii și Prețuri</h2>
    <ul>
      <li>📷 Ședință foto de familie – 100€</li>
      <li>👶 Fotografie botez – 250€</li>
      <li>💍 Fotografie nuntă – de la 500€</li>
      <li>🧑‍🎓 Portrete individuale – 80€</li>
      <li>🎉 Evenimente private sau corporate – de la 200€</li>
      <li>🖼️ Tablouri printate 10x15 cm în rame din lemn – 5€/buc</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Pentru rezervări sau întrebări, mă poți contacta:</p>
    <p><strong>Email:</strong> catalingphotography@email.com</p>
    <p><strong>Telefon:</strong> +49 123 456 789</p>
    <p><strong>Social Media:</strong> Facebook & Instagram - <em>@CatalinGPhotography</em></p>
  </section>

  <footer>
    &copy; 2025 CatalinGPhotography - Toate drepturile rezervate.
  </footer>
</body>
</html>
