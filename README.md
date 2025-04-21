# eZbita
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ремонт телефонов</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      color: #333;
    }
    header {
      background: #1e88e5;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    .phone {
      font-size: 1.2em;
      margin-top: 5px;
    }
    section {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    .button {
      display: inline-block;
      padding: 12px 20px;
      background: #1e88e5;
      color: white;
      text-decoration: none;
      border-radius: 4px;
      margin-top: 10px;
    }
    footer {
      text-align: center;
      padding: 10px;
      background: #ccc;
    }
    @media (max-width: 600px) {
      header, section {
        padding: 15px;
      }
      .button {
        width: 100%;
        text-align: center;
        box-sizing: border-box;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Ремонт телефонов</h1>
    <div class="phone">Позвоните: <a href="tel:+48573682178" style="color:white;">+48 573 682 178</a></div>
  </header>

  <section>
    <h2>Наши услуги</h2>
    <ul>
      <li>Замена экрана</li>
      <li>Ремонт зарядного гнезда</li>
      <li>Замена аккумулятора</li>
      <li>Восстановление после воды</li>
    </ul>

    <h2>Почему мы?</h2>
    <ul>
      <li>Быстро и качественно</li>
      <li>Оригинальные запчасти</li>
      <li>Гарантия на ремонт</li>
    </ul>

    <a class="button" href="tel:+48573682178">Позвонить сейчас</a>
  </section>

  <footer>
    &copy; 2025 Ремонт телефонов
  </footer>
</body>
</html>