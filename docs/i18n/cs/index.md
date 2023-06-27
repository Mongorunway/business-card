<div style="text-align: center;">
  <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
</div>

<head>
  <title>Naše Projekty</title>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>
</head>

<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🙌 Mongorunway je organizace zaměřená na vývoj nástrojů pro MongoDB, 
  které přinášejí prospěch komunitě.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ V souladu s filosofií organizace by se všechny projekty měly řídit čistou architekturou. 
  Dodržováním principů čisté architektury a přijetím specifického přístupu k návrhu systému se 
  zjednodušuje vývoj nástrojů, snižuje se koheze a technický dluh.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Vývoj nástroje s konkrétním systémovým návrhem také umožňuje vytvořit uživatelsky přívětivé 
  API, obejít monolitickou sadu souborů v kořenovém adresáři projektu nebo chaoticky pojmenované 
  složky s nejasnými odpovědnostmi.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🤝 Pokud sdílíte naše vidění vývoje nástrojů pro MongoDB, budeme nadšeni za váš příspěvek k 
  našim projektům na GitHub!
</p>


<br>

<body>
  <div style="text-align: center;">
    <h1 style="font-size: 28px; font-weight: bold; margin-bottom: 20px;">Naše Projekty ✨</h1>
  </div>
  <div class="projects">
    <div>
        <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Mongorunway</strong> - organizace, jejímž cílem je vytvářet nástroje pro MongoDB, 
            které prospívají komunitě.
            <br>
            <a href="https://github.com/Mongorunway">Navštivte webovou stránku.</a>
            </span>
          </figcaption>
    </div>
    <div>
        <img src="assets/migration-tool-banner.jpg" alt="Migration tool" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Nástroj pro migraci Mongorunway</strong> je určen pro pohodlnou a jednoduchou 
            migraci databází MongoDB.
            <br>
            <a href="https://github.com/Mongorunway/mongorunway">Navštivte webovou stránku.</a>
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
