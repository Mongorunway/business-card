<div style="text-align: center;">
  <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
</div>

<head>
  <title>Our projects</title>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css"/>
  <link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css"/>
</head>

<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🙌 Mongorunway is an organization aimed at building MongoDB tools 
  that benefit the community.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ In line with the organization's philosophy, all projects should 
  adhere to clean architecture. By following the principles of clean 
  architecture and adopting a specific system design approach, 
  building  tools becomes simpler, reduces cohesion and technical debt.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  ✨ Developing a tool with a specific system design approach also allows 
  for creating a user-friendly API, bypassing a monolithic set of files in 
  the root directory of the project or chaotically named folders with unclear 
  responsibilities.
</p>
<p style="font-size: 18px; line-height: 1.5; margin-bottom: 20px;">
  🤝 If you share our vision of building MongoDB tools, we would be delighted 
  to have your contribution to our projects on GitHub!
</p>


<br>

<body>
  <div style="text-align: center;">
    <h1 style="font-size: 28px; font-weight: bold; margin-bottom: 20px;">Our Projects ✨</h1>
  </div>
  <div class="projects">
    <div>
        <img src="assets/mongorunway-banner.jpg" alt="Mongorunway" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Mongorunway</strong> is an organization aimed at building MongoDB tools that 
            benefit the community.
            <br>
            <a href="https://github.com/Mongorunway">Visit webpage.</a>
            </span>
          </figcaption>
    </div>
    <div>
        <img src="assets/migration-tool-banner.jpg" alt="Migration tool" id="interactive-image">
          <figcaption>
            <span class="caption-text">
            <strong>Mongorunway migration tool</strong> is a tool designed for easy and convenient 
            migration of MongoDB databases. 
            <br>
            <a href="https://github.com/Mongorunway/mongorunway">Visit webpage.</a>
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
