<div style="text-align: center;">
  <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
</div>

<head>
  <title>Nos Projets</title>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>
</head>

<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🙌 Mongorunway est une organisation dont le but est de construire des outils MongoDB 
  qui bénéficient à la communauté.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ En accord avec la philosophie de l'organisation, tous les projets doivent 
  respecter une architecture propre. En suivant les principes de l'architecture propre 
  et en adoptant une approche spécifique de conception système, 
  la construction d'outils devient plus simple, réduit la cohésion et la dette technique.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Le développement d'un outil avec une approche spécifique de conception système permet 
  également de créer une API conviviale, en contournant un ensemble monolithique de fichiers 
  dans le répertoire racine du projet ou des dossiers au nom chaotique avec des responsabilités 
  peu claires.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🤝 Si vous partagez notre vision de construction d'outils MongoDB, nous serions ravis 
  de recevoir votre contribution à nos projets sur GitHub !
</p>

<br>

<body>
  <div style="text-align: center;">
    <h1 style="font-size: 28px; font-weight: bold; margin-bottom: 20px;">Nos Projets ✨</h1>
  </div>
  <div class="projects">
    <div>
        <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Mongorunway</strong> est une organisation dont le but est de créer des outils 
            pour MongoDB qui bénéficient à la communauté.
            <br>
            <a href="https://github.com/Mongorunway">Visitez la page web.</a>
            </span>
          </figcaption>
    </div>
    <div>
        <img src="assets/migration-tool-banner.jpg" alt="Migration tool" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>L'outil de migration Mongorunway</strong> est conçu pour une migration pratique 
            et simple des bases de données MongoDB.
            <br>
            <a href="https://github.com/Mongorunway/mongorunway">Visitez la page web.</a>
            </span>
          </figcaption>
    </div>
  </div>
    <style>
      .caption-text {
        font-style: normal;
      }
    </style>
  <script type="text/javascript" src="//code.jquery.com/jquery-1.11.0.min.js"></script>
  <script type="text/javascript" src="//code.jquery.com/jquery-migrate-1.2.1.min.js"></script>
  <script type="text/javascript" src="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>

  <script type="text/javascript">
    $(document).ready(function(){
      $('.projects').slick({
          dots: false,
          infinite: true,
          speed: 600,
          autoplay: true,
          autoplaySpeed: 2000,
          slidesToShow: 1,
          adaptiveHeight: true,
      });
    });
  </script>
</body>
