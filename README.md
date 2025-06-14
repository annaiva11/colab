```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой Сайт</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f4f4f4;
        }
        header {
            background: #35424a;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        nav ul {
            padding: 0;
            list-style: none;
        }
        nav li {
            display: inline;
            margin-right: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        main {
            padding: 20px 0;
        }
        footer {
            background: #35424a;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Добро пожаловать на мой сайт</h1>
            <nav>
                <ul>
                    <li><a href="#">Главная</a></li>
                    <li><a href="#">О нас</a></li>
                    <li><a href="#">Контакты</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container">
        <section>
            <h2>О нашем проекте</h2>
            <p>Это простой пример сайта, созданного с помощью HTML и CSS.</p>
        </section>

        <section>
            <h2>Наши услуги</h2>
            <ul>
                <li>Веб-разработка</li>
                <li>Дизайн</li>
                <li>Консультации</li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Мой Сайт. Все права защищены.</p>
    </footer>
</body>
</html>
