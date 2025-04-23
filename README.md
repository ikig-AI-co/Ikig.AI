![Ø - 2](https://github.com/user-attachments/assets/3a27aaf1-8807-4577-b378-55ff5f1dde52)
# Ikig.AI
We all have abilities
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ikig.AI</title>
  <style>
    body {
      margin: 0;
      background-color: #000;
      color: #fff;
      font-family: 'Arial', sans-serif;
      overflow: hidden;
    }

    .container {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      transition: opacity 1s ease;
    }

    .logo {
      width: 150px;
      height: 150px;
      background-image: url('logo.png'); /* Altere para o nome correto da imagem */
      background-size: contain;
      background-repeat: no-repeat;
      background-position: center;
      opacity: 0;
      animation: grow 1.5s forwards;
    }

    .slogan {
      font-size: 24px;
      opacity: 0;
      margin-top: 30px;
      animation: fadeIn 1s forwards;
      animation-delay: 2s;
    }

    @keyframes grow {
      0% {
        transform: scale(0.5);
        opacity: 0;
      }
      100% {
        transform: scale(1.2);
        opacity: 1;
      }
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }

    .main-content {
      display: none;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="container" id="intro">
    <div class="logo"></div>
    <div class="slogan">Todos nós temos habilidades</div>
  </div>

  <div class="main-content" id="main">
    <h1>Bem-vindo ao ikig.AI</h1>
    <p>Sua jornada começa aqui.</p>
  </div>

  <script>
    setTimeout(() => {
      document.getElementById("intro").style.opacity = 0;
    }, 4000);

    setTimeout(() => {
      document.getElementById("intro").style.display = "none";
      document.getElementById("main").style.display = "block";
    }, 5000);
  </script>
</body>
</html>
