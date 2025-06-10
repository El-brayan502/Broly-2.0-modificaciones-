<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Brayam | Mi Página</title>
  <style>
    body {
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      min-height: 100vh;
    }

    .profile-pic {
      margin-top: 40px;
      border-radius: 50%;
      width: 120px;
      height: 120px;
      object-fit: cover;
      border: 4px solid white;
    }

    h1 {
      margin: 20px 0 10px;
      font-size: 26px;
    }

    p {
      margin: 0 20px 20px;
      color: #ccc;
    }

    .button-container {
      display: flex;
      flex-direction: column;
      width: 90%;
      max-width: 400px;
      gap: 15px;
    }

    .button {
      background-color: #1DB954;
      padding: 14px 20px;
      border: none;
      border-radius: 10px;
      font-size: 16px;
      text-decoration: none;
      color: white;
      transition: background 0.3s;
    }

    .button:hover {
      background-color: #1ed760;
    }

    footer {
      margin-top: auto;
      padding: 20px;
      font-size: 12px;
      color: #999;
    }
  </style>
</head>
<body>

  <img src="https://avatars.githubusercontent.com/u/0000000?v=4" alt="Brayam" class="profile-pic" />
  <h1>FANTOM UWU</h1>
  <p>Bienvenido a mi bio. Aquí encuentras mis enlaces, proyectos y más.</p>

  <div class="button-container">
    <a href="https://wa.me/50200000000" class="button">📞 Contáctame por WhatsApp</a>
    <a href="https://github.com/El-brayan502" class="button">👨‍💻 Mi GitHub</a>
    <a href="https://t.me/fantomuwu" class="button">📢 Canal de Telegram</a>
    <a href="https://www.youtube.com/@fantomuwu" class="button">📺 YouTube</a>
  </div>

  <footer>
    Hecho con 💖 por Brayam
  </footer>

</body>
</html>