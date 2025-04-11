# darkbloom-client
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>DarkBloom Client</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: url('https://images.unsplash.com/photo-1586281380349-d2aa0cfafa7b') no-repeat center center fixed;
      background-size: cover;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      backdrop-filter: brightness(0.5);
    }

    .container {
      background: rgba(0, 0, 0, 0.6);
      padding: 40px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 0 20px #ff00aa66;
    }

    p {
      font-size: 1.2em;
      color: #ddd;
    }

    .button-container {
      display: flex;
      gap: 20px;
      justify-content: center;
      margin-top: 20px;
    }

    .buy-button {
      background-color: #ff00aa;
      border: none;
      color: white;
      padding: 15px 30px;
      font-size: 1em;
      border-radius: 12px;
      cursor: pointer;
      transition: 0.3s;
    }

    .buy-button:hover {
      background-color: #ff33bb;
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <div class="container">
    <p>Чит-клиент нового поколения в стиле сакуры. Быстрый. Красивый. Убийственный.</p>
    <div class="button-container">
      <button class="buy-button" onclick="window.location.href='https://t.me/Convictedi'">Купить через Telegram</button>
      <button class="buy-button" onclick="window.location.href='https://funpay.com/users/12597508/'">Оплатить через FanPay</button>
    </div>
  </div>
</body>
</html>
