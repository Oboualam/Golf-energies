<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Golf Energies</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@600;700&display=swap" rel="stylesheet">
<style>
    /* Basic resets */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Montserrat', sans-serif;
      background: url('file:///C:/Users/oboualam/Downloads/background.png') no-repeat center center fixed;
      background-size: cover;
      color: #ffffff;
    }
    .container {
      text-align: center;
      position: relative;
      width: 100%;
      height: 100vh;
      background: rgba(0, 0, 0, 0.5);
    }
    .logo {
      position: absolute;
      top: 5px;
      left: 40px;
      width: 100px;
    }
    .logo img {
      width: 100%;
    }
    .navbar {
      display: flex;
      justify-content: center;
      align-items: center;
      gap: 40px;
      font-size: 20px;
      padding: 20px 0;
      position: relative;
      top: 10px;
      border-bottom: 1px solid #ffffff;
      font-weight: 600;
    }
    .navbar a {
      color: #ffffff;
      text-decoration: none;
      padding: 10px 20px;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .navbar a.contact-btn {
      color: #ffffff;
      background-color: #006400;
    }
    .navbar a.contact-btn:hover {
      background: #004c00;
    }
    .content {
      position: absolute;
      top: 60%;
      left: 50%;
      transform: translate(-50%, -50%);
      text-align: center;
    }
    .content h1 {
      font-size: 36px;
      color: #ffffff;
      font-weight: 600;
      margin-bottom: 20px;
      position: relative;
      display: inline-block;
    }
    .content h1:before, .content h1:after {
      content: "";
      width: 100px;
      height: 2px;
      background: #ffffff;
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
    }
    .content h1:before {
      left: -120px;
    }
    .content h1:after {
      right: -120px;
    }
    .content p {
      font-size: 48px;
      margin: 20px 0;
      line-height: 1.2;
      font-weight: 700;
    }
    .content p .highlight-green {
      color: #008000;
      font-weight: 700;
    }
    .content p .highlight-orange {
      color: #FFA500;
      font-weight: 700;
    }
    .content .cta-buttons {
      margin-top: 40px;
      display: flex;
      justify-content: center;
      gap: 20px;
    }
    .cta-buttons a {
      display: inline-block;
      padding: 15px 30px;
      color: #ffffff;
      border: 2px solid #ffffff;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
      font-weight: 600;
    }
    .cta-buttons .contact-btn {
      background-color: #006400;
      border: none;
    }
    .cta-buttons a:hover {
      background: rgba(255, 255, 255, 0.2);
    }
    .section {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 50px 100px;
      background-color: #ffffff;
      color: #333333;
      font-weight: 600;
      margin-top: 30px;
    }
    .section img {
      width: 45%;
      border-radius: 10px;
    }
    .section .text {
      width: 50%;
    }
    .section h2 {
      font-size: 28px;
      color: #FFA500;
      margin-bottom: 10px;
      font-weight: 600;
    }
    .section h3 {
      font-size: 24px;
      color: #333333;
      margin-bottom: 20px;
      font-weight: 700;
    }
    .section p {
      font-size: 18px;
      line-height: 1.6;
      margin-bottom: 20px;
    }
    .section a {
      display: inline-block;
      padding: 10px 20px;
      background-color: #006400;
      color: #ffffff;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .section a:hover {
      background-color: #004c00;
    }
    /* New page section styling for Événement */
    .event-page {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 100px;
      background-color: #ffffff;
      color: #333333;
      font-weight: 600;
    }
    .event-page img {
      width: 40%;
      border-radius: 10px;
    }
    .event-page .text {
      width: 50%;
    }
    .event-page h2 {
      font-size: 28px;
      color: #FFA500;
      margin-bottom: 10px;
      font-weight: 600;
    }
    .event-page h3 {
      font-size: 24px;
      color: #333333;
      margin-bottom: 20px;
      font-weight: 700;
    }
    .event-page p {
      font-size: 18px;
      line-height: 1.6;
      margin-bottom: 20px;
    }
    .event-page a {
      display: inline-block;
      padding: 10px 20px;
      background-color: #006400;
      color: #ffffff;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .event-page a:hover {
      background-color: #004c00;
    }
    .last-section {
      background: url('file:///C:/Users/oboualam/Downloads/grass.png') no-repeat center center fixed;
      background-size: cover;
      padding: 100px 50px;
      color: #ffffff;
      text-align: center;
    }
    .last-section h2 {
      font-size: 28px;
      font-weight: 700;
      margin-bottom: 20px;
    }
    .last-section p {
      font-size: 18px;
      margin-bottom: 40px;
    }
    .last-section a {
      display: inline-block;
      padding: 15px 30px;
      background-color: #006400;
      color: #ffffff;
      text-decoration: none;
      border-radius: 5px;
      font-weight: 600;
      margin: 10px;
    }
    .last-section a:hover {
      background-color: #004c00;
    }
    .footer {
      font-size: 14px;
      margin-top: 50px;
    }
    .footer a {
    color: #ffffff;
    text-decoration: none;
    margin: 0 10px;
    font-weight: normal; /* Supprime le style de bouton */
    background: none; /* Supprime le fond vert */
    padding: 0; /* Supprime le padding pour que ce soit un simple lien */
}

</style>
</head>
<body>
<div class="container">
<!-- Logo -->
<div class="logo">
<img src="file:///C:/Users/oboualam/Downloads/logo.png" alt="Golf Energies Logo">
</div>
<!-- Navbar -->
<div class="navbar">
<a href="index.html">Accueil</a>
<a href="evenement.html">Événement</a>
<a href="#">Programme</a>
<a href="#">Inscription</a>
<a href="#" class="contact-btn">Contact</a>
</div>
<!-- Content -->
<div class="content">
<h1>GOLF ENERGIES</h1>
<p>UN <span class="highlight-green">TEE</span> POUR L’INNOVATION UN FAIRWAY POUR LA <span class="highlight-orange">DURABILITÉ</span></p>
<div class="cta-buttons">
<a href="#" class="contact-btn">Contactez-nous</a>
<a href="#">Inscrivez-vous</a>
</div>
</div>
</div>

<!-- New Section -->
<div class="section">
  <img src="file:///C:/Users/oboualam/Downloads/golf.jpg" alt="Golf Image">
  <div class="text">
    <h2>Golf Énergies</h2>
    <h3>PARCOURS DE QUALITÉ, OBJECTIFS DURABLES</h3>
    <p>Golf Énergies est plus qu’un simple tournoi de golf, c’est une opportunité unique de rencontrer les décideurs du secteur des énergies renouvelables, d’échanger des idées, et de créer des synergies pour un avenir plus vert.</p>
    <p>Lors de cette première édition, vous aurez l’opportunité de jouer sur l’un des plus beaux terrains de golf de France, tout en renforçant vos relations professionnelles dans une atmosphère conviviale.</p>
    <a href="#">Découvrez le programme complet</a>
  </div>
</div>
<div class="spacer"></div>
<style> 
    .section, .event-page, .last-section {
        padding: 2; 
        margin: 0;  
    }
    
</style>


<div class="section">
  <div class="text">
    <h2>Programme de la journée</h2>
    <h3>14h00 - 18h00 : Tournoi de golf</h3>
    <p>Profitez d’un tournoi amical sur le superbe parcours du <strong>Golf Marivaux</strong>, adapté aux joueurs de tous niveaux.</p>
    <h3>19h00 : Dîner</h3>
    <p>Après une après-midi de compétition, retrouvez-vous autour d’un dîner convivial pour approfondir vos échanges dans une ambiance détendue.</p>
    <p><span>Date :</span> Jeudi 22 mai 2025<br>
    <span>Adresse :</span> Golf Marivaux, Route du Golf, 91640 Janvry</p>
    <div class="cta-buttons">
    <a href="#" class="contact-btn">Voir l’emplacement sur Google Maps</a>
    <a href="#">Inscrivez-vous dès maintenant</a>
</div>
  </div>
  <img src="file:///C:/Users/oboualam/Downloads/mariveau.jpg" alt="Golf Image">
</div>

<!-- Last Section -->
<div class="last-section">
  <h2>
<p style="font-size: 30px; font-style: italic;">REJOIGNEZ-NOUS SUR LE GREEN – INSCRIVEZ-VOUS MAINTENANT</p> </h2>


<p style="font-size: 24px;">Ne manquez pas l’occasion de participer à cet événement exclusif. Les places sont limitées, alors assurez-vous de réserver la vôtre dès maintenant.</p>

<a href="#">Je m’inscris maintenant !</a>
<div class="spacer" style="height: 50px;"> </div>


<h2> 
<p style="font-size: 30px; font-style: italic;">VOUS AVEZ DES QUESTIONS ? NOUS SOMMES LÀ POUR VOUS !</p> </h2>

<p style="font-size: 24px;">Pour toute question ou demande d’information supplémentaire, n’hésitez pas à nous contacter via le formulaire ci-dessous. Notre équipe se fera un plaisir de vous répondre rapidement.</p>

<a href="#">Contactez-nous dès maintenant</a>
 

 <div class="footer">
  <p>© 2024 Golf-Energies. All rights reserved.</p>
  <a href="#">Privacy Policy</a>
  <a href="#">Terms of Service</a>
  <a href="#">Anti-corruption Policy</a>
</div>

  <div style="clear: both;"></div>
</div>


</div>
</body>
</html>
