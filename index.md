<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Mayna Crisley – Gallery</title>

  <script src="jquery-3.6.0.min.js"></script>
  <link href="fotorama.css" rel="stylesheet">
  <script src="fotorama.js"></script>

  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      overflow: hidden;
      background: #111;
      color: white;
      font-family: sans-serif;
    }

    .fotorama {
      height: 100vh;
    }

    h1 {
      position: absolute;
      top: 10px;
      width: 100%;
      text-align: center;
      z-index: 10;
      margin: 0;
      pointer-events: none;
    }
  </style>
</head>
<body>

<h1>Mayna Crisley – Gallery</h1>

<div class="fotorama"
     data-width="100%"
     data-height="100%"
     data-autoplay="3000"
     data-loop="true"
     data-transition="crossfade"
     data-nav="thumbs"
     data-fit="contain"
     data-allowfullscreen="true">

  <img src="mayna-mini.png" data-caption="Mayna Crisley">

  <img src="chevelle-mini.jpg" data-caption="Chevelle">
  <img src="figures-mini.jpg" data-caption="Figures">
  <img src="fish-mini.jpg" data-caption="Fish">
  <img src="indian-mini.jpg" data-caption="Indian">
  <img src="kayak-mini.jpg" data-caption="Kayak">
  <img src="lake-mini.jpg" data-caption="Lake">
  <img src="leafs-mini.jpg" data-caption="Leafs">
  <img src="raptors-mini.jpg" data-caption="Raptors">
  <img src="toronto-mini.jpg" data-caption="Toronto">
  <img src="toronto2-mini.jpg" data-caption="Toronto">
  <img src="village-mini.jpg" data-caption="Village">
  <img src="aurora-mini.jpg" data-caption="Aurora">
  <img src="lafer-mini.jpg" data-caption="Lafer">
  <img src="tucan-mini.jpg" data-caption="Tucan">
  <img src="the-last-supper-mini.jpg" data-caption="The Last Supper">
  <img src="dog-mini.jpg" data-caption="Dog">

</div>

</body>
</html>
