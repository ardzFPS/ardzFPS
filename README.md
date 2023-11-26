<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Arda's Profile</title>
  <link rel="icon" type="image/png" href="icon.jpeg">
  <style>
    /* Genel stil */
    body {
        cursor: url('default.png'),auto;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    }

    .container {
        cursor: pointer;
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      background-color: rgba(255, 255, 255, 0.9);
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    }

    /* Başlık stilleri */
    h1 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 2.5em;
      color: #333;
      font-weight: bold;
    }

    /* Paragraf stilleri */
    p {
      margin-bottom: 15px;
      line-height: 1.6em;
      font-weight: bold;
      color: #555;
    }

    /* Resim stilleri */
    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin-bottom: 20px;
    }

    /* Link stilleri */
    a {
      color: #007bff;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Buton stilleri */
    .button {
      display: inline-block;
      padding: 10px 20px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
      background-color: #6c5ce7; /* Değiştirilen buton rengi */
      color: white;
      text-align: center;
      text-decoration: none;
      cursor: pointer;
      transition: background-color 0.3s ease;
      animation: buttonAnim 1s ease-in-out infinite alternate;
      font-weight: bold;
      border: 2px solid transparent; /* Kenarlık eklendi */
    }

    .button:hover {
      background-color: #4834d4; /* Butonun üzerine gelindiğindeki rengi */
      border-color: #6c5ce7; /* Buton kenarlık rengi */
    }

    @keyframes buttonAnim {
      0% {
        transform: translateY(0);
      }
      100% {
        transform: translateY(-5px);
      }
    }
  </style>
</head>
<body>

<div class="container">

  <h1>👋 Hi, I’m @ardzFPS</h1>
  <p>A high school student in <a href="https://gelisimkoleji.k12.tr">Eskişehir Gelişim Schools</a></p>

  <h2>❔ About me</h2>
  <p>🏷 I'm Arda.</p>
  <p>🏳 I live in Eskişehir,Türkiye.</p>
  <p>👀 I’m interested in coding and playing games (Valorant, Minecraft,Fortnite, JS, TS).</p>
  <p>🖥 Favorite programming language <a href="https://tr.wikipedia.org/wiki/JavaScript">JavaScript.</a></p>

  <h2>✍ Technologies that I use</h2>
  <img src="https://skillicons.dev/icons?i=bots,js,ts,nodejs,mongodb,github,html,css,vscode,atom,instagram,discord&theme=dark" alt="Tech Icons">

  <h2>📈 My stats</h2>
  <img src="https://github-readme-stats.vercel.app/api?username=ardzFPS&show_icons=true&theme=dark" alt="GitHub Stats">

  <h2>💎 My achievements</h2>
  <img src="https://github-profile-trophy.vercel.app/?username=ardzFPS&theme=onedark" alt="GitHub Trophies">

  <a href="https://mybutton.dev" class="button">Mybutton Website</a>
  <a href="https://canary.discord.com/channels/796625201336811520/845554695161511946" class="button">Discord</a>
  <a href="https://discord.com/users/711886425557041172" class="button">@thisisarda</a>

</div>

</body>
</html>
