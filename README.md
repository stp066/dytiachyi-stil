<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Супер Продукт — Купуй Зараз!</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #007bff;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    .product {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem;
    }
    .product img {
      width: 300px;
      max-width: 90%;
      border-radius: 10px;
      margin-bottom: 1rem;
    }
    .btn {
      background-color: #28a745;
      color: white;
      padding: 1rem 2rem;
      border: none;
      border-radius: 8px;
      font-size: 1.2rem;
      cursor: pointer;
      text-decoration: none;
    }
    .features {
      background-color: #fff;
      padding: 2rem;
      text-align: center;
    }
    .features h2 {
      margin-bottom: 1rem;
    }
    .feature-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
    }
    .feature {
      background-color: #e9ecef;
      padding: 1rem;
      border-radius: 8px;
      width: 250px;
    }
    footer {
      background-color: #343a40;
      color: white;
      text-align: center;
      padding: 1rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>🔥 Супер Продукт для Тебе</h1>
    <p>Ідеальний вибір за суперціною</p>
  </header>

  <section class="product">
    <img src="https://via.placeholder.com/300x300.png?text=Фото+Продукту" alt="Наш продукт">
    <h2>Назва продукту</h2>
    <p>Опис продукту, коротко і переконливо. Переваги, вигоди, актуальність.</p>
    <a class="btn" href="https://t.me/yourtelegram" target="_blank">Замовити зараз</a>
  </section>

  <section class="features">
    <h2>Чому обирають нас?</h2>
    <div class="feature-list">
      <div class="feature">✅ Якість гарантуємо</div>
      <div class="feature">🚚 Швидка доставка</div>
      <div class="feature">💸 Краща ціна</div>
      <div class="feature">📦 Оплата при отриманні</div>
    </div>
  </section>

  <footer>
    &copy; 2025 SuperShop. Усі права захищено.
  </footer>

</body>
</html>
