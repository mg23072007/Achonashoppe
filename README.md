<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Meus Links</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      text-align: center;
      padding: 40px;
    }
    .container {
      max-width: 500px;
      margin: auto;
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0,0,0,0.1);
    }
    h1 {
      color: #333;
      margin-bottom: 30px;
    }
    a.link {
      display: flex;
      align-items: center;
      justify-content: flex-start;
      gap: 10px;
      margin: 12px 0;
      padding: 12px 20px;
      background: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      transition: background 0.3s;
    }
    a.link:hover {
      background: #0056b3;
    }
    a.link img {
      height: 24px;
      width: 24px;
      border-radius: 5px;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>🌐 Meus Links Favoritos</h1>

    <a href="https://youtube.com" class="link" target="_blank">
      <img src="https://upload.wikimedia.org/wikipedia/commons/b/b8/YouTube_Logo_2017.svg" alt="YouTube">
      YouTube
    </a>

    <a href="https://shopee.com.br" class="link" target="_blank">
      <img src="https://cdn.iconscout.com/icon/free/png-256/shopee-282184.png" alt="Shopee">
      Shopee
    </a>

    <a href="https://example.com" class="link" target="_blank">
      <img src="https://cdn-icons-png.flaticon.com/512/25/25694.png" alt="Site">
      Meu Site Pessoal
    </a>

    <!-- Você pode duplicar o bloco acima para adicionar mais links -->
  </div>
</body>

</html>
