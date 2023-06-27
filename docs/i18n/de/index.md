<div style="text-align: center;">
  <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
</div>

<head>
  <title>Unsere Projekte</title>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>
</head>

<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🙌 Mongorunway ist eine Organisation, die darauf abzielt, MongoDB-Tools zu entwickeln, 
  die der Gemeinschaft zugutekommen.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Im Einklang mit der Philosophie der Organisation sollten alle Projekte eine saubere 
  Architektur haben. Durch die Einhaltung der Prinzipien der sauberen Architektur und die 
  Anwendung eines bestimmten Systemdesign-Ansatzes wird der Aufbau von Tools vereinfacht, 
  die Kohäsion erhöht und technische Schulden reduziert.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Die Entwicklung eines Tools mit einem spezifischen Systemdesign-Ansatz ermöglicht 
  auch die Erstellung einer benutzerfreundlichen API. Dabei werden ein monolithischer 
  Satz von Dateien im Stammverzeichnis des Projekts oder chaotisch benannte Ordner mit 
  unklaren Zuständigkeiten vermieden.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🤝 Wenn Sie unsere Vision des Aufbaus von MongoDB-Tools teilen, würden wir uns freuen, 
  Ihren Beitrag zu unseren Projekten auf GitHub zu erhalten!
</p>

<br>

<body>
  <div style="text-align: center;">
    <h1 style="font-size: 28px; font-weight: bold; margin-bottom: 20px;">Unsere Projekte ✨</h1>
  </div>
  <div class="projects">
    <div>
        <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Mongorunway</strong> ist eine Organisation, deren Ziel es ist, MongoDB-Tools zu 
            entwickeln, die der Gemeinschaft nutzen.
            <br>
            <a href="https://github.com/Mongorunway">Webseite besuchen.</a>
            </span>
          </figcaption>
    </div>
    <div>
        <img src="assets/migration-tool-banner.jpg" alt="Migration tool" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            Das <strong>Mongorunway-Migrationswerkzeug</strong> dient der bequemen und einfachen 
            Migration von MongoDB-Datenbanken.
            <br>
            <a href="https://github.com/Mongorunway/mongorunway">Webseite besuchen.</a>
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
