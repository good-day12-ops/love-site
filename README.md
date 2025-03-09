# love-site
<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Для тебе, красуне!</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: linear-gradient(45deg, #ff9a9e, #fad0c4);
      font-family: Arial, sans-serif;
      text-align: center;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 0.5em;
      color: #fff;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    }
    p {
      font-size: 1.2em;
      color: #fff;
      margin-bottom: 1em;
    }
    .heart {
      font-size: 2em;
      animation: pulse 1.5s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <h1>Привіт, красуне!</h1>
  <p>Це маленький сайт для тебе. Ти особлива!</p>
  <div class="heart">❤️</div>
</body>
</html>
