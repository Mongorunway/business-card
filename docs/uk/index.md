<div style="text-align: center;">
  <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
</div>

<head>
  <title>Наші Проєкти</title>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>
</head>

<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🙌 Mongorunway - це організація, спрямована на розробку інструментів для MongoDB, 
  які приносять користь спільноті.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Згідно з філософією організації, всі проєкти повинні дотримуватися принципів чистої 
  архітектури. Слідуючи принципам чистої архітектури та приймаючи певний підхід до системного 
  проєктування, розробка інструментів стає простішою, зменшується зв'язність та технічний борг.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Розробка інструменту з певним підходом до системного проєктування також дозволяє створювати 
  зрозумілий користувачеві API, обходячи монолітний набір файлів у кореневому каталозі проєкту або 
  хаотично названі теки без чітких обов'язків.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🤝 Якщо ви поділяєте наше бачення розробки інструментів для MongoDB, будемо раді вашому внеску 
  до наших проєктів на GitHub!
</p>


<br>

<body>
  <div style="text-align: center;">
    <h1 style="font-size: 28px; font-weight: bold; margin-bottom: 20px;">Наші Проєкти ✨</h1>
  </div>
  <div class="projects">
    <div>
        <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Mongorunway</strong> - це організація, метою якої є створення інструментів для 
            MongoDB, що приносять користь спільноті.
            <br>
            <a href="https://github.com/Mongorunway">Відвідати сторінку.</a>
            </span>
          </figcaption>
    </div>
    <div>
        <img src="assets/migration-tool-banner.jpg" alt="Migration tool" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Інструмент міграції Mongorunway</strong> призначений для зручної та простої 
            міграції баз даних MongoDB.
            <br>
            <a href="https://github.com/Mongorunway/mongorunway">Відвідати сторінку.</a>
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
