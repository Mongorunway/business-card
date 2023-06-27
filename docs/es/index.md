<div style="text-align: center;">
  <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
</div>

<head>
  <title>Nuestros Proyectos</title>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>
</head>

<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🙌 Mongorunway es una organización cuyo objetivo es construir herramientas para MongoDB 
  que beneficien a la comunidad.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ En línea con la filosofía de la organización, todos los proyectos deben adherirse a una 
  arquitectura limpia. Siguiendo los principios de una arquitectura limpia y adoptando un enfoque 
  específico de diseño de sistema, la construcción de herramientas se vuelve más sencilla, reduce 
  la cohesión y la deuda técnica.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Desarrollar una herramienta con un enfoque específico de diseño de sistema también permite 
  crear una API fácil de usar, evitando un conjunto monolítico de archivos en el directorio raíz 
  del proyecto o carpetas con nombres caóticos y responsabilidades poco claras.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🤝 Si compartes nuestra visión de construir herramientas para MongoDB, ¡estaremos encantados 
  de contar con tu contribución en nuestros proyectos en GitHub!
</p>

<br>

<body>
  <div style="text-align: center;">
    <h1 style="font-size: 28px; font-weight: bold; margin-bottom: 20px;">Nuestros Proyectos ✨</h1>
  </div>
  <div class="projects">
    <div>
        <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Mongorunway</strong> es una organización cuyo objetivo es crear herramientas 
            para MongoDB que beneficien a la comunidad.
            <br>
            <a href="https://github.com/Mongorunway">Visita la página web.</a>
            </span>
          </figcaption>
    </div>
    <div>
        <img src="assets/migration-tool-banner.jpg" alt="Migration tool" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            La <strong>Herramienta de migración de Mongorunway</strong> está diseñada para facilitar 
            y simplificar la migración de bases de datos de MongoDB.
            <br>
            <a href="https://github.com/Mongorunway/mongorunway">Visita la página web.</a>
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
