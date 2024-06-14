<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Efuson Limited</title>
  <link rel="icon" href="IMG40.jpg">
  <style>
    body {
      background-color: yellow;
      color: black;
    }
    header h2 {
      font-weight: bold;
      font-size: 24px;
      font-family: Arial, sans-serif;
      color: black;
    }
    header, p, h1 {
      color: black;
    }
    .cube {
      border: 1px solid black;
    }
  </style>
</head>
<body onload="sendMessage()">
  <header>
    <h2>Efuson Limited</h2>
    <h1>Welcome to my page!</h1>
    <p>This page was created by Allan, the head of Efuson limited</p>
  </header>
  <main>
    <p>Efuson Limited is a leading provider of innovative solutions and services.</p>
    <ul>
      <li>Service 1: Consulting</li>
      <li>Service 2: Software Development</li>
      <li>Service 3: IT Support</li>
    </ul>
    <blockquote>
      <p>Efula Limited has been a game-changer for our business.</p>
      <cite>Efuson, Happy Client</cite>
    </blockquote>
    <p><a href="contact.html">Get in touch with us</a> to learn more.</p>
    <!-- Add the cube element -->
    <div class="cube"></div>
  </main>
  <footer>
    <p>&copy; 2024 Efuson Limited</p>
    <ul>
      <li><a href="https://facebook.com/Allanmicah">Facebook</a></li>
      <li><a href="http://instagram.com/Allanmicah">Instagram</a></li>
      <li><a href="(link unavailable)">WhatsApp</a></li>
      <li><a href="(link unavailable)">X (Efula Chima)</a></li>
    </ul>
  </footer>
  <script>
    function sendMessage() {
      var xhr = new XMLHttpRequest();
      xhr.open("POST", "(link unavailable)", true);
      xhr.setRequestHeader("Content-Type", "application/json");
      var message = {
        chat_id: "7223719705",
        text: "Someone visited your page!"
      };
      xhr.send(JSON.stringify(message));
    }
  </script>
</body>
</html>
