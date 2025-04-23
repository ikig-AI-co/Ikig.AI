![ logo png](https://github.com/user-attachments/assets/0e9ef06e-761f-4438-8bcb-699c3dc3f5c6)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Ikig.AI</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
    }

    img.logo {
      width: 200px;
      opacity: 0;
      animation: fadeInZoom 2s ease-out forwards;
    }

    @keyframes fadeInZoom {
      0% {
        opacity: 0;
        transform: scale(0.8);
      }
      100% {
        opacity: 1;
        transform: scale(1);
      }
    }
  </style>
</head>
<body>
  <img src="logo.png" alt="Logo Ikig.AI" class="logo">
</body>
</html>
