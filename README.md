# Essaie-
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SIC BTP - Société d'Ingénierie et Construction</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: #1a1a1a;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 32px;
    }

    nav {
      background: #ff6600;
      text-align: center;
      padding: 10px 0;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      background: #ffffff;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      margin-top: 30px;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeIn 1s ease-out forwards;
    }

    .section h2 {
      color: #ff6600;
    }

    img.banniere {
      width: 100%;
      max-height: 400px;
      object-fit: cover;
      border-radius: 8px;
    }

    ul li {
      margin-bottom: 10px;
    }

    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form button {
      background-color: #ff6600;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }

    footer {
      background: #1a1a1a;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>SIC BTP</h1>
    <p>Société d'Ingénierie et Construction</p>
  </header>

  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#services">Services</a>
    <a href="#apropos">À propos</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="section" id="accueil">
    <img src="banniere.jpg" alt="Bannière SIC BTP" class="banniere">
    <h2>Bienvenue chez SIC BTP</h2>
    <p>Nous sommes une entreprise spécialisée dans le génie civil, la construction de bâtiments et les travaux publics.</p>
  </div>

  <div class="section" id="services">
    <h2>Nos Services</h2>
    <ul>
      <li>🏗️ Construction de routes et ponts</li>
      <li>🏢 Bâtiments publics et privés</li>
      <li>🔧 Rénovation d’infrastructures</li>
      <li>📐 Études techniques et ingénierie</li>
    </ul>
  </div>

  <div class="section" id="apropos">
    <h2>À propos de nous</h2>
    <p>SIC BTP est une société béninoise dynamique avec une expertise solide dans le domaine du BTP. Nous mettons la qualité, la sécurité et le respect des délais au cœur de nos réalisations.</p>
  </div>

  <div class="section" id="contact">
    <h2>Contactez-nous</h2>
    <p>Email : contact@sicbtp.com</p>
    <p>Téléphone : +229 90 00 00 00</p>
    <p>Adresse : Abomey-Calavi, Bénin</p>

    <form>
      <label for="nom">Nom :</label>
      <input type="text" id="nom" name="nom" required>

      <label for="email">Email :</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Message :</label>
      <textarea id="message" name="message" rows="4" required></textarea>

      <button type="submit">Envoyer</button>
    </form>
  </div>

  <footer>
    <p>&copy; 2025 SIC BTP - Tous droits réservés</p>
  </footer>

</body>
</html>
