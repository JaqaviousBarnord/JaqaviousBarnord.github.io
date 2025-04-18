<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tha Bronx 3 - Cash Buyer</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');

    body {
      background: linear-gradient(145deg, #1a1a1a, #111);
      color: #fff;
      font-family: 'Bebas Neue', sans-serif;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }

    .cash-card {
      background: #222;
      border: 3px solid #00ff88;
      box-shadow: 0 0 25px #00ff8855;
      border-radius: 16px;
      padding: 2rem 3rem;
      text-align: center;
      max-width: 400px;
      animation: glow 2s infinite alternate;
    }

    @keyframes glow {
      from {
        box-shadow: 0 0 20px #00ff88;
      }
      to {
        box-shadow: 0 0 35px #00ff88, 0 0 15px #00ff88 inset;
      }
    }

    .cash-card h1 {
      font-size: 3rem;
      margin-bottom: 10px;
      text-shadow: 0 0 10px #00ff88;
    }

    .cash-card p {
      font-size: 1.2rem;
      margin-bottom: 20px;
      color: #aaa;
    }

    .buy-button {
      background: #00ff88;
      color: #000;
      border: none;
      font-size: 1.5rem;
      padding: 0.8rem 2rem;
      border-radius: 12px;
      cursor: pointer;
      transition: background 0.3s, transform 0.2s;
    }

    .buy-button:hover {
      background: #00ffaa;
      transform: scale(1.05);
    }

    .money-icon {
      font-size: 3rem;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="cash-card">
    <div class="money-icon">💵</div>
    <h1>Tha Bronx 3</h1>
    <p>In-Game Cash Buyer</p>
    <button class="buy-button">Cop Now</button>
  </div>
</body>
</html>
