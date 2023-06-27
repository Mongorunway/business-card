<div style="text-align: center;">
  <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
</div>

<head>
  <title>Наши Проекты</title>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>
</head>

<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🙌 Mongorunway - это организация, направленная на разработку инструментов для MongoDB, которые 
  приносят пользу сообществу.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Согласно философии организации, все проекты должны придерживаться принципов чистой 
  архитектуры. Следуя принципам чистой архитектуры и принимая определенный подход к системному 
  проектированию, создание инструментов становится проще, уменьшается связность и технический долг.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Разработка инструмента с определенным подходом к системному проектированию также позволяет 
  создавать понятный пользователю API, минуя монолитный набор файлов в корневом каталоге проекта 
  или хаотично названные папки без четких обязанностей.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🤝 Если вы разделяете наше видение построения инструментов для MongoDB, будем рады Вашему  
  вкладу в наши проекты на GitHub!
</p>
<br>

<body>
  <div style="text-align: center;">
    <h1 style="font-size: 28px; font-weight: bold; margin-bottom: 20px;">Наши Проекты ✨</h1>
  </div>
  <div class="projects">
    <div>
        <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Mongorunway</strong> - это организация, цель которой заключается в создании  
            инструментов для MongoDB, которые приносят пользу сообществу.
            <br>
            <a href="https://github.com/Mongorunway">Посетить страницу.</a>
            </span>
          </figcaption>
    </div>
    <div>
        <img src="assets/migration-tool-banner.jpg" alt="Migration tool" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Инструмент миграции Mongorunway</strong> предназначен для удобной и простой 
            миграции баз данных MongoDB.
            <br>
            <a href="https://github.com/Mongorunway/mongorunway">Посетить страницу.</a>
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
