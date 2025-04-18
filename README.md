<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mahmmoud | Social Links</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: Arial, sans-serif;
      color: white;
      text-align: center;
      background: url('background.jpg') no-repeat center center fixed;
      background-size: cover;
    }
    .overlay {
      background: rgba(0, 0, 0, 0.6);
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 1;
    }
    .content {
      position: relative;
      z-index: 2;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 0.5em;
    }
    .links {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      max-width: 800px;
      margin-top: 20px;
    }
    .links .column {
      flex: 1;
      min-width: 200px;
      padding: 10px;
    }
    .links a, .links p {
      display: block;
      margin: 10px auto;
      color: white;
      text-decoration: none;
      font-size: 1.3em;
      transition: 0.3s;
    }
    .links a:hover {
      color: #ff0000;
    }
    .play-button {
      margin-top: 40px;
    }
    button {
      padding: 12px 24px;
      font-size: 1.2em;
      cursor: pointer;
      background-color: #ff0000;
      color: white;
      border: none;
      border-radius: 8px;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #cc0000;
    }
    iframe {
      display: none;
    }
  </style>
</head>
<body>
  <div class="overlay"></div>
  <div class="content">
    <h1>Follow Mahmmoud</h1>
    <div class="links">
      <div class="column">
        <a href="https://x.com/m7mod_18" target="_blank">Twitter / X</a>
        <a href="https://open.spotify.com/user/mahmmuod" target="_blank">Spotify</a>
        <a href="https://www.instagram.com/mahmmuodalsgher" target="_blank">Instagram</a>
      </div>
      <div class="column">
        <a href="https://www.tiktok.com/@silence.1l" target="_blank">TikTok</a>
        <p>PSN: m7mod_355</p>
        <p>Discord: ittzm7mod</p>
      </div>
    </div>
    <div class="play-button">
      <button onclick="playMusic()">تشغيل الأغنية</button>
    </div>
  </div>  <!-- Hidden YouTube player -->  <iframe id="ytplayer" width="0" height="0" 
    src="" frameborder="0" allow="autoplay"></iframe>
  <script>
    function playMusic() {
      const player = document.getElementById("ytplayer");
      player.src = "https://www.youtube.com/embed/Ld2a5KewaGU?autoplay=1&loop=1&playlist=Ld2a5KewaGU";
    }
  </script>
</body>
</html>
